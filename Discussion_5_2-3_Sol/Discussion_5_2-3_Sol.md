## Problem 1

![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2-3_Sol/Problem1.png?raw=true)

### Recall & Analysis

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2-3_Sol/oblique_impact.png?raw=true" alt="oblique_impact" style="zoom:67%;" />

​	Some Key concepts and equations for oblique impact.

**Plane of contact**: The plane where two objects contact. Perpendicular to line of impact.

**Line of impact**: where internal deformation and restitution impulses takes place, hence results obtained in the previous lecture (about 1-D impact) can be applied along LOI. Line of impact is set as local $x-axis$ in the following equations.

(1) conservation of momentum:
$$
m_A(v_{Ax})_1+m_A(v_{Bx})_1=m_A(v_{Ax})_1+m_A(v_{Bx})_2
$$
(2) relative speed before and after the impact is related through the coefficient of restitution: 
$$
e=\frac{(v_{Bx})_2-(v_{Ax})_2}{(v_{Ax})_1-(v_{Bx})_1}
$$
(3) There is no impulsive forces perpendicular to the line of impact, so momentum in plan of impact direction is conserved for each object:
$$
m_A(v_{Ay})_1+m_A(v_{By})_1=m_A(v_{Ay})_1+m_A(v_{By})_2
$$
​	Or in most cases without friction and other types of forces on plane of impact:
$$
(v_{Ay})_1=(v_{Ay})_2\\
(v_{By})_1=(v_{By})_2\\
$$
In today's problem, the speed of car A and B before and after collision can be described as:
$$
\begin{align}
(v_{A})_1&=v_Acos30^o\cdot \hat{i} + v_Asin30^o\cdot \hat{j}\\
(v_{B})_1&=0\cdot \hat{i} +-v_B\cdot \hat{j}\\
(v_{A})_2=(v_{B})_2&=v\ cos10^o\cdot \hat{i} + v\ sin10^o\cdot \hat{j}
\end{align}
$$
Applying the conclusions above to this problem, we can have these equations:

momentum conservation along LOI:
$$
m_A(v_{Ax})_1+m_A(v_{Bx})_1=(m_A+m_{B})(v_x)_2
$$
and momentum conservation on plane of impact:
$$
m_A(v_{Ay})_1+m_A(v_{By})_1=(m_A+m_B)(v_{y})_2
$$

<div style="page-break-after: always;"></div>

### Solution

(1)	Plugging in the known values to our equations, we have:

​	x-direction: $m_Av_Acos30^o=(m_A+m_{B})v\ cos10^o$ 					(1) 

​	y-direction: $m_Av_Asin30^o-m_B v_B=(m_A+m_{B})v\ sin10^o$	(2)

​	Though we have 3 unknowns($v_A,v_B$ and $v$), we only need the ratio $v_B/v_A$ to determine who is faster.

​	by (1)/(2) and rearrange to solve $v_B/v_A$, we have:
$$
\frac{v_B}{v_A}=0.3473\frac{m_B}{m_A}=0.4465
$$
​	Therefore, $v_A>v_B$.

(2)	Given $v_B=30mph$, we have $v_A=v_B/0.4465=67.2mph$

<div style="page-break-after: always;"></div>

## Problem 2
<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2-3_Sol/Screenshot%202023-10-31%20175756.png?raw=true" alt="oblique_impact" style="zoom:67%;" />

### Recall & Analysis

- The _**equations of motion**_ are functions of time that describe the position, velocity, and acceleration. In this problem, it's in the 2-D polar coordinate system, so we need **two** variables: **$r$** and **$\theta$** to describe the position of the particle. To solve for two variables, we need two equations of motion.
- Equation 1: it's a curvilinear motion, so we could consider the acceleration equation:
    - $a_r = \ddot{R} - R\dot{\theta}^2$, direction is outward the center of curvature
    - $a_{\theta} = R\ddot{\theta} + 2\dot{R}\dot{\theta}$, direction is perpendicular to the radial direction
  > **Note**: we don't need both equations. Please analyze the problem and choose the one.
- Equation 2: impulse-momentum principle:$M = \dot{h}$, where $h$ is the angular momentum of the particle about the center of curvature.

<div style="page-break-after: always;"></div>

### Solution
![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_2-3_Sol/Screenshot%202023-10-31%20182607.png?raw=true) 
- Impulse momentum principle: $M = \dot{h}$, where $\vec{h}=\vec{r}\times m\vec{v}$
  - $\vec{r} = R\hat{u}_r$
  - $\vec{v} = \dot{R}\hat{u}_r + R\dot{\theta}\hat{u}_{\theta}$
  - $h = mR^2\dot{\theta}$, because $\vec{r}\times\vec{v} = mR^2\dot{\theta}\hat{u}_z$ where $\hat{u}_r\times\hat{u}_{\theta} = \hat{u}_z$ and $\hat{u}_r\times\hat{u}_r = 0$
  - $\dot{h} = mR^2\ddot{\theta} + 2mR\dot{R}\dot{\theta}$
  - $M = mR^2\ddot{\theta} + 2mR\dot{R}\dot{\theta}$

- Curvilinear motion: observe that the collar is not subject to any force in the $r$ direction, so $a_r=0$, this then implies: $\ddot{R}-R\dot{\theta}^2=0$

Summarize the equations of motion:
$$
\begin{cases}
\ddot{R}-R\dot{\theta}^2=0 \\
mR^2\ddot{\theta} + 2mR\dot{R}\dot{\theta} = M
\end{cases}
$$
