## Problem 1

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_1_Sol/Screenshot%202023-10-24%20221549.png?raw=true" width="500"/>   
</div>


### Review

- The impulse-momentum principle：$mv_{x1} + \int_{t_1}^{t_2} F dt = mv_{x2}$
  - $v_{x1}$ and $v_{x2}$ are the velocities of the particle at initial and final instants, respectively.

<!-- Page Seg -->
<div style="page-break-after: always;"></div>

### Solution
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_1_Sol/Screenshot%202023-10-24%20223813.png?raw=true" />   
</div>

<!-- Page Seg -->
<div style="page-break-after: always;"></div>

## Problem 2

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_5_1_Sol/Screenshot%202023-10-24%20224047.png?raw=true" width="500"/>   
</div>

### Review
- Energy: $T_1 + V_1 = T_2 + V_2$
  - There is no $U_{1-2}$ because there is no non-conservative force like friction.
  - $T_1 = 0$ because they are at rest initially.
  - $V_2 = 0$ because crate reaches the bottom of the ramp in the end.
  - $V_1 = m_c g d \sin \theta$ 
  - $T_2 = \frac{1}{2} m_c v_{c_2}^2 + \frac{1}{2} m_R v_{R_2}^2$
- Momentum: $m_c v_{c_{1_x}} + m_R v_{R_{1_x}} = m_c v_{c_{2_x}} + m_R v_{R_{2_x}}$ because the system is balanced in the x-direction.
  - $v_{c_{1_x}} = 0$ because the crate is at rest initially.
  - $v_{R_{1_x}} = 0$ because the ramp is at rest initially.
  - $v_{R_{2_x}} = v_{R_{2}}$ because the ramp moves in the x-direction only.
  - $v_{c/r_{2_x}} = v_{c/r_{2}} \cos \theta$ because the crate moves in both x and y directions.
  - $\vec{v_c} = \vec{v_r}+\vec{v_{c/r}}$, and relative speed $v_{c/r}$ is the same with the direction of decline.

<img src="C:\Users\23472\AppData\Roaming\Typora\typora-user-images\image-20231025005826348.png" alt="image-20231025005826348" style="zoom:50%;" />



### Solution

The relative velocity of crate and ramp is parallels to the decline of the slope:
$$
v_c^2=v_{c/r}^2+v_{r}^2-2v_{c/r}v_{r}cos30^o
$$

$$
\begin{aligned}
m_c g d \sin \theta &= \frac{1}{2} m_c v_{c_2}^2 + \frac{1}{2} m_R v_{R_2}^2 \\
0 &= m_c v_{c/r2} \cos \theta + m_R v_{R_2}
\end{aligned}
$$
Plug the values into the equations above and solve for $v_{c_2}$ and $v_{R_2}$. So, $v_{c_2} = 5.33 \text{ m/s}$ and $v_{R_2} = -1.08 \text{ m/s}$.

## Problem 3

<img src="D:\UWM\Dynamics_TA\Discussion_5_1_Sol\Problem3.png" style="zoom: 50%;" />

### Solution

$(a)$ :Energy: $T_1+V_1=T_2+V_2$, where $T_1=0$, $V_2=0$
$$
mgh = \frac{1}{2}mv_2^2
$$
​	Solve to get: $v_2=31.08ft/s$

​	Momentum: $mv_2=(m_c+m)v_3$, so $v_3=20.72ft/s$

$(b)$ :Assume the impulse $I = \int Fdt$, and $m_bv_2-\int Fdt=0$

​	Just plug the result in $(a)$ and: $I = m_bv_2= \frac{40}{32.2}*31.08=38.6093(Lb\cdot s)$

