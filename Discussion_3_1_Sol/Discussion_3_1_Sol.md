# Problem 1

![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_1_Sol/Screenshot%20from%202023-09-28%2017-24-09.png?raw=true)

## Recall and Analysis
### 1. Recall
- Newton's 2nd Law
$$
\begin{aligned}
\sum \vec{F} &= m \vec{a} \\
\end{aligned}
$$

- Acceleration in N-T coordinate
$$
\begin{aligned}
\vec{a} &= \dot{v} \hat{u}_t + \frac{v^2}{\rho} \hat{u}_n \\
\end{aligned}
$$

### 2. Analysis
- Try to apply Newton second law on both **A** and **B**. 
- The motion of trolley **A** is restricted on the rail, so the sum of force perpendicular to the rail should be zero. define $\vec{x}$ axis with the same direction as $\vec{CD}$, along the slope . We can write the Newton-Euler equation of **A** as:

$$
\sum F_x = ma_x = T_{CD} - m_Ag\sin 25^o - T_{AB}\sin 25^o \\ \nonumber
$$

> Hint: writing $\sum F_y=m_Aa_Y$ will also introduce an unknown normal force N, so it can not help us solve the problem.



<img src="D:\UWM\Dynamics_TA\Discussion_3_1_Sol\A_FBD.jpg" style="zoom: 25%;" />

- For crate **B**, it only have vertical external force, so its Newton-Euler equation should be:
$$
\begin{align} \nonumber
\sum F_y &= m_Ba_y = T_{AB} - m_Bg  \\ \nonumber
\end{align}
$$

<img src="D:\UWM\Dynamics_TA\Discussion_3_1_Sol\B_FBD.jpg" style="zoom:25%;" />

- For relative motion between A and B, we have: $\vec{a}_{B} = \vec{a}_{A} + \vec{a}_{B/A}$. 

- To solve **B**'s' acceleration relative  to **A**, we can try to build a N-T coordinate based on **A**, and make $\vec{AB}$  its Normal axis. Within the coordinate system, relative acceleration can be written as:
  $$
  \vec{a}_{B/A}=(\vec{a}_{B/A})_n\cdot \hat{u}_n+(\vec{a}_{B/A})_T\cdot \hat{u}_T
  $$
  <img src="D:\UWM\Dynamics_TA\Discussion_3_1_Sol\B_NT (2).jpg" style="zoom:25%;" />

- And the acceleration of **B** should be:

$$
\begin{align}
 \vec{a}_B&=\vec{a}_{B/A}+\vec{a}_A \\
 \vec{a_B}&=(\vec{a}_{B/A})_n\cdot \hat{u}_n+(\vec{a}_{B/A})_T\cdot \hat{u}_T+\vec{a}_A
 \end{align}
$$


> Hint: N-T coordinates are built on moving path of particles (Here, **A**). Any acceleration we calculate using $\vec{a} = \dot{v} \hat{u}_t + \frac{v^2}{\rho} \hat{u}_n \\$ will return acceleration relative to **A**.










## Solution

**(1) Solving $\vec{a}_{B/A}$**
$$
\vec{a}_B = \vec{a}_A + \vec{a}_{B/A}\qquad(1)
$$
Forces applied on **B** is only in the vertical direction, therefore:
$$
\vec{a}_B = a_B \hat{j}\qquad (2)
$$
trolley **A** is attached to the rail, therefore:
$$
\vec{a}_A = a_A (\cos 25^o \hat{i} + \sin 25^o \hat{j})\qquad (3)
$$
where $a_A= 1.2 ft/s^2.$

Writing the relative acceleration in N-T coordinate system:
$$
\vec{a}_{B/A} = (a_{B/A})_n \hat{u}_n + (a_{B/A})_t \hat{u}_t
$$
where $(a_{B/A})_n = \frac{v_{B/A}^2}{\rho} = 0$ because crate is released from **rest**. And $\hat{u}_n = \hat{j}$, $\hat{u}_t = -\hat{i}$.

