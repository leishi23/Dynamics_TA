## Problem 1

![image-20231107195436910](./Screenshot%202023-11-09%20183754.png)
- $r_{A} = 0.1\ m$
- $r_{B} = 0.3\ m$

### Review

- Point D is both on bar CD and cylinder B. Therefore, there are two ways to find the velocity of point D. **One is using the angular velocity of bar CD and the other is using the angular velocity of cylinder B. The two ways should give the same result.**
- Find $V_D$ from bar CD: $$\vec{V}_D=\vec{V}_C+\vec{\omega}_{CD}\times\vec{r}_{D/C}$$
  - where $\vec{V}_C=0$ as cylinder A is fixed, and $ \vec{r}_{D/C}=(r_A+r_B)\hat{i}$
- Find $V_D$ from cylinder B: $$\vec{V}_D=\vec{V}_E+\vec{\omega}_{ED}\times\vec{r}_{D/E}$$
  - where point E is on cylinder A, and it's the contact point of cylinder A and B. Therefore, $\vec{V}_E=0$ as cylinder A is fixed, and $ \omega_{ED}=\omega_{B}$ as there is a rotation between cylinders.
    - If we set point E is on cylinder B, then $ \omega_{ED}=0$
  - $ \vec{r}_{D/E}=r_B\hat{i}$

<div style="page-break-after: always;"></div>

### Solution

Find $V_D$ from bar CD: 
$$
\begin{aligned}
\vec{V}_D&=\vec{V}_C+\vec{\omega}_{CD}\times\vec{r}_{D/C} \\
&=0+(\omega_{CD}\hat{k})\times[(r_A+r_B)\hat{i}] \\
&=5(0.1+0.3)\hat{j} \\
&=2\hat{j}
\end{aligned}
$$

Find $V_D$ from cylinder B:
$$
\begin{aligned}
\vec{V}_D&=\vec{V}_E+\vec{\omega}_{ED}\times\vec{r}_{D/E} \\
&=0+(\omega_{B}\hat{k})\times[r_B\hat{i}] \\
&=0.3\omega_{B}\hat{j} \\
\end{aligned}
$$

Since the two ways should give the same result, we have:
$$
\begin{aligned}
\vec{V}_D&=2\hat{j} \\
&=0.3\omega_{B}\hat{j} \\
\omega_{B}&=\frac{2}{0.3} \\
&=6.67\ rad/s
\end{aligned}
$$

Find the velocity of point F: 
$$
\begin{aligned}
\vec{V}_F&=\vec{V}_D+\vec{\omega}_{B}\times\vec{r}_{F/D} \\
&=2\hat{j}+(6.67\hat{k})\times[0.3\hat{j}] \\
&=2\hat{j}-2\hat{i} \\
&=-2\hat{i}+2\hat{j}
\end{aligned}
$$

<!-- page segamentation -->
<div style="page-break-after: always;"></div>

## Problem 2

![](D:\UWM\Dynamics_TA\Discussion_6_2_Sol\Problem2.png)

### Analysis

​	Velocity of $B$ is easy to obtain since $B$ is rotating at constant rate to $A$. 
$$
\vec{v}_B = \vec{v}_A +\vec{v}_{B/A}\quad (i)
$$
​	As $A$ is fixed, we have: $\vec{v}_B = \vec{v}_{B/A}$

​	Also, with $D$ is rotating with respect to $B$, and the velocity of $D$ can be described with this equation:
$$
\vec{v}_D = \vec{v}_B + \vec{v}_{D/B}\quad (ii)
$$
​	As D and P are 2 points constrainted on the piston, their velocity are the same:
$$
\vec{v}_D=\vec{v}_P
$$
​	Our strategy to solve this problem can be: Break the problem down to a chain of relative motions. $B$ with respect to $A$, and $D$ with respect to $B$, then use the equations above to solve them.

<!-- page segamentation -->

<div style="page-break-after: always;"></div>

### Solution

​	Given values: $\theta=40^o$, $l_1=3inch$, $l_2=8inch$, $\omega_{AB}=2000rpm$

​	Unknow variables: $\beta$, all velocities.

​	$B$ is rotating with respect to $A$, its speed is:
$$
\vec{v}_B=\vec{v}_{B/A}=\vec\omega_{AB}\times\vec{r}_{AB}=(-\omega_{AB})\cdot\hat{k}\times(l_1cos\theta\cdot\hat{i}+l_1sin\theta\cdot\hat{j})\quad (1)
$$
​	By plugging in the known values, we have:
$$
\begin{align}
\vec{v}_{B}&=\omega_{AB}l_1cos\theta\cdot\hat{j}-\omega_{AB}l_1sin\theta\cdot\hat{i}\\
&=403.9\hat{i}-481.3\hat{j} (ft/s)
\end{align}
$$
​	As $\vec{v}_D = \vec{v}_B + \vec{v}_{D/B}$, we still need $\vec{v}_{D/B}$, which is:
$$
\vec{v}_{D/B}=\vec\omega_{BD}\times\vec{r}_{BD}=\omega_{BD}\cdot\hat{k}\times(l_2cos\beta\cdot\hat{i}-l_1sin\beta\cdot\hat{j}) \quad (2)
$$
​	(hint: here we used B as the origin of the relative motion, therefore the $\hat{j}$ component is negative).

​	In this equation, $\omega_{BD}$ and $\beta$ are also unknown, so we still need other constraints to solve them, for $\beta$, we can use law of sines:
$$
\frac{l_1}{\beta}=\frac{l_2}{\theta}\Rightarrow \beta=sin^{-1}(\frac{l_1}{l_2}sin\theta)\quad (3)
$$
​	Solve that $\beta = 0.24rad$, or 14 degrees.

​	For $\omega_{BD}$ and $\vec{v}_{D/B}$, we can use another constraint, that is D is moving with the pistol, which means that $\vec{v}_{D}$ doesn't have a vertical component. Which indicates:
$$
\left\{
\begin{align}
v_{Dx}&=v_D\\
v_{Dy}&=0\\
\end{align}
\right.
$$
​	Using $\vec{v}_D = \vec{v}_B + \vec{v}_{D/B}$, and $(1)$, we have:
$$
\vec{v}_{D}=(\omega_{AB}l_1cos\theta+\omega_{BD}l_2cos\beta)\cdot\hat{j}-(\omega_{AB}l_1sin\theta-\omega_{BD}l_2sin\beta)\cdot\hat{i}
$$
​	Plug in the equations, we have:
$$
\left\{
\begin{align}
v_D&=-\omega_{AB}l_1sin\theta+\omega_{BD}l_2sin\beta\\
0  &=\omega_{AB}l_1cos\theta+\omega_{BD}l_2cos\beta
\end{align}
\right.
$$
​	With 2 equations and 2 unknowns, we can solve $v_D=523.4in/s$