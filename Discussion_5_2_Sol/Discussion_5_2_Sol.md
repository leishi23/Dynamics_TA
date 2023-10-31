## Problem 1

![](D:\UWM\Dynamics_TA\Discussion_5_2_Sol\屏幕截图 2023-10-26 225143.png)

### Analysis

​	Let us set $y$ axis pointing vertically up and break down the process into 4 stages:

	1. the laptop starts dropping, $ T_1=0,\ V_1=mgh$.
	2. the moment before the laptop hits the ground, where: $T_2=\frac{1}{2}mv_2^2,\ V_2=0$.
	3. the moment after laptop bounce off the ground, where: $T_3=\frac{1}{2}mv_3^2,\ V_2=0$.
	4. The laptop rebounds to the highest point of $h_4=5cm$, where: $T_4=0,\ V_4=mgh_4$.

​	We can use conservation of energy between 1 and 2, 3 and 4. And we can use impulse-momentum principle between 2 and 3.

### Solution	

​	Using conservation of energy between stage 1 and 2, 3 and 4. we can obtain these equations:
$$
\begin{align}
mgh &=\frac{1}{2}mv_2^2\\
\frac{1}{2}mv_3^2 &= mgh_4
\end{align}
$$
​	Solving these 2 equations, we will have: $v_2=-\sqrt{2gh}=(-4.429m/s)\hat{j}$ (negative implies velocity vector pointing down) and $v_3=\sqrt{2gh_4}=(0.991m/s)\hat{j}$.

​	And Using impulse-momentum principle between stage 2 and 3, we have:
$$
\vec{p_2}+I = \vec{p_3}
$$
​	and $I = \vec{p_3} -\vec{p_2} = 2.75\times[0.991-(-4.429)]=14.9\ \hat{j}N\cdot s$.

​	For average acceleration, we can use contact time $t=10^{-3}s$ and change of velocity:
$$
\bar{a}=\frac{v_3-v_2}{t}=5420 \hat{j}\ m/s
$$


## Problem 2

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2_Sol/Screenshot%202023-10-26%20220453.png?raw=true" width="500"/>   
</div>


### Review
- Conservation of momentum(impact): $m_1v_1+m_2v_2=m_1v_1'+m_2v_2'$
- <div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2_Sol/Screenshot%202023-10-26%20220833.png?raw=true" width="500"/>   
</div>

<!-- Page Seg -->
<div style="page-break-after: always;"></div>

### Solution

#### Part 1
Consider the impact between the two blocks, we have the following equations:
$$
\begin{cases}
m_A \vec{v}_{A-} + m_B \vec{v}_{B-} = m_A \vec{v}_{A+} + m_B \vec{v}_{B+} \\
e = \frac{v_{B+}-v_{A+}}{v_{A-}-v_{B-}}
\end{cases}
$$
where $e$ is the coefficient of restitution, and $v_{A-}$, $v_{B-}$, $v_{A+}$, $v_{B+}$ are the velocities of block A and B before and after the impact, respectively.

Plug in the given values, we have:
$$
\begin{cases}
0.5 \times 2 + 2 \times 0 = 0.5 \times v_{A+} + 2 \times v_{B+} \\
0.4 = \frac{v_{B+}-v_{A+}}{2-0}
\end{cases}
$$

So, we have: $v_{A+} = -0.24 \text{ m/s}$, $v_{B+} = 0.56 \text{ m/s}$.

#### Part 2
As for the friction and energy of block B, we have:
$$T_1 + V_1 + U_{1-2} = T_2 + V_2$$
where $T$ is the kinetic energy, $V$ is the potential energy, and $U$ is the work done by friction.

There is no change in potential energy, so we have: 
$$T_1 + U_{1-2} = T_2 $$

- $T_1$ is the kinetic energy of block B after impact, which is $T_1 = \frac{1}{2} m_B v_{B+}^2$.
- $T_2$ is the kinetic energy of block B when it stops, so $T_2 = 0$.
- $U_{1-2}$ is the work done by friction, which is $U_{1-2} = -\mu_k m_B g d$. The negative sign is because the friction force is in the opposite direction of the displacement.
- So, $d = \frac{1}{2\mu_k g} v_{B+}^2 = 0.04 \text{ m}$.


<!-- Page Seg -->
<div style="page-break-after: always;"></div>

