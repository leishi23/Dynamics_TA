

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

So, $T_1 + V_1 + U_{1-2} = T_2 + V_2 $ becomes $14400 + V_1 + 1610d = 3200 + V_2$, then $d = 6.96$ ft.. 
> The unit is feet because everything is in the imperial system.


<div style="page-break-after: always;"></div>

## Problem 2

<img src="C:\Users\23472\AppData\Roaming\Typora\typora-user-images\image-20231017233052841.png" alt="image-20231017233052841" style="zoom:64%;" />

### Analysis

​	We can break it down into three stages, (1) the system starting from rest. (2) C was stopped and separated from the system. (3) A hits the ground.

1.  $T_1$=0, 	$V_1=V_A+V_B+V_C$

<img src="C:\Users\23472\AppData\Roaming\Typora\typora-user-images\image-20231018001521849.png" alt="image-20231018001521849" style="zoom: 67%;" />

2. for A, B, and C: $T_2=\frac{1}{2}(m_A+m_B+m_C)v_2^2$,	 $V_2=V_{A2}+V_{B2}+V_{C2}$, 

   or for A and B: $T_2'=\frac{1}{2}(m_A+m_B)v_2^2$,	 $V_2'=V_{A2}+V_{B2}$.

<img src="C:\Users\23472\AppData\Roaming\Typora\typora-user-images\image-20231018002329744.png" alt="image-20231018002329744" style="zoom:67%;" />

3. For A and B: $T_3=\frac{1}{2}(m_A+m_B)v_3^2$,	$V_3=V_{A3}+V_{B3}$

<img src="C:\Users\23472\AppData\Roaming\Typora\typora-user-images\image-20231018002335717.png" alt="image-20231018002335717" style="zoom:67%;" />

### Solution

Since the external force in the system is gravity (conservative force), we can solve it in a kinetic-potential energy fashion: $T_1+V_1+U_{1\rightarrow 2}=T_2+V_2$. Since $C$ was removed in the second stage, we need to break it down into 2 stages.

1. $C$ drops along with $A$ and $B$, and stopped at some height, where: $v_A = v_C = -v_B$. The system travelled $d_1+d_2$

   With: $T_1+V_1+U_{nc}=T_2+V_2$, and $U_{nc}=0$, we have:

   $0+[m_Ag(d_2+d_3)+ m_Cg(d_1+d_2+d_3) ]=\frac{1}{2}(m_A+m_B+m_C)v_2^2+(m_Ag(d_3-d_1)+m_bg(d_1+d_2)+m_Cgd_3) $

   we can use it to solve $v_2$:
   $$
   v_2^2=\frac{2g(m_A+m_C-m_B)(d_1+d_2)}{m_A+m_B+m_C}
   $$
   

   or $v_2=1.72m/s$.

2. $A$ and $B$ continues to move, where $v_A = -v_B$ ,and $T_2'+V_2'+U_{2\rightarrow 3}=T_3'+V_3'$. The system travelled a distance of $d_3-d_1$.

   $\frac{1}{2}(m_A+m_B)v_2^2+[m_Ag(d_3-d_1)+ m_bg(d_1+d_2) ]=\frac{1}{2}(m_A+m_B)v_3^2+(m_bg(d_2+d_3)) $

   We use it to solve $v_3$:
   $$
   v_3^2=\frac{(m_A+m_B)v_2^2+2g(m_A-m_B)(d_3-d_1)}{m_A+m_B}
   $$
   where $v_3=1.19m/s^2$

<div style="page-break-after: always;"></div>

## Problem 3
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_4_3_Sol/Screenshot%202023-10-17%20230018.png?raw=true" width="500"/>   
</div>

### Solution
> $W_1$, $W_2$ are forces.
> $x_2 = 2x_1$

$ T_1 + V_1 + U_{1-2} = T_2 +v_2$, where $T$ is the kinetic energy, $V$ is the potential energy, and $U$ is the work done by the internal friction force.
  - $T_1 = 0$, because the it's released from rest.
  - $T_2 = \frac{1}{2} m_1 v_{1f}^2 + \frac{1}{2} m_2 v_{2f}^2$, where $v_{1f}$ is the final velocity block 1, and $v_{2f}$ is the final velocity of block 2.
  - $U_{1-2} = \mu_k m_1 g d$, where $d = 1ft$ 
  - $V_1 = \frac{1}{2} k x_1^2$, where $x_1 = 1ft$ is the initial displacement of block 1.
  - $V_2 = \frac{1}{2} k x_{1f}^2 + m_2g(x_2 - x_{2f})$, where $x_{1f} = 0.5ft$ is the final displacement of block 1, and $x_{2f} = 1ft$ is the final displacement of block 2, $x_2 = 2ft$ is the initial displacement of block 2.

Assemble all the equations above, we have: $v_{1f}^2 + v_{2f}^2 = 170.64$.
So, $v_{1f} = 5.84 ft/s$, and $v_{2f} = 11.68 ft/s$.

> - Students have 1 week to submit a regrade request to the grader.  Students must write a document outlining why they need a regrade and email it or bring it to office hours.  Warning: regrades may result in a lower score.
> - Q1 Lei Shi
> - Q2 Josh Murwin
> - Q3 Yicheng Zeng

