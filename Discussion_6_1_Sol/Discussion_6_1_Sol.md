## Problem 1

![image-20231107195436910](D:\UWM\Dynamics_TA\Discussion_6_1_Sol\Prob1.png)

### Recall

​	We first review the cross product of vectors.
$$
\vec{a} \times \vec{b} = 
\left|
\begin{matrix}
i & j & k\\
a_x & a_y & a_z\\
b_x & b_y & b_z\\
\end{matrix}
\right|=
(a_yb_z-a_zb_y)\hat{i}+
(a_zb_x-a_xb_z)\hat{j}+
(a_xb_y-a_yb_x)\hat{k}
$$
​	Where $\hat{i},\hat{j},\hat{k}$ are unit vectors of positive $x,y,z$ direction. And by definition, we knows that: $\vec{a} \times \vec{b}=-\vec{b} \times \vec{a}$, and $\vec{a} \times \vec{a}=\vec{0}$.

​	Specifically, we have: 
$$
\vec{i}\times\vec{j}=\vec{k}\\
\vec{j}\times\vec{k}=\vec{i}\\
\vec{k}\times\vec{i}=\vec{j}\\
$$
​	For rigid body rotating to a fixed axis at A, for any point B on the object, we have:
$$
\vec{v}_{B/A} = \vec\omega_{AB}\times \vec R_{B/A}
$$


### Solution

​	For this problem, we first find $\vec{r}$ and $\vec{\omega}$ for the fixed rotation
$$
\vec{r}_{A/O}=R(sin\varPhi\cdot \hat{i} + cos\varPhi\cdot \hat{j})\\
\vec{r}_{B/O}=-R/2\cdot \hat{i}
$$
  We can find $\omega$ using given velocity of A and radius. Since: $v_A=|\omega| R$, z axis is pointing outwards of the plane, and the turbine is rotating clockwise (angular vector pointing inwards), we have
$$
\vec \omega = -v_A/R\cdot \hat{k}
$$
 therefore,  
$$
\begin{align}
\vec v_B&= \vec \omega \times \vec R\\
&=-v_A/R\cdot \hat{k}\times (-\frac{R}{2}\cdot \hat{i})\\
&=\frac{v_A}{2}\hat j\\
&=146\hat j\ ft/s
\end{align}
$$




