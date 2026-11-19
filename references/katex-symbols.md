> KaTeX 符号全表，集成自官方文档 katex.org/docs/supported.html（20 类、976 个写法）。
> 用法：多行公式写在 ` ```math ` 与 ` ``` ` 之间，行内公式写在 `` `$` `` 与 `` `$` `` 之间。
> 查找方式：先看下方章节目录定位类别，再用 grep 搜索符号关键词。

## 附录 A：KaTeX 符号全表（集成自官方文档）

> 集成自 KaTeX 官方文档 [Supported Functions](https://katex.org/docs/supported.html) 的全部 20 类符号章节（共 976 个写法）。
> 用法：多行公式写在 ` ```math ` 与 ` ``` ` 之间，行内公式写在 `` `$` `` 与 `` `$` `` 之间（用法详见第 7 节）。
> 部分常用符号标注了「→ 渲染字符」便于对照；其余写法在公式环境中输入即可渲染出对应图形。

### A.1 重音符号（Accents）（51 个）

`a'`　`\tilde{a}`　`\mathring{g}`　`a''`　`\widetilde{ac}`　`\overgroup{AB}`　`a^{\prime}`
`\utilde{AB}`　`\undergroup{AB}`　`\acute{a}`　`\vec{F}`　`\Overrightarrow{AB}`　`\bar{y}`
`\overleftarrow{AB}`　`\overrightarrow{AB}`　`\breve{a}`　`\underleftarrow{AB}`
`\underrightarrow{AB}`　`\check{a}`　`\overleftharpoon{ac}`　`\overrightharpoon{ac}`　`\dot{a}`
`\overleftrightarrow{AB}`　`\overbrace{AB}`　`\ddot{a}`　`\underleftrightarrow{AB}`
`\underbrace{AB}`　`\dddot{a}`　`\overline{AB}`　`\overbracket{AB}`　`\ddddot{a}`
`\underline{AB}`　`\underbracket{AB}`　`\grave{a}`　`\underbar{X}`　`\overlinesegment{AB}`
`\hat{\theta}`　`\widecheck{ac}`　`\underlinesegment{AB}`　`\widehat{ac}`　`\'{a}`　`\~{a}`　`\.{a}`
`\H{a}`　`` \`{a} ``　`\={a}`　`\"{a}`　`\v{a}`　`\^{a}`　`\u{a}`　`\r{a}`

### A.2 定界符 / 括号（Delimiters）（60 个）

`( )`　`\lparen`　`⌈ ⌉`　`\lceil`　`\uparrow`（→ ↑）　`[ ]`　`\lbrack`　`⌊ ⌋`　`\lfloor`　`\downarrow`（→ ↓）
`\{ \}`　`\lbrace`　`⎰⎱`　`\lmoustache`　`\updownarrow`　`⟨ ⟩`　`\langle`　`⟮ ⟯`　`\lgroup`　`\Uparrow`　`|`
`\vert`　`┌ ┐`　`\ulcorner`　`\Downarrow`　`\|`　`\Vert`　`└ ┘`　`\llcorner`　`\Updownarrow`　`\lvert`
`\lVert`　`\left.`　`\right.`　`\backslash`　`\lang`　`\lt \gt`　`⟦ ⟧`　`\llbracket`　`/`
`\lBrace \rBrace`　`\left`　`\big`　`\bigl`　`\bigm`　`\bigr`　`\middle`　`\Big`　`\Bigl`　`\Bigm`　`\Bigr`
`\right`　`\bigg`　`\biggl`　`\biggm`　`\biggr`　`\Bigg`　`\Biggl`　`\Biggm`　`\Biggr`

### A.3 环境（Environments）（24 个）

`\begin{matrix}`　`\begin{array}{cc}`　`\begin{pmatrix}`　`\begin{bmatrix}`　`\begin{vmatrix}`
`\begin{Vmatrix}`　`\begin{Bmatrix}`　`\def\arraystretch{1.5}`　`x = \begin{cases}`
`\begin{rcases}`　`\begin{smallmatrix}`　`\sum_{`　`\begin{equation}`　`\begin{align}`
`\begin{gather}`　`\begin{alignat}{2}`　`\begin{CD}`　`darray`　`displaystyle`　`matrix*`
`\begin{matrix*}[r]`　`equation*`　`\nonumber`　`gathered`

### A.4 HTML（部分输出模式支持）（11 个）

`\href{https://katex.org/}{\KaTeX}`　`\url{https://katex.org/}`
`\includegraphics[height=0.8em, totalheight=0.9em, width=0.9em, alt=KA logo]{https://katex.org/img/khan-academy.png}`
`…<span id="bar" class="enclosing">…x…</span>…`　`\htmlId{bar}{x}`
`…<span class="enclosing foo">…x…</span>…`　`\htmlClass{foo}{x}`
`…<span style="color: red;" class="enclosing">…x…</span>…`　`\htmlStyle{color: red;}{x}`
`…<span data-foo="a" data-bar="b" class="enclosing">…x…</span>…`
`\htmlData{foo=a, bar=b}{x}`

### A.5 字母与 Unicode（含希腊字母）（110 个）

`\Alpha`　`\Beta`　`\Gamma`（→ Γ）　`\Delta`（→ Δ）　`\Epsilon`　`\Zeta`　`\Eta`　`\Theta`（→ Θ）　`\Iota`
`\Kappa`　`\Lambda`（→ Λ）　`\Mu`　`\Nu`　`\Xi`（→ Ξ）　`\Omicron`　`\Pi`（→ Π）　`\Rho`　`\Sigma`（→ Σ）　`\Tau`
`\Upsilon`（→ Υ）　`\Phi`（→ Φ）　`\Chi`　`\Psi`（→ Ψ）　`\Omega`（→ Ω）　`\varGamma`　`\varDelta`
`\varTheta`　`\varLambda`　`\varXi`　`\varPi`　`\varSigma`　`\varUpsilon`　`\varPhi`　`\varPsi`
`\varOmega`　`\alpha`（→ α）　`\beta`（→ β）　`\gamma`（→ γ）　`\delta`（→ δ）　`\epsilon`（→ ϵ）
`\zeta`（→ ζ）　`\eta`（→ η）　`\theta`（→ θ）　`\iota`（→ ι）　`\kappa`（→ κ）　`\lambda`（→ λ）　`\mu`（→ μ）
`\nu`（→ ν）　`\xi`（→ ξ）　`\omicron`（→ ο）　`\pi`（→ π）　`\rho`（→ ρ）　`\sigma`（→ σ）　`\tau`（→ τ）
`\upsilon`（→ υ）　`\phi`（→ ϕ）　`\chi`（→ χ）　`\psi`（→ ψ）　`\omega`（→ ω）　`\varepsilon`（→ ε）
`\varkappa`　`\vartheta`（→ ϑ）　`\thetasym`　`\varpi`（→ ϖ）　`\varrho`（→ ϱ）　`\varsigma`（→ ς）
`\varphi`（→ φ）　`\digamma`　`\imath`　`\nabla`（→ ∇）　`\Im`（→ ℑ）　`\Reals`　`\text{\OE}`　`\jmath`
`\partial`（→ ∂）　`\image`　`\wp`　`\text{\o}`　`\aleph`（→ ℵ）　`\Game`　`\Bbbk`　`\weierp`　`\text{\O}`
`\alef`　`\Finv`　`\N`　`\Z`　`\text{\ss}`　`\alefsym`　`\cnums`　`\natnums`　`\text{\aa}`　`\text{\i}`
`\beth`（→ ℶ）　`\Complex`　`\R`　`\text{\AA}`　`\text{\j}`　`\gimel`（→ ℷ）　`\ell`（→ ℓ）　`\Re`（→ ℜ）
`\text{\ae}`　`\daleth`（→ ℸ）　`\hbar`（→ ℏ）　`\real`　`\text{\AE}`　`\eth`　`\hslash`　`\reals`
`\text{\oe}`

### A.6 注释（Annotation）（13 个）

`\cancel{5}`　`\overbrace{a+b+c}^{\text{note}}`　`\bcancel{5}`
`\underbrace{a+b+c}_{\text{note}}`　`\xcancel{ABC}`　`\not =`　`\text{\sout{abc}}`
`\boxed{\pi=\frac c d}`　`$a_{\angl n}`　`a_\angln`　`\overbracket{a+b+c}^{\text{note}}`
`\underbracket{a+b+c}_{\text{note}}`　`\phase{-78^\circ}`

### A.7 纵向排版（Vertical Layout）（12 个）

`x_n`　`\stackrel{!}{=}`　`a \atop b`　`e^x`　`\overset{!}{=}`　`a\raisebox{0.25em}{$b$}c`
`\reflectbox{KaTeX}`　`\mathreflectbox{x^2}`　`_u^o`　`\underset{!}{=}`
`a+\left(\vcenter{\hbox{$\frac{\frac a b}c$}}\right)`　`\sum_{\substack{0<i<m\\0<j<n}}`

### A.8 重叠与间距（Overlap and Spacing）（33 个）

`{=}\mathllap{/\,}`　`\left(x^{\smash{2}}\right)`　`\mathrlap{\,/}{=}`　`\sqrt{\smash[b]{y}}`
`\,`　`\kern{distance}`　`\thinspace`　`\mkern{distance}`　`\>`　`\mskip{distance}`　`\:`
`\hskip{distance}`　`\medspace`　`\hspace{distance}`　`\;`　`\hspace*{distance}`　`\thickspace`
`\phantom{content}`　`\enspace`　`\hphantom{content}`　`\quad`　`\vphantom{content}`　`\qquad`　`\!`
`~`　`\negthinspace`　`\<space>`　`\negmedspace`　`\nobreakspace`　`\negthickspace`　`\space`
`\mathstrut`　`\vphantom{(}`

### A.9 逻辑与集合论（Logic and Set Theory）（30 个）

`\forall`（→ ∀）　`\complement`　`\therefore`（→ ∴）　`\emptyset`（→ ∅）　`\exists`（→ ∃）　`\subset`（→ ⊂）
`\because`（→ ∵）　`\empty`　`\exist`　`\supset`（→ ⊃）　`\mapsto`（→ ↦）　`\varnothing`（→ ∅）
`\nexists`（→ ∄）　`\mid`（→ ∣）　`\to`（→ →）　`\implies`（→ ⇒）　`\in`（→ ∈）　`\land`　`\gets`
`\impliedby`（→ ⇐）　`\isin`　`\lor`　`\leftrightarrow`（→ ↔）　`\iff`（→ ⇔）　`\notin`（→ ∉）　`\ni`（→ ∋）
`\notni`　`\neg`（→ ¬）　`\Set{ x | x<\frac 1 2 }`　`\set{x|x<5}`

### A.10 宏（Macros）（10 个）

`\def\foo{x^2} \foo + \foo`　`\gdef\foo#1{#1^2} \foo{y} + \foo{y}`
`\edef\macroname#1#2…{definition to be expanded}`
`\xdef\macroname#1#2…{definition to be expanded}`　`\let\foo=\bar`　`\futurelet\foo\bar x`
`\global\def\macroname#1#2…{definition}`　`\newcommand\macroname[numargs]{definition}`
`\renewcommand\macroname[numargs]{definition}`
`\providecommand\macroname[numargs]{definition}`

### A.11 大型运算符（Big Operators）（20 个）

`\sum`（→ ∑）　`\prod`（→ ∏）　`\bigotimes`　`\bigvee`　`\int`（→ ∫）　`\coprod`（→ ∐）　`\bigoplus`
`\bigwedge`　`\iint`（→ ∬）　`\intop`　`\bigodot`　`\bigcap`　`\iiint`（→ ∭）　`\smallint`　`\biguplus`
`\bigcup`　`\oint`（→ ∮）　`\oiint`　`\oiiint`　`\bigsqcup`

### A.12 二元运算符（Binary Operators）（68 个）

`+`　`\cdot`　`\gtrdot`　`x \pmod a`　`-`　`\cdotp`　`\intercal`　`x \pod a`　`/`　`\centerdot`　`\land`
`\rhd`　`*`　`\circ`（→ ∘）　`\leftthreetimes`　`\rightthreetimes`　`\amalg`　`\circledast`　`\ldotp`
`\rtimes`　`\And`　`\circledcirc`　`\lor`　`\setminus`（→ ∖）　`\ast`（→ ∗）　`\circleddash`　`\lessdot`
`\smallsetminus`　`\barwedge`　`\Cup`　`\lhd`　`\sqcap`　`\bigcirc`　`\cup`（→ ∪）　`\ltimes`　`\sqcup`
`\bmod`　`\curlyvee`　`x\mod a`　`\times`（→ ×）　`\boxdot`　`\curlywedge`　`\mp`（→ ∓）　`\unlhd`
`\boxminus`　`\div`（→ ÷）　`\odot`（→ ⊙）　`\unrhd`　`\boxplus`　`\divideontimes`　`\ominus`（→ ⊖）
`\uplus`　`\boxtimes`　`\dotplus`　`\oplus`（→ ⊕）　`\vee`　`\bullet`（→ ∙）　`\doublebarwedge`
`\otimes`（→ ⊗）　`\veebar`　`\Cap`　`\doublecap`　`\oslash`（→ ⊘）　`\wedge`　`\cap`（→ ∩）　`\doublecup`
`\pm`（→ ±）　`\wr`

### A.13 分式与二项式（Fractions and Binomials）（14 个）

`\frac{a}{b}`　`\tfrac{a}{b}`　`\genfrac ( ] {2pt}{1}a{a+1}`　`{a \over b}`　`\dfrac{a}{b}`
`{a \above{2pt} b+1}`　`a/b`　`\cfrac{a}{1 + \cfrac{1}{b}}`　`\binom{n}{k}`　`\dbinom{n}{k}`
`{n\brace k}`　`{n \choose k}`　`\tbinom{n}{k}`　`{n\brack k}`

### A.14 数学函数名（Math Operators）（54 个）

`\arcsin`　`\cosec`　`\deg`（→ °）　`\sec`　`\arccos`　`\cosh`　`\dim`　`\sin`　`\arctan`　`\cot`　`\exp`
`\sinh`　`\arctg`　`\cotg`　`\hom`　`\sh`　`\arcctg`　`\coth`　`\ker`　`\tan`　`\arg`　`\csc`　`\lg`　`\tanh`
`\ch`　`\ctg`　`\ln`　`\tg`　`\cos`　`\cth`　`\log`　`\th`　`\operatorname{f}`　`\argmax`　`\injlim`　`\min`
`\varinjlim`　`\argmin`　`\lim`　`\plim`　`\varliminf`　`\det`　`\liminf`　`\Pr`　`\varlimsup`　`\gcd`
`\limsup`　`\projlim`　`\varprojlim`　`\inf`　`\max`　`\sup`　`\operatorname*{f}`
`\operatornamewithlimits{f}`

### A.15 关系符（Relations）（128 个）

`=`　`\doteqdot`　`\lessapprox`　`\smile`　`<`　`\eqcirc`　`\lesseqgtr`　`\sqsubset`　`>`　`\eqcolon`
`\lesseqqgtr`　`\sqsubseteq`　`:`　`\Eqcolon`　`\lessgtr`　`\sqsupset`　`\approx`（→ ≈）　`\eqqcolon`
`\lesssim`　`\sqsupseteq`　`\approxcolon`　`\Eqqcolon`　`\ll`（→ ≪）　`\Subset`　`\approxcoloncolon`
`\eqsim`　`\lll`　`\subset`（→ ⊂）　`\approxeq`　`\eqslantgtr`　`\llless`　`\subseteq`（→ ⊆）　`\asymp`
`\eqslantless`　`\lt`　`\subseteqq`　`\backepsilon`　`\equiv`（→ ≡）　`\mid`（→ ∣）　`\succ`　`\backsim`
`\fallingdotseq`　`\models`　`\succapprox`　`\backsimeq`　`\frown`　`\multimap`　`\succcurlyeq`
`\between`　`\ge`（→ ≥）　`\origof`　`\succeq`　`\bowtie`　`\geq`（→ ≥）　`\owns`　`\succsim`　`\bumpeq`
`\geqq`　`\parallel`（→ ∥）　`\Supset`　`\Bumpeq`　`\geqslant`　`\perp`（→ ⊥）　`\supset`（→ ⊃）　`\circeq`
`\gg`（→ ≫）　`\pitchfork`　`\supseteq`（→ ⊇）　`\colonapprox`　`\ggg`　`\prec`　`\supseteqq`
`\Colonapprox`　`\gggtr`　`\precapprox`　`\thickapprox`　`\coloneq`　`\gt`　`\preccurlyeq`
`\thicksim`　`\Coloneq`　`\gtrapprox`　`\preceq`　`\trianglelefteq`　`\coloneqq`　`\gtreqless`
`\precsim`　`\triangleq`　`\Coloneqq`　`\gtreqqless`　`\propto`（→ ∝）　`\trianglerighteq`
`\colonsim`　`\gtrless`　`\risingdotseq`　`\varpropto`　`\Colonsim`　`\gtrsim`　`\shortmid`
`\vartriangle`　`\cong`（→ ≅）　`\imageof`　`\shortparallel`　`\vartriangleleft`　`\curlyeqprec`
`\in`（→ ∈）　`\sim`（→ ∼）　`\vartriangleright`　`\curlyeqsucc`　`\Join`　`\simcolon`　`\vcentcolon`
`\dashv`（→ ⊣）　`\le`（→ ≤）　`\simcoloncolon`　`\vdash`（→ ⊢）　`\dblcolon`　`\leq`（→ ≤）　`\simeq`（→ ≃）
`\vDash`　`\doteq`　`\leqq`　`\smallfrown`　`\Vdash`　`\Doteq`　`\leqslant`　`\smallsmile`　`\Vvdash`

### A.16 否定关系符（Negated Relations）（58 个）

`\gnapprox`　`\ngeqslant`　`\nsubseteq`　`\precneqq`　`\gneq`　`\ngtr`　`\nsubseteqq`　`\precnsim`
`\gneqq`　`\nleq`　`\nsucc`　`\subsetneq`　`\gnsim`　`\nleqq`　`\nsucceq`　`\subsetneqq`　`\gvertneqq`
`\nleqslant`　`\nsupseteq`　`\succnapprox`　`\lnapprox`　`\nless`　`\nsupseteqq`　`\succneqq`　`\lneq`
`\nmid`（→ ∤）　`\ntriangleleft`　`\succnsim`　`\lneqq`　`\notin`（→ ∉）　`\ntrianglelefteq`
`\supsetneq`　`\lnsim`　`\notni`　`\ntriangleright`　`\supsetneqq`　`\lvertneqq`　`\nparallel`
`\ntrianglerighteq`　`\varsubsetneq`　`\ncong`　`\nprec`　`\nvdash`　`\varsubsetneqq`　`\ne`（→ ≠）
`\npreceq`　`\nvDash`　`\varsupsetneq`　`\neq`（→ ≠）　`\nshortmid`　`\nVDash`　`\varsupsetneqq`
`\ngeq`　`\nshortparallel`　`\nVdash`　`\ngeqq`　`\nsim`　`\precnapprox`

### A.17 箭头（Arrows）（111 个）

`\circlearrowleft`（→ ↺）　`\leftharpoonup`　`\rArr`　`\circlearrowright`（→ ↻）
`\leftleftarrows`（→ ⇇）　`\rarr`　`\curvearrowleft`（→ ↶）　`\leftrightarrow`（→ ↔）　`\restriction`
`\curvearrowright`（→ ↷）　`\Leftrightarrow`（→ ⇔）　`\rightarrow`（→ →）　`\Darr`　`\leftrightarrows`
`\Rightarrow`（→ ⇒）　`\dArr`　`\leftrightharpoons`（→ ⇋）　`\rightarrowtail`　`\darr`
`\leftrightsquigarrow`　`\rightharpoondown`　`\dashleftarrow`　`\Lleftarrow`（→ ⇚）
`\rightharpoonup`　`\dashrightarrow`　`\longleftarrow`（→ ⟵）　`\rightleftarrows`
`\downarrow`（→ ↓）　`\Longleftarrow`　`\rightleftharpoons`（→ ⇌）　`\Downarrow`
`\longleftrightarrow`（→ ⟷）　`\rightrightarrows`（→ ⇉）　`\downdownarrows`（→ ⇊）
`\Longleftrightarrow`　`\rightsquigarrow`　`\downharpoonleft`　`\longmapsto`（→ ⟼）
`\Rrightarrow`（→ ⇛）　`\downharpoonright`　`\longrightarrow`（→ ⟶）　`\Rsh`　`\gets`
`\Longrightarrow`（→ ⟹）　`\searrow`（→ ↘）　`\Harr`　`\looparrowleft`　`\swarrow`（→ ↙）　`\hArr`
`\looparrowright`　`\to`（→ →）　`\harr`　`\Lrarr`　`\twoheadleftarrow`　`\hookleftarrow`（→ ↩）
`\lrArr`　`\twoheadrightarrow`　`\hookrightarrow`（→ ↪）　`\lrarr`　`\Uarr`　`\iff`（→ ⇔）　`\Lsh`
`\uArr`　`\impliedby`（→ ⇐）　`\mapsto`（→ ↦）　`\uarr`　`\implies`（→ ⇒）　`\nearrow`（→ ↗）
`\uparrow`（→ ↑）　`\Larr`　`\nleftarrow`　`\Uparrow`　`\lArr`　`\nLeftarrow`　`\updownarrow`　`\larr`
`\nleftrightarrow`　`\Updownarrow`　`\leadsto`　`\nLeftrightarrow`　`\upharpoonleft`
`\leftarrow`（→ ←）　`\nrightarrow`　`\upharpoonright`　`\Leftarrow`（→ ⇐）　`\nRightarrow`
`\upuparrows`（→ ⇈）　`\leftarrowtail`　`\nwarrow`（→ ↖）　`\mapsfrom`　`\leftharpoondown`　`\Rarr`
`\xleftarrow{abc}`　`\xrightarrow[under]{over}`　`\xLeftarrow{abc}`　`\xRightarrow{abc}`
`\xleftrightarrow{abc}`　`\xLeftrightarrow{abc}`　`\xhookleftarrow{abc}`
`\xhookrightarrow{abc}`　`\xtwoheadleftarrow{abc}`　`\xtwoheadrightarrow{abc}`
`\xleftharpoonup{abc}`　`\xrightharpoonup{abc}`　`\xleftharpoondown{abc}`
`\xrightharpoondown{abc}`　`\xleftrightharpoons{abc}`　`\xrightleftharpoons{abc}`
`\xtofrom{abc}`　`\xmapsto{abc}`　`\xlongequal{abc}`

### A.18 特殊记法（Special Notation）（6 个）

`\bra{\phi}`　`\ket{\psi}`　`\braket{\phi|\psi}`　`\Bra{\phi}`　`\Ket{\psi}`
`\Braket{ ϕ | \frac{∂^2}{∂ t^2} | ψ }`

### A.19 样式、颜色、字号与字体（Style, Color, Size, and Font）（49 个）

`\mathrm{Ab0}`　`\mathbf{Ab0}`　`\mathsf{Ab0}`　`\mathnormal{Ab0}`　`\textbf{Ab0}`　`\textsf{Ab0}`
`\textrm{Ab0}`　`\bf Ab0`　`\sf Ab0`　`\rm Ab0`　`\bold{Ab0}`　`\mathsfit{Ab0}`　`\textnormal{Ab0}`
`\boldsymbol{Ab0}`　`\Bbb{AB}`　`\text{Ab0}`　`\bm{Ab0}`　`\mathbb{AB}`　`\textup{Ab0}`
`\textmd{Ab0}`　`\frak{Ab0}`　`\mathit{Ab0}`　`\mathtt{Ab0}`　`\mathfrak{Ab0}`　`\textit{Ab0}`
`\texttt{Ab0}`　`\mathcal{AB0}`　`\it Ab0`　`\tt Ab0`　`\cal AB0`　`\emph{Ab0}`　`\mathscr{AB}`
`\Huge AB`　`\normalsize AB`　`\huge AB`　`\small AB`　`\LARGE AB`　`\footnotesize AB`　`\Large AB`
`\scriptsize AB`　`\large AB`　`\tiny AB`　`\displaystyle\sum_{i=1}^n`　`\textstyle\sum_{i=1}^n`
`\scriptstyle x`　`\scriptscriptstyle x`　`\lim\limits_x`　`\lim\nolimits_x`　`\verb!x^2!`

### A.20 符号与标点（Symbols and Punctuation）（114 个）

`% comment`　`\dots`　`\KaTeX`　`\%`　`\cdots`（→ ⋯）　`\LaTeX`　`\#`　`\ddots`（→ ⋱）　`\TeX`　`\&`
`\ldots`（→ …）　`\nabla`（→ ∇）　`\_`　`\vdots`（→ ⋮）　`\infty`（→ ∞）　`\text{\textunderscore}`　`\dotsb`
`\infin`　`\text{--}`　`\dotsc`　`\checkmark`（→ ✓）　`\text{\textendash}`　`\dotsi`　`\dag`
`\text{---}`　`\dotsm`　`\dagger`（→ †）　`\text{\textemdash}`　`\dotso`　`\text{\textdagger}`
`\text{\textasciitilde}`　`\sdot`　`\ddag`　`\text{\textasciicircum}`　`\mathellipsis`
`\ddagger`（→ ‡）　`` ` ``　`\text{\textellipsis}`　`\text{\textdaggerdbl}`
`\text{\textquoteleft}`　`\Box`　`\Dagger`　`\lq`　`\square`　`\angle`（→ ∠）
`\text{\textquoteright}`　`\blacksquare`　`\measuredangle`　`\rq`　`\triangle`　`\sphericalangle`
`\text{\textquotedblleft}`　`\triangledown`　`\top`（→ ⊤）　`"`　`\triangleleft`　`\bot`（→ ⊥）
`\text{\textquotedblright}`　`\triangleright`　`\$`　`\colon`　`\bigtriangledown`
`\text{\textdollar}`　`\backprime`　`\bigtriangleup`　`\pounds`　`\prime`（→ ′）　`\blacktriangle`
`\mathsterling`　`\text{\textless}`　`\blacktriangledown`　`\text{\textsterling}`
`\text{\textgreater}`　`\blacktriangleleft`　`\yen`　`\text{\textbar}`　`\blacktriangleright`
`\surd`　`\text{\textbardbl}`　`\diamond`　`\degree`　`\text{\textbraceleft}`　`\Diamond`
`\text{\textdegree}`　`\text{\textbraceright}`　`\lozenge`　`\mho`　`\text{\textbackslash}`
`\blacklozenge`　`\diagdown`　`\text{\P}`　`\star`（→ ⋆）　`\diagup`　`\text{\S}`　`\bigstar`　`\flat`
`\text{\sect}`　`\clubsuit`　`\natural`　`\copyright`（→ ©）　`\clubs`　`\sharp`　`\circledR`
`\diamondsuit`　`\heartsuit`　`\text{\textregistered}`　`\diamonds`　`\hearts`　`\circledS`
`\spadesuit`　`\spades`　`\text{\textcircled a}`　`\maltese`　`\minuso`

---