Plug $(2),(3),(4)$ into $(1)$, we have:
$$
\begin{align} \nonumber
a_B \hat{j} &= a_A (\cos 25^o \hat{i} + \sin 25^o \hat{j}) + (a_{B/A})_n \hat{j} + (a_{B/A})_t \hat{i} \\ \nonumber
\end{align}
$$
Separating the $\hat{i}$ and $\hat{j}$ components, we have:
$$
\left\{
\begin{align}
a_B &= a_A \sin 25^o + (a_{B/A})_n\\
0 & = a_A \cos 25^o \hat{i} +(a_{B/A})_t \hat{i}
 \end{align}
\right.
$$
so $a_B$ and $a_{B/A}$ should be:
$$
a_B = a_A \sin 25^o + (a_{B/A})_n = 1.2 \sin 25^o + 0 = 0.5071 ft/s^2\\
a_{B/A} = (a_{B/A})_t \hat{i} = -a_A \cos 25^o \hat{i} = 1.2 \cos 25^o \hat{i} = 1.0876 \hat{i} ft/s^2
$$
**(2) Solving $T_{CD}$**

Newton Euler equation of **A** : $ma_x = T_{CD} - W_A\sin 25^o - T_{AB}\sin 25^o$.

Therefore:
$$
\begin{align}
T_{CD} &= W_A\sin 25^o + T_{AB}\sin 25^o + ma_x \\
&= W_A\sin 25^o + (W_B + m_Ba_B)\sin 25^o + ma_x\\
&=233.03 lbf
 \end{align}
$$
(unit $lbf$ is pounds force).











# Problem 2

![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_1_Sol/Screenshot%20from%202023-09-28%2017-24-25.png?raw=true)

## Recall and Analysis
### 1. Recall
- Newton's 2nd Law
$$
\begin{aligned}
\sum \vec{F} &= m \vec{a} \\
\end{aligned}
$$

- Spring Force
$$
\begin{aligned}
\vec{F}_{spring} &= kx \\
\end{aligned}
$$

### 2. Analysis

- `Maximum reading` is the maximum force that generated from spring, which happens when the spring reaches maximum displacement. The corresponding velocity at maximum displacement is zero, in which case the spring stops compressing and starts to stretch.

- `Maximum speed` means acceleration is zero. In which case the spring stops accelerating and starts decelerate.

- $\sum F_x: mg-kx = ma_x$, so $a_x = g-\frac{kx}{m}$.

- Using chain rule, we have:
  $$
  \begin{align}
  a&=\frac{dv}{dt}\\
  a&=\frac{dv}{dx}\frac{dx}{dt}\\
  a&=v\frac{dv}{dx}\\
   \end{align}
  $$
- Since $a(x)$ depends on $x$, we need to integrate it to get the velocity:
  $$
  \int_{0}^x a(x)dx =\frac{1}{2}(v^2- v_0^2)
  $$








## Solution

$v^2 = v_0^2 + 2\int a_x dx = 0 + 2\int_{0}^{x} (g-\frac{kx}{m}) dx = 2gx - \frac{kx^2}{m}$
For maximum reading/zero velocity:
$$
\begin{align} \nonumber
v^2 &= 2gx - \frac{kx^2}{m} = 0 \\ \nonumber
\end{align}
$$
So, $x = \frac{2mg}{k}$. $F_{max} = kx = 2mg$.

For maximum speed/zero acceleration:
zero acceleration means force balance, so $mg-kx = 0$. So, $x = \frac{mg}{k}$. 
Plug in $x$ to the velocity equation, we have: $v^2 = 2gx - \frac{kx^2}{m} = 2g\frac{mg}{k} - \frac{k(\frac{mg}{k})^2}{m} = \frac{mg^2}{k}$. So, $v = \sqrt{\frac{mg^2}{k}}$.