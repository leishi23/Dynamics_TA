## Problem 1

![](D:\UWM\Dynamics_TA\Discussion_5_2-3_Sol\Problem1.png)

### Recall & Analysis

<img src="D:\UWM\Dynamics_TA\Discussion_5_2-3_Sol\oblique_impact.png" alt="oblique_impact" style="zoom:67%;" />

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