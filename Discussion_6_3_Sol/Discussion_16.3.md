## Problem 1

![image-20231107195436910](./Screenshot%202023-11-16%20122156.png)
Set the drum center as point **$G$**.

### Review

![image-20231107195436910](./Screenshot%202023-11-16%20122519.png)

<div style="page-break-after: always;"></div>

### Solution

$$
\vec{v}_B = \vec{v}_D = \omega \vec{r}_{B/A} \Rightarrow \omega = \frac{8}{2} = 4 \text{ rad/s}
$$


$$
\vec{\omega} = 4 \text{ rad/s}, clockwise
$$

$$
\vec{a}_G = \vec{a}_A + \vec{\alpha} \times \vec{r}_{G/A} - \omega^2 \vec{r}_{G/A} \quad 
$$

$$
\vec{a}_G = a_G \hat{i} \quad (\text{Path of } G \text{ is horizontal})
$$

$$
\vec{a}_A = a_A \hat{j} \quad (\text{Path of } A \text{ at this instant is vertical, because the rolling is without slipping})
$$

$$
a_G\hat{i} = a_A\hat{j} + (-\alpha \hat{k} \times 3 \hat{j}) - (4^2)(3)\hat{j}
$$

$$
a_G = 3 \alpha
$$

$$
\boxed{\vec{a}_A = 48 \hat{j} \text{ in/s}^2} \uparrow
$$

$$
\vec{a}_B = \vec{a}_A + \vec{\alpha} \times r_{B/A} - \omega^2  \vec{r}_{B/A}
$$

$$
\vec{a}_D = -30 \hat{i} = \vec{\alpha} \times \vec{r}_{B/A} = -\alpha \hat{k} \times (-2 \hat{j}) = -2 \alpha \hat{i}
$$

$$
-30 \hat{i} = -2\alpha \hat{i} 
$$

$$
\vec{\alpha} = 15 \text{ rad/s}^2
$$

$$
\vec{a}_B = 48 \hat{j} - 30 \hat{i} - 4^2 (-2\hat{j})
$$

$$
\boxed{\vec{a}_B = -30 \hat{i} + 80 \hat{j} \text{ in/s}^2} 
$$

$$
a_G = 3 \alpha = 45 \text{ in/s}^2
$$

$$
\boxed{\vec{a}_G = 45 \hat{i} \text{ in/s}^2} \rightarrow
$$

$$
\vec{a}_C = \vec{a}_G + \vec{\alpha} \times \vec{r}_{C/G} - \omega^2 \vec{r}_{C/G} = 45 \hat{i} + (-15 \hat{k} \times (5 \hat{i})) - (4^2)(5 \hat{i})
$$

$$
\boxed{\vec{a}_C = -35 \hat{i} - 75 \hat{k} \text{ in/s}^2}
$$

<!-- page segamentation -->
<div style="page-break-after: always;"></div>

# Problem 2

![](D:\UWM\Dynamics_TA\Discussion_6_3_Sol\Screenshot 2023-11-16 135609.png)

## Recall

- In non-slipping rolling, contact point has zero-velocity $\vec v_E=0$, hence is the instantaneous center at the instant.

- The acceleration of contact point can be different from zero, but only in the direction perpendicular to the contact. $\vec a_E = \omega^2 R\cdot \hat j$.

- Acceleration analysis of different points on a rigid body:

$$
\vec a_B = \vec a_A + \vec \alpha_{AB}\times\vec r_{B/A} - \omega_{AB}^2\vec r_{B/A}\cdot
$$
<!-- page segamentation -->
<div style="page-break-after: always;"></div>
## Solution

#### Angular Velocity of CD

​	There are 3 rigid bodies in this problem: disk $A$, link $BC$, and link $CD$. Assume their angular velocities as $\omega_A$, $\omega_{BC}$ and $\omega_{CD}$. $\omega_{CD}$ is what we need to solve. 

