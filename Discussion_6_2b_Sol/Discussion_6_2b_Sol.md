# Problem 1

![](D:\UWM\Dynamics_TA\Discussion_6_2b_Sol\Problem2.png)

## Review

​	The last lecture is about **Instantaneous center** (IC) of a rigid body. The key feature of instantaneous center is:

1. It is not constant in time, and not necessarily on the object.

2. Its velocity is zero at this instant. All points on the body can be described as:
   $$
   \vec{v_A} = \vec\omega\times\vec{r}_{A/IC}
   $$
   Where $\omega$  is the angular velocity around instantaneous center. Therefore, for every point on the rigid body, its velocity is perpendicular to the position vector from instantaneous center to itself.

​	We can find the instantaneous center by using physical features of the rigid body(rotating around a fixed point), or we can determine instantaneous center by know velocities, positions and angular velocities.

## Analysis

​	For this problem, we have already done analysis and found $\vec{v}_D=\vec{v}_P$. To find $\vec{v}_D$, we can apply instantaneous center method on rod BD:

<img src="D:\UWM\Dynamics_TA\Discussion_6_2b_Sol\屏幕截图 2023-11-14 191758.png" style="zoom:40%;" />

​	We used the feature "all points on the rigid body have perpendicular velocity to IC".

<!-- page segamentation -->

<div style="page-break-after: always;"></div>

## Solution

​	With the graph we have from analysis, we can first write down B and D's velocities described with IC:
$$
\vec{v}_B=\vec{\omega}\times\vec{r}_{B/IC}\quad (1)\\
\vec{v}_D=\vec{\omega}\times\vec{r}_{D/IC}\quad (2)
$$
​	And we can use geometric features of the system to solve $\vec{r}_{B/IC}$ and $\vec{r}_{D/IC}$
$$
\begin{align}
\vec{r}_{B/IC} &= -(\bar{AD}-\frac{l_1}{cos\theta})\hat{i}-(\frac{\bar{AD}}{tan\theta}-l_1sin\theta)\hat{j}\\
&=-7.76\hat{i}-6.51\hat{j}\\
\vec{r}_{D/IC} &= -\frac{\bar{AD}}{tan\theta}\cdot \hat{j}\\
&=-8.44 \hat{j}
\end{align}
$$
​	Also, B is rotating around A, we have:
$$
\vec{v}_B=\vec{v}_A+\vec{\omega}_{AB}\times\vec{r}_{B/A}\quad (3)
$$
​	Where $\vec{v}_A=0$ and $\vec{r}_{B/A}=l_1cos\theta\hat{i}+l_1sin\theta\hat{j}$ . and we can solve that (just like last Friday) $\vec{v}_{B}=403.9\hat{i}-481.3\hat{j} (ft/s)$

​	Plugging into equation (1), we found that the remaining unknowns are: $\omega, \vec{v_D},$ with 2 equations and 2 unknowns, we can plug in to solve.

​	First, $\omega = 403.9/6.51 = 62.03 rad/s$

​	Then plug in (2), $\vec{v}_D=62.03\hat{k}\times(-8.44 \hat{j})=523.4in/s\hat{i}$

​	Which is the same with our solution from last Friday.

<!-- page segamentation -->

<div style="page-break-after: always;"></div>

# Problem 2

![屏幕截图 2023-11-14 190200](D:\UWM\Dynamics_TA\Discussion_6_2b_Sol\屏幕截图 2023-11-14 190200.png)

## Analysis

<img src="D:\UWM\Dynamics_TA\Discussion_6_2b_Sol\微信图片_20231114195540.jpg" alt="微信图片_20231114195540" style="zoom: 33%;" />

​	Repeat what we have done for the first problem: find IC. In this case. Since $\theta=45^o$, velocity of C is perpendicular to $\bar{AC}$, and $B$ is on rod $AB$ which is also rotating around $A$, so we can find out IC in this case is $A$.

<!-- page segamentation -->

<div style="page-break-after: always;"></div>

### Solution

​	The angular velocity of C with respect to the instantaneous center is the same as the angular velocity of $BC$, which is  $\omega_{BC}=20rad/s\cdot \hat{k}$
$$
\begin{align}
\vec{v}_C &=\vec{v}_A+\vec{\omega}\times\vec{r}_{C/A}\\
&=0+20\hat{k}\times(2.5\hat{i}-2.5\hat{j})
\\ &= 50\hat{i}+50\hat{j}
\end{align}
$$
​	For B, we have
$$
\vec{v}_B =\vec{v}_{IC}+\vec{\omega}\times\vec{r}_{B/IC}\\
\vec{v}_B =\vec{v}_A+\vec{\omega}_{AB}\times\vec{r}_{B/A}\\
$$
​	It is obvious that $\vec{\omega}_{AB}=\vec\omega=20rad/s\cdot \hat{k}$

