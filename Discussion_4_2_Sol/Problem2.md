<!-- Insert an image with html in center position -->
# Problem 1
<div style="display: flex; justify-content: center; align-items: center;">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_4_2_Sol/Screenshot%202023-10-12%20171624.png?raw=true" alt="Image" />
</div>

## Review
- FBD: two forces: $F_c$ (the string tension) and $mg$ (the weight of the ball)
- N-T coordinate system: 
  - N dimension: $F_c - mg\sin\theta = ma_n$, where $a_n = v^2/L$
  - T dimension: $mg\cos\theta = ma_t$, where $a_t = \dot{v}$
- Energy conservation: since $F_c$ is always perpendicular to the velocity, it does not do work. Therefore, the kinetic energy and the potential energy are conserved. 
  - $T_0 + V_0 = T_1 + V_1$, where $T$ is the kinetic energy and $V$ is the potential energy.
  - Initial condition: 
    - $T_0 = \frac{1}{2}mv_0^2=0$, because the ball is released from rest.
    - $V_0 = mg \triangle h = 0$, where $\triangle h$ is the height difference between the initial position and the current position.
    - $T_1 = \frac{1}{2}mv_1^2$, $V_1 = mg\triangle h_1$, where $\triangle h_1 = -L \sin\theta$.

## Solution
Energy conservation:
$$
\begin{aligned}
\frac{1}{2}mv_1^2 + mg\triangle h_1 &= \frac{1}{2}mv_0^2 + mg\triangle h_0\\
\frac{1}{2}mv_1^2 + mg\triangle h_1 &= 0\\
\frac{1}{2}mv_1^2 &= -mg\triangle h_1\\
\frac{1}{2}mv_1^2 &= mgL\sin\theta\\
v_1 &= \sqrt{2gL\sin\theta}
\end{aligned}
$$

N-T coordinate system:
N dimension:
$$
\begin{aligned}
F_c - mg\sin\theta &= ma_n\\
F_c - mg\sin\theta &= m\frac{v_1^2}{L}\\
F_c &= mg\sin\theta + m\frac{v_1^2}{L}\\
F_c &= mg\sin\theta + m\frac{2gL\sin\theta}{L}\\
F_c &= 3mg\sin\theta 
\end{aligned}
$$
The tension threshold is $F_c = 2mg$, so:
$$
\begin{aligned}
3mg\sin\theta &= 2mg\\
\sin\theta &= \frac{2}{3}\\
\theta &= \sin^{-1}\frac{2}{3}\\
\theta &= 41.8 \degree
\end{aligned}
$$


# Problem 2

![](D:\UWM\Dynamics_TA\Discussion_4_2_Sol\Problem2.png)

## Recall and Analysis

Conservation of Energy:

$$
T_1+V_1=T_2+V_2
$$

For springs, its potential energy is: 
$$
V = \frac{1}{2} k \Delta x^2
$$
We can recall the equation of kinetic energy from 14.1:
$$
T=\frac{1}{2}mv^2
$$

## Solution

Given $m=2.85oz$

The ball starts from rest ($v_1=0$) with plunger compression of 2 inch. So the initial condition can be listed as: $v_1=0,\Delta x_1=2\ inch$
$$
T_1 = \frac{1}{2}mv_1^2=0,\quad V_1 = \frac{1}{2} k \Delta x_1^2
$$


The ball is released with speed $v_2=v$, when the spring returns its rest position (and no longer)

Final Condition $v_2 = 15 ft/s, \Delta x_2 = 0 $
$$
T_2 = \frac{1}{2}mv_2^2 ,\quad V_2 =\frac{1}{2} k \Delta x_2^2= 0
$$
List the Conservation of Energy equation,
$$
T_1+V_1=T_2+V_2
$$
and plug in the terms of potential and kinetic energy, we have:

$$
\begin{align}
\frac{1}{2}k\Delta x_1^2&=\frac{1}{2}mv^2\\
k&=\frac{mv^2}{\Delta x_1^2}\\
k&= 44.81 lb/ft
\end{align}
$$
