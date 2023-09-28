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
- For trolley A, build a coordinate with $\vec{CD}$ as x-axis and upward $\uparrow$ as y-axis.
$$
\begin{align} \nonumber
\sum F_x &= ma_x = T_{CD} - W_A\sin 25\degree - T_{AB}\sin 25\degree \\ \nonumber
\sum F_y &= ma_y = T_{AB} - W_B  \\ \nonumber
\end{align}
$$

- For relative motion between A and B, we have: $\vec{a}_{B} = \vec{a}_{A} + \vec{a}_{B/A}$. 
- Build a N-T coordinate on crate B with $\vec{AB}$ as N-axis.

> Hint: 
> $a_{B/A}$ is in N-T coordinate. To calculate the normal acceleration, i.e. **$(a_{B/A})_n$**
> For crate B, there are two forces acting on it: $T_{AB}$ and $W_B$. So, acceleration of B is only in the vertical direction.


## Solution
$$\vec{a}_B = \vec{a}_A + \vec{a}_{B/A}$$
Since $a_B$ is only in the vertical direction, we have: $\vec{a}_B = a_B \hat{j}$
$\vec{a}_A = a_A (\cos 25\degree \hat{i} + \sin 25\degree \hat{j})$, where $\vec{a}_A = 1.2 ft/s^2$.
$\vec{a}_{B/A} = (a_{B/A})_n \hat{u}_n + (a_{B/A})_t \hat{u}_t$, where $(a_{B/A})_n = \frac{v_{B/A}^2}{\rho} = 0$ because crate is released from **rest**. And $\hat{u}_n = \hat{j}$, $\hat{u}_t = \hat{i}$.

$$
\begin{align} \nonumber
a_B \hat{j} &= a_A (\cos 25\degree \hat{i} + \sin 25\degree \hat{j}) + (a_{B/A})_n \hat{j} + (a_{B/A})_t \hat{i} \\ \nonumber
\end{align}
$$
So, $a_B = a_A \sin 25\degree + (a_{B/A})_n = 1.2 \sin 25\degree + 0 = 0.5071 ft/s^2$. 
$a_{B/A} = (a_{B/A})_t \hat{i} = -a_A \cos 25\degree \hat{i} = -1.2 \cos 25\degree \hat{i} = -1.0876 \hat{i} ft/s^2$.

$T_{CD} = W_A\sin 25\degree + T_{AB}\sin 25\degree + ma_x = W_A\sin 25\degree + (W_B + m_Ba_B)\sin 25\degree + ma_x=233.03 lb$.

<br>
<br>
<br>
<br>
<br>

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
- `Maximum reading` is the maximum force that generated from spring, that is the maximum displacement of spring. For maximum displacement, the corresponding velocity is zero.
- `Maximum speed` means acceleration is zero. 
- $\sum F_x: mg-kx = ma_x$, so $a_x = g-\frac{kx}{m}$.
- $v^2 = v_0^2 + 2a_x \Delta x$ (Since $a_x$ depends on x, we need to integrate it to get the velocity.)

## Solution
$v^2 = v_0^2 + 2a_x \Delta x = 0 + 2\int_{0}^{x} (g-\frac{kx}{m}) dx = 2gx - \frac{kx^2}{m}$.
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
