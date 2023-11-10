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
