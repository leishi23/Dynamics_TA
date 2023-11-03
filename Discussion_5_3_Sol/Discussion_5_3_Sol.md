## Problem 2

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_3_Sol/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(43).png?raw=true" alt="oblique_impact" style="zoom:67%;" />

### Recall & Analysis

![oblique_impact](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_3_Sol/Screenshot%202023-11-02%20233515.png?raw=true)

- Angular momentum: $\vec{H}=\vec{r}\times\vec{p}=m\vec{r}\times\vec{v}$
- Conservation of angular momentum: if the torque $\vec{M}$ is zero, then $\vec{H}$ is constant. Because $\vec{M}=\frac{d\vec{H}}{dt}$, if $\vec{M}=0$, then $\frac{d\vec{H}}{dt}=0$, which means $\vec{H}$ is constant.
- In this problem, the $\vec{H} = m\vec{r}\times\vec{v} = m (r\hat{u_r}) \times (v\hat{u_\theta}) = mvr\hat{u_k}$, which is always perpendicular to the $z$-axis. Therefore, if there is no torque on the $\hat{u_k}$ direction, the angular momentum is conserved.
- In this problem, the torque $\vec{M} = \vec{r} \times \sum\vec{F} = (r\hat{u_r}) \times (N\hat{u_k} - mg\hat{u_k} - T\hat{u_r}) = (-rN + rmg)\hat{u_\theta}$. Therefore, there is no torque on the $\hat{u_k}$ direction.


<div style="page-break-after: always;"></div>

### Solution

Since the angular momentum is conserved, we can use the angular momentum conservation to solve this problem: $H_1 = H_2$.

$$
\begin{aligned}
H_1 &= H_2 \\
mr_1v_1 &= mr_2v_2 \\
mr_1(\dot{\theta_1}r_1) &= mr_2(\dot{\theta_2}r_2) \\
\dot{\theta_1}r_1^2 &= \dot{\theta_2}r_2^2 \\
\frac{\dot{\theta_1}}{\dot{\theta_2}} &= \frac{r_2^2}{r_1^2} \\
\frac{\dot{\theta_1}}{\dot{\theta_2}} &= \frac{0.25^2}{0.5^2} \\
\frac{\dot{\theta_1}}{\dot{\theta_2}} &= \frac{1}{4} \\
\dot{\theta_2} &= 4\dot{\theta_1} \\
\dot{\theta_2} &= 4\text{ rad/s}
\end{aligned}
$$

From the FBD:
$$
\begin{aligned}
\sum F_r &= m\ddot{r} - mr\dot{\theta}^2 = - T \\
\end{aligned}
$$
where $\ddot{r} = 0$ because the string is always drawn down at a constant speed, i.e. $T = mr\dot{\theta}^2$.
So, at $r_2 = 0.25$ m, $\dot{\theta_2} = 4$ rad/s, $T = 2\times 0.25\times 4^2 = 8$ N.
