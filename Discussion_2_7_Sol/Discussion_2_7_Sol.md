# Problem 1

![Prbloem1](D:\UWM\Dynamics_TA\Discussion_2_7_Sol\Problem_1.png)

## Recall & Analysis

![](D:\UWM\Dynamics_TA\Discussion_2_7_Sol\Relative Motion.png)

For velocity and acceleration, we have:
$$
\vec{v_B}=\vec{v_A}+\vec{v_{B/A}}\\
\vec{a_B}=\vec{a_A}+\vec{a_{B/A}}
$$

## Solution

In case to find $v_G$ and $a_G$, we should first determine the expression of  $y_G$. But we don't need the the explicit form of it, since our final goal is velocity and acceleartion.

First we need to set up our coordinates system, where $y$ axis points downwards.

As the lengths of all ropes($L_1,L_2,L_3$) don't change over time, we can set up the equations with them and coordinates of all pulleys:
$$
\left\{
\begin{align}
L_1&=y_G+3y_B&(1)\\
L_2&=y_G+y_D-2y_C&(2)\\
L_3&=y_A+y_G-2y_D&(3)\\
L_4&=y_C-y_B&(4)\\
\end{align}
\right.
$$
Do derivative w.r.t. time, we have:
$$
\left\{
\begin{align}
0&=\dot{y_G}+\dot{3y_B}&(5)\\
0&=\dot{y_G}+\dot{y_D}-\dot{2y_C}&(6)\\
0&=\dot{y_G}+\dot{y_A}-\dot{2y_D}&(7)\\
0&=\dot{y_C}-\dot{y_B}&(8)\\
\end{align}
\right.
$$

by cancelling terms containing $y_B$, $y_C$ and $y_D$ which we don't need, we have:
$$
\begin{align}
\dot{y_G}&=-\frac{3}{13}\dot{y_a}&(9)\\
\end{align}\\
$$
Placing $\dot{y_a}=v_0=3ft/s$ inside, we have $\dot{y_G}=-0.692ft/s$

As for acceleration, do time derivative to (9), We have
$$
\begin{align}
\ddot{y_G}&=-\frac{3}{13}\ddot{y_a}&(9)\\
\end{align}\\
$$
Where $\ddot{y_a}=a_0=aft/s$, and $\ddot{y_G}=0.231ft/s^2$





# Problem2

![](D:\UWM\Dynamics_TA\Discussion_2_7_Sol\Problem_2.png)

## Recall & Analysis

$$
\vec{r}_B=\vec{r}_A+\vec{r}_{B/A}
$$



## Solution

make $\vec{x}$ pointing downwards the slope.
$$
L=3x_A+x_B\\
0=3\ddot{x}_A+\ddot{x}_B
$$
using the fact $\ddot{x}_A=a_0$, we have
$$
\vec{a}_B=-11.10\vec{i}\ m/s^2
$$

$$
\vec{x}_{B/A}=\vec{x}_B-\vec{x}_A
$$

*... To Be Continued*