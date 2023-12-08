## Problem 2

<!-- ![image-20231107195436910](./Screenshot%202023-11-28%20133131.png) -->
<img src="./Screenshot 2023-12-07 223621.png" alt="oblique_impact" style="zoom:57%; center;" />

### Review and Hints
- For the angular impulse momentum: to convert the angular impulse momentum from point $P$ to point $G$, we have:
  - $\vec{h}_P = I_G\vec{\omega}_B + m\vec{r}_{G/P}\times\vec{v}_G$
<img src="./Screenshot 2023-12-07 223908.png" alt="oblique_impact" style="zoom:57%; center;" />

- Conservation of angular impulse monmentum:
  - It's conserved when there is no external moment applied to the system. In this case, there is no external moment applied to the system due to the negligible friction.
  - $\vec{h}_{P1} = \vec{h}_{P2}$
    - $\vec{h}_{P1}$ is the angular impulse momentum at point $P$ before the mition.
    - $\vec{h}_{P2}$ is the angular impulse momentum at point $P$ after the motion.


<div style="page-break-after: always;"></div>

### Solution

Before the motion, we have:
$$
\begin{aligned}
\vec{h}_{P1} &= (I_{GB}\vec{\omega}_1 + m_B\vec{r}_{B/O}\times\vec{v}_{B1}) + (I_{GA}\vec{\omega}_1 + m_A\vec{r}_{A/O}\times\vec{v}_{A1})  + (I_{OC}\vec{\omega}_C + 0) \\
&= \underline{Disk B} + \underline{Disk A} + \underline{Rod C} \\
&= (I_{GB}\vec{\omega}_1 + 0) + (I_{GA}\vec{\omega}_1 + 0) + (I_{OC}\vec{\omega}_C) \\
\end{aligned}
$$
In the initial instant, the $\vec{v}_{B1}$, $\vec{v}_{A1}$ and $\vec{\omega}_C$ are all 0 because the system is at rest.

After the motion, we have:
$$
\begin{aligned}
\vec{h}_{P2} &= (I_{GB}\vec{\omega}_2 + m_B\vec{r}_{B/O}\times\vec{v}_{B2}) + (I_{GA}\vec{\omega}_2 + m_A\vec{r}_{A/O}\times\vec{v}_{A2})  + (I_{OC}\vec{\omega}_C + 0) \\
&= \underline{Disk B} + \underline{Disk A} + \underline{Rod C} \\
&= (I_{GB}\vec{\omega}_2 + m_B\omega_2r_{B/O}^2\hat{k}_r) + (I_{GA}\vec{\omega}_2 + m_A\omega_2r_{A/O}^2\hat{k}_r) + (I_{OC}\vec{\omega}_2) \\
\end{aligned}
$$
In the final instant, the $\vec{v}_{B2} = \omega_2\vec{r}_{B/O}$, $\vec{v}_{A2} = \omega_2\vec{r}_{A/O}$ and $\vec{\omega}_C = \omega_2\hat{k}$ because the system is rotating at the same angular velocity $\omega_2$.

Fill in the moment of inertia:
$$
\begin{aligned}
I_{GA} &= \frac{1}{2}m_Ar_{A/O}^2 \\
&= 0.045kg\cdot m^2 \\
I_{GB} &= \frac{1}{2}m_Br_{B/O}^2 \\
&= 0.045kg\cdot m^2 \\
I_{OC} &= \frac{1}{12}m_CL^2 \\
&= 0.375kg\cdot m^2 \\
\end{aligned}
$$

Therefore, we have:
$$
\begin{aligned}
0.045\cdot (-5\hat{k}) + 0.045\cdot (-5\hat{k}) = 0.045\cdot (\omega_2\hat{k}) + 2.25\cdot (\omega_2\hat{k}) + 0.045\dot (\omega_2\hat{k}) + 2.25\cdot (\omega_2\hat{k}) + 0.375\cdot (\omega_2\hat{k}) \\
\end{aligned}
$$
So, $\omega_2 = -0.0906\ rad/s$. The negative sign indicates that the rotation is clockwise.