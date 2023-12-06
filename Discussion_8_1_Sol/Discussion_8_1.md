## Problem 1

<!-- ![image-20231107195436910](./Screenshot%202023-11-28%20133131.png) -->
<img src="./Screenshot 2023-12-05 131837.png" alt="oblique_impact" style="zoom:57%; center;" />

### Review and Hints
- Both cases are: $T_1 + V_1 + W_{1-2} = T_2 + V_2$
  - $W_{1-2}$ is the work done by the unconservative force, like friction. Here, we set $W_{1-2} = 0$.
  - $T$ is the kinetic energy, including the rotational kinetic energy and the translational kinetic energy.
- For the moment of inertia, we have:
  - $I_A = \frac{1}{2}mR^2$
  - $I_B = mR^2$

<div style="page-break-after: always;"></div>

### Solution

#### Part (a)

$$
\begin{aligned}
T_1 + V_1 &= T_2 + V_2 \\
mgb\sin \theta + 0 &= \frac{1}{2}mv_2^2 + \frac{1}{2}I_A\omega_2^2 \\
mgb\sin \theta &= \frac{1}{2}mv_2^2 + \frac{1}{2}(\frac{1}{2}mr^2)(\frac{v_2}{r})^2 \\
mgb\sin \theta &= \frac{1}{2}mv_2^2 + \frac{1}{4}mv_2^2 \\
mgb\sin \theta &= \frac{3}{4}mv_2^2 \\
v_2 &= \sqrt{\frac{4}{3}gb\sin \theta}
\end{aligned}
$$

#### Part (b)

$$
\begin{aligned}
T_1 + V_1 &= T_2 + V_2 \\
mgb\sin \theta + 0 &= \frac{1}{2}mv_2^2 + \frac{1}{2}I_B\omega_2^2 \\
mgb\sin \theta &= \frac{1}{2}mv_2^2 + \frac{1}{2}(mr^2)(\frac{v_2}{r})^2 \\
mgb\sin \theta &= \frac{1}{2}mv_2^2 + \frac{1}{2}mv_2^2 \\
mgb\sin \theta &= mv_2^2 \\
v_2 &= \sqrt{gb\sin \theta}
\end{aligned}
$$

<div style="page-break-after: always;"></div>

## Problem 2

<img src="./Screenshot 2023-12-05 134336.png" alt="oblique_impact" style="zoom:57%; center;" />

<div style="page-break-after: always;"></div>

## Solution

(a) Find number of revolutions of B when $\omega_B=600rpm$.(Where $600rpm = 20\pi\ rad/s$ )

​	Again, we can apply work energy equation in this problem.
$$
T_1 + V_1 + U_{unc} = T_2+V_2
$$
​	Where $T_1,V_1$ and $V_2$ are all 0. And $T_2=\frac{1}{2}I_A\omega_A^2+\frac{1}{2}I_B\omega_B^2$.

​	For work done by unconservative force: $U_{1\rightarrow 2}=M\cdot \theta_B + F_T\theta_Ar_A-F_T\theta_Br_B $.

​	As we learnt the gear equations: $\omega_Ar_A=\omega_Br_B$, to integrate w.r.t. t on both sides, we have:
$$
\theta_Ar_A=\theta_Br_B
$$
​	Plugging in the terms into the equation, we have:
$$
M\cdot \theta_B=\frac{1}{2}I_A\omega_A^2+\frac{1}{2}I_B\omega_B^2
$$
​	Here $\omega_A = \omega_B\frac{r_B}{r_A}=5\pi\ rad/s$, and $I_A=m_Ak_A^2$, $I_B=m_Bk_B^2$.
$$
M\theta_B=\frac{1}{2}[m_Ak_A^2(\frac{r_B}{r_A})+m_Bk_B^2]\omega_B^2
$$
​	Plug in the values to have: $\theta_B=27.34rad\approx4.35r$

(b) This time we look at Gear B only.
$$
T_1 + V_1 + U_{unc} = T_2+V_2
$$
​	Here $T_2=\frac{1}{2}I_B\omega_B^2=\frac{1}{2}m_Bk_B^2\omega_B^2$

​	And $U_{1\rightarrow 2}=M\cdot \theta_B -F_T\theta_Br_B$, where $\theta_B=27.34rad$ as solved in part (a). Plug in the values into the equation:
$$
M\cdot \theta_B -F_T\theta_Br_B=\frac{1}{2}m_Bk_B^2\omega_B^2
$$
​	And solving for $F_t = 46.15 N$