> Mermaid 流程图语法详解，集成自官方文档 mermaid.js.org/syntax/flowchart.html。
> 有道云笔记中使用 ` ``` ` 代码块包裹；并非所有新版特性都已被有道云支持，以实际渲染为准并对照 blacklist.md。

## 附录 B：Mermaid 流程图语法详解（集成自官方文档）

> 集成自 [mermaid 官方仓库](https://github.com/mermaid-js/mermaid) 指向的官方文档 [Flowchart 语法页](https://mermaid.js.org/syntax/flowchart.html)。
> 有道云笔记中使用 ` ``` ` 代码块包裹（首行 `graph` 或 `flowchart`）；并非所有新版特性都已被有道云编辑器支持，以实际渲染效果为准。

### B.1 图类型与方向声明

首行写 `graph` 或 `flowchart`（二者等价），后接方向：

- `TB` / `TD` - 从上到下（top bottom / top down）
- `BT` - 从下到上（bottom top）
- `RL` - 从右到左（right left）
- `LR` - 从左到右（left right）

```text
flowchart TD
```

### B.2 节点形状完整列表

| 语法写法 | 形状 |
| --- | --- |
| `id[文字]` | 矩形（默认） |
| `id(文字)` | 圆角矩形 |
| `id([文字])` | 体育场形（stadium） |
| `id[[文字]]` | 子程序形（subroutine） |
| `id[(文字)]` | 圆柱形 / 数据库 |
| `id((文字))` | 圆形 |
| `id(((文字)))` | 双圆形 |
| `id>文字]` | 非对称形（仅右侧） |
| `id{文字}` | 菱形（决策判断） |
| `id{{文字}}` | 六边形 |
| `id[/文字/]` | 平行四边形 |
| `id[\文字\]` | 平行四边形（反向） |
| `id[/文字\]` | 梯形 |
| `id[\文字/]` | 梯形（反向） |

> v11.3.0+ 还支持新语法 `A@{ shape: rect, label: "文字" }`，提供 30 余种新形状（如 `cyl` 数据库、`diam` 决策、`doc` 文档、`person` 人员等）。

### B.3 连接线（边）类型完整列表

| 语法写法 | 效果 |
| --- | --- |
| `A-->B` | 带箭头实线 |
| `A---B` | 无箭头实线（开放连线） |
| `A---\|文字\|B` 或 `A-- 文字 ---B` | 无箭头连线带文字 |
| `A-->|文字|B` 或 `A-- 文字 -->B` | 箭头线带文字 |
| `A-.->B` | 虚线箭头 |
| `A-. 文字 .->B` | 虚线箭头带文字 |
| `A==>B` | 粗实线箭头 |
| `A== 文字 ==>B` | 粗实线箭头带文字 |
| `A~~~B` | 不可见连线（仅布局用） |
| `A--oB` | 圆形端点连线 |
| `A--xB` | 叉形端点连线 |
| `B<-->C` | 双向箭头 |
| `Ao--oB` / `Cx--xD` | 双向圆端 / 双向叉端 |

**连线长度的加长写法**（跨越更多层级）：在中间加短横线，箭头/虚线/粗线同理：

| 长度 | 实线 | 箭头 | 粗线 | 虚线 |
| --- | --- | --- | --- | --- |
| 1 | `---` | `-->` | `===` | `-.-` |
| 2 | `----` | `--->` | `====` | `-..-` |
| 3 | `-----` | `---->` | `=====` | `-...-` |

**链式与多节点写法：**

```text
A -- text --> B -- text2 --> C    （链式）
a --> b & c --> d                 （一入多出）
A & B --> C & D                   （多入多出）
```

### B.4 子图（subgraph）

```text
flowchart TB
    subgraph 标题或ID
        节点定义...
    end
    subgraph one [显示标题]
        a1 --> a2
    end
    one --> two
```

- flowchart 类型下子图之间可以直接连线（如 `one --> two`）
- 子图内可用 `direction LR` 等单独设置方向；**但若子图节点连接到了外部节点，其 direction 会被忽略并继承父图方向**

### B.5 节点 ID 与文字规则

- 节点 ID 即默认显示内容：单独写 `id` 即可成为节点
- ID 与文字分离：`id1[文字内容]`；同一 ID 多次定义时**以最后一次为准**
- 含特殊字符（括号、Unicode 表情等）需用双引号包裹：`id1["This is the (text) in the box"]`
- HTML 实体转义：`#quot;`、`#9829;`；`#` 本身写作 `#35;`
- Markdown 语法嵌套（v9.4+）：`` markdown["`This **is** _Markdown_`"] ``（需配置 `htmlLabels: false`）
- ⚠️ 节点文字含小写 `end` 会破坏语法解析，须写成大写 `End` 或 `END`
- ⚠️ 连线目标首字母为小写 `o` 或 `x` 时（如 `A---oB`），会被解析为圆端/叉端连线，需加空格或改大写
- 语句末尾分号 `;` 可省略

### B.6 样式与 classDef

**单节点直接样式：**

```text
style id1 fill:#f9f,stroke:#333,stroke-width:4px
style id2 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
```

**classDef 类样式（推荐）：**

```text
classDef className fill:#f9f,stroke:#333,stroke-width:4px;
class nodeId1 className
class nodeId1,nodeId2 className
```

**`:::` 简写操作符：**

```text
A:::someclass --> B
classDef someclass fill:#f96
```

- 名为 `default` 的类会应用到所有未指定类的节点：`classDef default fill:#f9f,stroke:#333`
- 边样式：`linkStyle 3 stroke:#ff3,stroke-width:4px`；多条边：`linkStyle 1,2,7 color:blue`（序号从 0 开始按声明顺序计数）
- 曲线样式可选：`basis`、`linear`、`monotoneX`、`natural`、`step` 等（图级配置 `flowchart.curve`）
- 不建议用外部 CSS 覆盖节点样式（Mermaid 内部样式带 `!important`），统一用 `classDef`

### B.7 交互与其他

- 点击交互：`click A callback "提示文字"` 或 `click B "https://example.com" _blank`（后者需 `securityLevel: 'loose'`）
- 注释：`%%` 开头独立成行
- 图标：`A[fa:fa-twitter Twitter]`（需加载 FontAwesome）；v11.7.0+ 支持注册图标包

> 注：有道云笔记内置的 Mermaid 版本可能低于官方最新版，上述高级特性（@{ } 新形状语法、边动画等）在笔记中不一定可用，基础形状、连线、子图、classDef 通常均可正常渲染。
