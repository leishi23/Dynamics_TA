# Problem 1

![Prbloem1](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_7_Sol/Problem_1.png?raw=true              )

## Recall & Analysis
![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_7_Sol/Screenshot%202023-09-26%20232729.png?raw=true)


The length of all ropes are constant, so we can set up the equations with them.

Here, we have three ropes: $L_1,L_2,L_3$ , $L_1$ is $G - F - B - E - B$, $L_2$ is $G - C -D$, $L_3$ is $G - D -A$. And their lengths are constant, so we can set up the equations with them.

## Solution

In case to find $v_G$ and $a_G$, we should first determine the expression of  $y_G$. But we don't need the the explicit form of it, since our final goal is velocity and acceleartion.

First we need to set up our coordinates system, where $y$ axis points downwards.

As the lengths of all ropes($L_1,L_2,L_3$) don't change over time, we can set up the equations with them and coordinates of all pulleys.

![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_7_Sol/Screenshot%202023-09-26%20235037.png?raw=true)

$$
\left\{
\begin{align} \nonumber
L_1&=y_G+3y_B&\\ \nonumber
L_2&=(y_G-y_C) + (y_D-y_C)&\\ \nonumber
L_3&=(y_G-y_D) +(y_A - y_D) &\\ \nonumber
L_4&=y_C-y_B&\\ \nonumber
\end{align}
\right.
$$

$$
\left\{
\begin{align} \nonumber
L_1&=y_G+3y_B&\\ \nonumber
L_2&=y_G+y_D-2y_C&\\ \nonumber
L_3&=y_A+y_G-2y_D&\\ \nonumber
L_4&=y_C-y_B&\\ \nonumber
\end{align}
\right.
$$
Do derivative w.r.t. time, we have:
$$
\left\{
\begin{align} \nonumber
0&=\dot{y_G}+\dot{3y_B}&\\ \nonumber
0&=\dot{y_G}+\dot{y_D}-\dot{2y_C}&\\ \nonumber
0&=\dot{y_G}+\dot{y_A}-\dot{2y_D}&\\ \nonumber
0&=\dot{y_C}-\dot{y_B}&\\ \nonumber
\end{align}
\right.
$$
So, $\dot{y_B}=\dot{y_C}$, and plug it into the first and second equation, we have: $\dot{y_D}=-\frac{5}{3}\dot{y_G}$, then plug it into the third equation, we have: 
$$
\begin{align}\nonumber
\dot{y_G}&=-\frac{3}{13}\dot{y_A}&\\ \nonumber
\end{align}\\
$$
Placing $\dot{y_a}=v_0=3ft/s$ inside, we have $\dot{y_G}=-0.692ft/s$

As for acceleration, do time derivative, We have
$$
\begin{align}\nonumber
\ddot{y_G}&=-\frac{3}{13}\ddot{y_A}&\\ \nonumber
\end{align}\\
$$
Where $\ddot{y_A}=a_0=aft/s$, and $\ddot{y_G}=0.231ft/s^2$





# Problem2

![](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_7_Sol/Problem_2.png?raw=true)

## Recall & Analysis

$$
\vec{r}_B=\vec{r}_A+\vec{r}_{B/A}
$$
Same as the previous problem, we can set up the equations with the lengths of all ropes.



## Solution

make $\vec{x}$ pointing downwards the slope.
$$
L=3x_A+x_B\\
0=3\ddot{x}_A+\ddot{x}_B\\
0=3\ddot{x}_A+\ddot{x}_A\\
$$
using the fact $\ddot{x}_A=a_0$, we have
$$
\vec{a}_B=-3\vec{a}_A=-3a_0=-11.10 m/s^2 
$$
where the positive direction is pointing downwards the incline.

$$
\vec{x}_{B/A}(t)=\vec{x}_{B/A}(0) + \dot{\vec{x}}_{B/A}(0)t + \frac{1}{2}\vec{a}_{B/A}t^2\\
\vec{x}_{B/A}(t)=\vec{x}_{B/A}(0) + \dot{\vec{x}}_{B/A}(0)t + \frac{1}{2}(\vec{a}_{B}-\vec{a}_{A})t^2\\
\vec{x}_{B/A}(t)=\vec{x}_{B/A}(0) + \dot{\vec{x}}_{B/A}(0)t + \frac{1}{2}(-3a_0-a_0)t^2
$$

Since the block is released from rest, we have $\dot{\vec{x}}_{B/A}(0)=0$, and $\vec{x}_{B/A}(0)=0$, so we have:
$$
\vec{x}_{B/A}(t)=\frac{1}{2}(-4a_0)t^2\\
\vec{x}_{B/A}(t)=-2a_0t^2\\
$$
When the distance $d=0.2m$, we have:  
$$
-0.2=-2a_0t^2\\
t=0.1644s
$$
