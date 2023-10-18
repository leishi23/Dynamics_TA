

## Problem 1

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_4_3_Sol/Screenshot%202023-10-17%20221446.png?raw=true" width="500"/>   
</div>


### Recall & Analysis

- The only force doing work here is the internal friction force between crate and platform. 
- "Neglecting the vertical motion" means that there is no variation of the vertical position of the system, i.e. no variation of the potential energy. 
- $T_1 + V_1 + U_{1-2} = T_2 + V_2 $, where $T$ is the kinetic energy, $V$ is the potential energy, and $U$ is the work done by the internal friction force.
  - $T_1 = \frac{1}{2} m_{1} v_0^2$
  - $T_2 = \frac{1}{2} (m_1+m_2) v^2$, where $m_1$ is the mass of the crate, $m_2$ is the mass of the platform, $v_0$ is the initial velocity of the crate, and $v$ is the final velocity of the crate and the platform.
  - $U_{1-2} = \mu_k m_1 g d$, where $d$ is the relative distance the crate moves on the platform.

### Solution
$$
\begin{align} \nonumber
  T_1 &= \frac{1}{2} m_{1} v_0^2 \\ \nonumber
&= \frac{1}{2} \times 200 \times 12^2 \\ \nonumber
&= 14400 \nonumber
\end{align}
$$

$$
\begin{align} \nonumber
  T_2 &= \frac{1}{2} (m_1+m_2) v^2 \\ \nonumber
&= \frac{1}{2} \times 900 \times 2.667^2 \\ \nonumber
&\approx 3200 \nonumber
\end{align}
$$

Since no variation of the vertical position of the system, $V_1 = V_2$.

$$
\begin{align} \nonumber
  U_{1-2} &= \mu_k m_1 g d \\ \nonumber
&= 0.25 \times 200 \times 32.2 \times d \\ \nonumber
&= 1610d \nonumber
\end{align}
$$

So, $T_1 + V_1 + U_{1-2} = T_2 + V_2 $ becomes $14400 + V_1 + 1610d = 3200 + V_2$, then $d = 6.96$ ft. 
> The unit is feet because everything is in the imperial system.
