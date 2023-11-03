## Problem 1

![](D:\UWM\Dynamics_TA\Discussion_5_3_Sol\Problem1.png)

### Analysis

<img src="D:\UWM\Dynamics_TA\Discussion_5_3_Sol\FBD_Problem1.png" style="zoom: 50%;" />

​	To find the equations, we can first draw a FBD of the block, then try to find what equations can we use to solve the unknowns.

​	First, we try to consider energy: we can easily notice that there are 2 forces, gravity $mg$, and normal force $N$ from the cone. Gravity is conservative force, and normal force is perpendicular to the cone surface. So we can use conservative of energy for this problem (with $U_{nc}=0$).
$$
T_1+V_1=T_2+V_2
$$
​	Then we look into  momentum-impulse. $\vec{p_1}+F_{1-2}=\vec{p_2}$
$$
\vec{F}=-Ncos\theta\cdot  \hat{u}_r +(Nsin\theta-mg)\cdot \hat{u}_z
$$
​	we can see that direction of $N$ is consistently changing with the position of the block, making $\int\vec{F}dt$ hard to solve, and making momentum in all directions not conserved.

​	We then analyze angular momentum-impulse. Where $\vec{M}=\vec{r}\times\vec{F}$:
$$
\begin{align}
\vec{M}&= r\hat{u}_r \times (-Ncos\theta\cdot  \hat{u}_r +(Nsin\theta-mg)\cdot \hat{u}_z)\\
&=(Nsin\theta-mg)r\cdot\hat{u}_\theta
\end{align}
$$
​	$\vec{M}$ is along polar direction, which means that on direction $\hat{u}_z$, angular momentum is conserved. Where $\hat{h}_z=r\hat{u}_r\times m(\dot{r}\hat{u}_r+r\dot\theta\hat{u}_\theta)=mr^2\dot\theta\hat{u}_z$. So
$$
mr_1^2\dot\theta_1=mr_2^2\dot\theta_2
$$

<div style="page-break-after: always;"></div>

### Solution

![](D:\UWM\Dynamics_TA\Discussion_5_3_Sol\1698988909852-88a2ebbd-12fd-4a9b-8f8a-77305560b8e7_2.jpg)
<div style="page-break-after: always;"></div>
![1698988909852-88a2ebbd-12fd-4a9b-8f8a-77305560b8e7_3](D:\UWM\Dynamics_TA\Discussion_5_3_Sol\1698988909852-88a2ebbd-12fd-4a9b-8f8a-77305560b8e7_3.jpg)
<div style="page-break-after: always;"></div>
![1698988909852-88a2ebbd-12fd-4a9b-8f8a-77305560b8e7_4](D:\UWM\Dynamics_TA\Discussion_5_3_Sol\1698988909852-88a2ebbd-12fd-4a9b-8f8a-77305560b8e7_4.jpg)
<div style="page-break-after: always;"></div>
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
