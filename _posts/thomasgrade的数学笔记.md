# thomasgrade的数学笔记

## 矢量运算

$$
\begin{align}
A \times ( B \times C )&= B(A \cdot C) - C(A \cdot B) \\
梯度算子\nabla = \frac{\partial }{\partial x}\vec{i}+&\frac{\partial }{\partial y}\vec{j}+\frac{\partial }{\partial z}\vec{k}\\
=\frac{\partial }{\partial\rho}\vec{e_\rho}+&\frac{1}\rho\frac{\partial}{\partial \phi}\vec e_{\phi}+\frac{\partial}{\partial z}\vec e_z\\
=\frac \partial {\partial r}\vec e_r+&\frac 1 r\frac{\partial}{\partial \theta}\vec e_{\theta}+\frac 1 {rsin\theta}\frac \partial {\partial \phi}\vec e_{\phi}\\
散度算子\nabla=(\frac \partial {\partial x},&\frac \partial {\partial y},\frac \partial {\partial z})\\
=(\frac 1 \rho\frac {\partial} {\partial \rho}\rho,&\frac 1 \rho\frac \partial {\partial \phi},\frac \partial {\partial z})\\
=(\frac{1}{r^2}\frac{\partial}{\partial r}r^2,&\frac{1}{rsin\theta}\frac{\partial}{\partial \theta}sin\theta,\frac{1}{rsin\theta}\frac{\partial}{\partial\phi})
\end{align}
$$

$$
\begin{align}

\end{align}
$$

### 线度：

$$
\begin{align}
直角坐标系下:(ds)^2&=(dx)^2+(dy)^2+(dz)^2\\
x,y,z&的线度为1，1，1\\
原著坐标系下:\left(\begin{array}{c}
x\\y\\z
\end{array}\right)
&=\left(\begin{array}{c}
\rho cos\theta\\\rho sin\theta\\z
\end{array}\right)\\
\left(\begin{array}{c}
dx\\dy\\dz
\end{array}\right)
&=\left(\begin{array}{cc}
cos\theta d\rho-\rho sin\theta d\theta\\sin\theta d\rho+\rho\cos\theta d\theta\\z
\end{array}\right)\\
(ds)^2&=(d\rho)^2+(\rho d\theta)^2+(dz)^2\\
(\rho,\theta,z)&的线度为（1,\rho,z)\\ \ \\
同理可以求得球&坐标系下(r,\phi,\theta)线度为(1,r,rsin\theta)
\end{align}
$$

$$
基底<q_1,q_2,q_3>线度为H_1,H_2,H_3\\
梯度:\frac{\partial}{\partial q_1}\frac {\vec{e_{q_1}}} {H_1}+
 	\frac{\partial}{\partial q_2}\frac {\vec{e_{q_2}}} {H_2}+
	\frac{\partial}{\partial q_3}\frac {\vec{e_{q_3}}} {H_3}\\
散度:\frac 1 {H_1H_2H_3}(\frac{\partial H_2H_3}{\partial q_1},
	\frac{\partial H_3H_1}{\partial q_2},
	\frac{\partial H_1H_2}{\partial q_3})\\
旋度:\left| \begin{array}{ccc}
\frac {\vec{q_1}}{H_2H_3}&\frac {\vec{q_2}}{H_3H_1}&\frac {\vec{q_3}}{H_1H_2}\\
\frac{\partial}{\partial q_1}&\frac{\partial}{\partial q_1}&\frac{\partial}{\partial q_1}\\
H_1F_1&H_2F_2&H_3F_3
\end{array}\right|
$$