​	To analyze the motion of disk $A$, set Point $E$ as the contact point, which is also instantaneous center of the disk.

> This is commonly used in non-slipping rolling motions. The contact point is also IC at the time instant.

​	
$$
\vec v_B = \vec{\omega}_A\times \vec{r}_{B/E} \tag{1}
$$
​	Instantaneous center of link CD is D, since Link CD is spinning around D. velocity of C can be derived as: 
$$
\vec v_C = \vec{\omega}_{CD}\times \vec{r}_{C/D}\tag{2}
$$
​	B and C is connected through link BC, so velocity of B can be represented by relative motion to C:
$$
\vec{v}_B = \vec v_C + \vec\omega_{BC}\times\vec{r}_{B/C}\tag{3}
$$
​	(You can also use $\vec{v}_C = \vec v_B + \vec\omega_{BC}\times\vec{r}_{C/B}$, to represent velocity of B, but they are equivalent somehow.)

​	Combining equations $(1),(2),(3)$, we have:
$$
\vec{\omega}_A\times \vec{r}_{B/E}=\vec{\omega}_{CD}\times \vec{r}_{C/D}+ \vec\omega_{BC}\times\vec{r}_{B/C}
$$
​	Where $\omega_{A}=4\hat{k}$,   $\vec r_{B/E}=2\hat i+2\hat {j}$,  $\vec r_{C/D}=2\hat {j}$, $\vec{r}_{B/C}=-8\hat i+6\hat j$.

​	Plug in and solve:
$$
\left\{
\begin{align}
8\hat i &= (-2\omega_{CD}-6\omega_{BC})\hat i \\
-8\hat j &= (-8 \omega_{BC})\hat j.
\end{align}
\right.
$$
​	Solve for $\omega_{BC}=1rad/s \cdot \hat k  $, $\omega_{CD}=7rad/s \cdot \hat k  $

#### Angular acceleration of CD

​	Using the angular acceleration equation, we have:
$$
\vec a_B = \vec a_F + \vec \alpha_{A}\times\vec r_{B/F} - \omega_{A}^2\vec r_{B/F}\tag{4}
$$

​	By recalling acceleration of $F$ is always perpendicular to contact surface and is $\omega^2 r$, $\vec a_F = \omega_A^2 R_A\cdot \hat j=32\hat j$.

​	Also, by analyzing B and C on link BC, we have acceleration of B described by C:
$$
\vec a_B = \vec a_C + \vec \alpha_{BC}\times\vec r_{B/C} - \omega_{BC}^2 \vec r_{B/C} \tag{5}
$$
​	Where $\omega_{BC}=1\hat k,\ \vec r_{B/C}=-8\hat i+6\hat {j}$

​	Acceleration of C is :
$$
\vec a_C = \vec a_D + \vec \alpha_{CD}\times\vec r_{C/D} - \omega_{CD}^2\vec r_{C/D} \tag{6}
$$
​	Where $ \vec a_D=0$, $\omega_{CD}=7\hat k,\ \vec r_{C/D}=2\hat j$.

​	Combining $(4),(5)$ and $(6)$, we have:
$$
\omega_A^2 (R\cdot \hat j-\vec r_{B/F}) + \vec \alpha_{A}\times\vec r_{B/F}  = (\vec \alpha_{CD}\times\vec r_{C/D} - \omega_{CD}^2\vec r_{C/D})+ \vec \alpha_{BC}\times\vec r_{B/C} - \omega_{BC}^2\vec r_{B/C}
$$
​	Separating $i$ and $j$ terms, we have 
$$
\left\{
\begin{align}
(-4-32)\hat i &= (-2\alpha_{CD}-6\alpha_{BC}+8)\hat i \\
-8\hat j &= (-98-8 \alpha_{BC}-6)\hat j.
\end{align}
\right.
$$
​		Solve for $\alpha_{BC}=13.5rad/s \cdot \hat k  $, $\alpha_{CD}=62.5rad/s \cdot \hat k  $.

