---
{"dg-publish":true,"permalink":"/mathnotes/nlpde-u-u-f/","tags":"gardenEntry","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false}
---


考虑带有度量形式 $ds^2=2dxdy$ 的曲面, 它的度量矩阵为
$$g=\begin{pmatrix}
0&1\\
1&0
\end{pmatrix}.$$
此时考虑一待定坐标变换 $u=u(x,y),\ v=v(x,y)$.
$$
\begin{aligned}
1&=g_{12}=\langle \boldsymbol r_x,\boldsymbol r_y\rangle=\left\langle \boldsymbol r_u{\partial u\over\partial x}+\boldsymbol r_v{\partial v\over\partial x},\boldsymbol r_u{\partial u\over\partial y}+\boldsymbol r_v{\partial v\over\partial y}\right\rangle\\
&=\langle\boldsymbol r_u,\boldsymbol r_u\rangle{\partial u\over\partial x}{\partial u\over\partial y}+\langle\boldsymbol r_u,\boldsymbol r_v\rangle\left({\partial u\over\partial x}{\partial v\over\partial y}+{\partial u\over\partial y}{\partial v\over\partial x}\right)+\langle\boldsymbol r_v,\boldsymbol r_v\rangle{\partial v\over\partial x}{\partial v\over\partial y}.
\end{aligned}
$$
考察 $v(x,y)$ 的一条等值线 $\gamma:\boldsymbol r=\boldsymbol r(u)$. $\gamma$ 从曲面上诱导得来的度量记为 $d\hat{s}$. 于是
$$
d\hat s^2=\hat g_{11}du^2=\langle\boldsymbol r_u,\boldsymbol r_u\rangle du^2=\left({\partial u\over\partial x}{\partial u\over\partial y}\right)^{-1}du^2=\frac1fdu^2.
$$
故
$$
{du\over d\hat s}=\sqrt f.
$$
