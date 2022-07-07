# Latex公式大全

## 希腊字母表

|   输入   | 显示 |  输入   | 显示 |   输入   | 显示 |   输入   | 显示 |
| :------: | :--: | :-----: | :--: | :------: | :--: | :------: | :--: |
|  \alpha  |  αα  |    A    |  AA  |  \beta   |  ββ  |    B     |  BB  |
|  \gamma  |  γγ  | \Gamma  |  ΓΓ  |  \delta  |  δδ  |  \Delta  |  ΔΔ  |
| \epsilon |  ϵϵ  |    E    |  EE  |  \zeta   |  ζζ  |    Z     |  ZZ  |
|   \eta   |  ηη  |    H    |  HH  |  \theta  |  θθ  |  \Theta  |  ΘΘ  |
|  \iota   |  ιι  |    I    |  II  |  \kappa  |  κκ  |    K     |  KK  |
| \lambda  |  λλ  | \Lambda |  ΛΛ  |   \mu    |  μμ  |    M     |  MM  |
|   \nu    |  νν  |    N    |  NN  |   \xi    |  ξξ  |   \Xi    |  ΞΞ  |
|    o     |  oo  |    O    |  OO  |   \pi    |  ππ  |   \Pi    |  ΠΠ  |
|   \rho   |  ρρ  |    P    |  PP  |  \sigma  |  σσ  |  \Sigma  |  ΣΣ  |
|   \tau   |  ττ  |    T    |  TT  | \upsilon |  υυ  | \Upsilon |  ΥΥ  |
|   \phi   |  ϕϕ  |  \Phi   |  ΦΦ  |   \chi   |  χχ  |    X     |  XX  |
|   \psi   |  ψψ  |  \Psi   |  ΨΨ  |  \omega  |  ω   |          |      |

| 小写形式 | 大写形式 |  变量形式   |    显示    |
| :------: | :------: | :---------: | :--------: |
| \epsilon |    E     | \varepsilon | ϵ∣E∣εϵ∣E∣ε |
|  \theta  |  \Theta  |  \vartheta  | θ∣Θ∣ϑθ∣Θ∣ϑ |
|   \rho   |    P     |   \varrho   | ρ∣P∣ϱρ∣P∣ϱ |
|  \sigma  |  \Sigma  |  \varsigma  | σ∣Σ∣ςσ∣Σ∣ς |
|   \phi   |   \Phi   |   \varphi   |   ϕ∣Φ∣φ    |

## 关系运算符

|    输入    | 显示 |    输入    | 显示 |   输入    | 显示 |  输入  | 显示 |
| :--------: | :--: | :--------: | :--: | :-------: | :--: | :----: | :--: |
|   \$\pm$   |  ±   |   \times   |  ××  |   \div    |  ÷÷  |  \mid  |  ∣∣  |
|  $\nmid$   | $∤$  |   \cdot    |  ⋅⋅  |   \circ   |  ∘∘  |  \ast  |  ∗∗  |
| $\bigodot$ |  ⨀⨀  | \bigotimes |  ⨂⨂  | \bigoplus |  ⨁⨁  |  \leq  |  ≤≤  |
|   $\geq$   |  ≥≥  |    \neq    |  ≠≠  |  \approx  |  ≈≈  | \equiv |  ≡≡  |
|   \$sum$   |  ∑∑  |   \prod    |  ∏∏  |  \coprod  |  ∐   |        |      |



## 公式上标记

$\vec{a}$  向量
$\overline{a}$ 平均值
$\underline{a}$下横线
$\widehat{a}$ (线性回归，直线方程) y尖
$\widetilde{a}$ 颚化符号  等价无穷小
$\dot{a}$   一阶导数
$\ddot{a}$  二阶导数



## 矩阵 大括号

$a = \left[
\matrix{
  \alpha_1 & test1\\
  \alpha_2 & test2\\
  \alpha_3 & test3 
}
\right]$
$$
T_{1}（x）=\begin{cases} 1，X_{1} < 6.24 \\ -1， X_{1} >= 8.91\end{cases}
$$

## 常用符号


$$
\\\sum_{i+1}^m
\\\prod
\\\coprod
\\\int
\\\oint
\\\iint
\\\oiint.....
\\\infty\\\nabla\\\partial\\\eth\\\forall\\\exists\\\nexists\\\varnothing\\\mho 
\\\cong\\\equiv\\\neq\\\sim\\\simeq\\\approx\\\approxeq (****)
\\\leq\\\leqq\\\ll\\\lll\\\geq\\\geqq\\\gg\\\ggg(****)
\\\supset\\\supseteq\\\notin\\\in\\\ni\\\subset\\\subseteq 
\\\vert\\\{\\\}\\\Vert\\\langle\\\rangle\\\lfloor\\\rfloor\\
\\\Uparrow\\\uparrow\\\downarrow\\\Downarrow\\\bigoplus\\\bigotimes\\\bigodot\\\ast\\\star\\\times\\\div....
\\\leftarrow\\\longleftarrow\\\Leftarrow\\\Longleftarrow\\\uparrow\\\Uparrow\\\rightarrow\\\downarrow.....
\\\leftrightarrow\\\Longleftrightarrow\\\nearrow\\\searrow\\\swarrow\\\nwarrow
$$

## 换行 分页 

$$
换行111\newline换行222
$$

$$
分段\par分段
$$

$$
换页\newpage换页
$$

## 公式对齐

$$
\begin{flalign*}
&111&
\end{flalign*}
$$


$$ {多行公式左对齐}
\begin{flalign*}
&111\\
&222\\
&333&
\end{flalign*}
$$

$$
\begin{flalign*}
&&111
\end{flalign*}
$$

$$
\begin{flalign*}
&&111\\
&&222\\
&&333
\end{flalign*}
$$

默认是居中，不考虑了

## 相关网址

[Typora数学公式大全 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/529733310)

[Typora数学公式输入指导手册 - 小x蛋x壳 - 博客园 (cnblogs.com)](https://www.cnblogs.com/Xuxiaokang/p/15654336.html)