# Discussion_3_3_Sol

## Problem 1

![](D:\UWM\Dynamics_TA\Discussion_3_3_Sol\Prob1.png)



### Recall & Analysis

- The tension along the rope is uniform.(set as $T$)
- friction can be calculated as: $f=\mu N$
- The length of the string is constant.

We can try to draw Full Body Diagram of both $A$ and $B$, and define their direction of acceleration. The external forces applied on A are gravity and tension on the rope.

<img src="D:\UWM\Dynamics_TA\Discussion_3_3_Sol\FBD_A.jpg" alt="FBD_A" style="zoom:33%;" />

The external forces applied on B are gravity, Normal force by the plan, friction and Tension on the rope.

<img src="D:\UWM\Dynamics_TA\Discussion_3_3_Sol\FBD_B.jpg" alt="FBD_B" style="zoom:33%;" />

​	We can also use kinematic analysis to determine the relationship between displacement of $A$ and $B$. Where: $\Delta L = 2x_A-x_B=0$

<img src="D:\UWM\Dynamics_TA\Discussion_3_3_Sol\Kinematics.jpg" alt="FBD_B" style="zoom:33%;" />

### Solution

First applied Newton 2nd Law on both A and B:

for A:
$$
m_Aa_A=m_Ag-T\quad(1)
$$
for B (Here we skipped the equations $N=m_Bg$ and $f = \mu N$):
$$
m_Ba_B=2T-\mu m_Bg\quad(2)
$$

Here we have 2 equations and 3 unknown variables: $a_A,a_B,T$, so we still need to analyze the kinematics of the system to find other constraints.

Give the fixed length of the rope, we have:
$$
\Delta L =x_A-2x_B=0\\
x_A=2x_B
$$
the equation's second derivate of time yields:

$$
a_A = 2a_B\quad(3)
$$
With 3 equations and 3 unknows, we can solve all of them, but most importantly, $a_A$
$$
a_A=\frac{4m_A-2m_B}{m_B+4m_A}\mu g=20.3ft/s^2
$$

Therefore, the velocity of $A$ should be:
$$
\begin{align}
v_A(t)&=v_0+a_At\\
v_A(2)&=4+20.3*2\\
v_A(2)&=44.6ft/s
\end{align}
$$
And it is moving downwards.

## Problem 2

![](D:\UWM\Dynamics_TA\Discussion_3_3_Sol\Prob2.png)

### Recall & Analysis

Newton 2nd Law in Cartesian Coordinate system:
$$
\sum F_x=ma_x\\
\sum F_y=ma_y
$$

<img src="D:\UWM\Dynamics_TA\Discussion_3_3_Sol\FBD_P.jpg" style="zoom:33%;" />

### Solution

**(a).**  With Full Body diagram of the plywood, we can apply Newton 2nd Law of it in Cartesian Coordinate system.(Here we set $\alpha = 20^o$)

On $x-axis, \sum F_x=ma_x$:
$$
fcos\alpha-Nsin\alpha=ma_t -ma_{p/t}cos\alpha
$$
On $y-axis, \sum F_y=ma_y$:
$$
Ncos\alpha-fsin\alpha =-ma_{p/t}sin\alpha
$$
for this case, at the critical state where the plywood started sliding,:

- the friction would be static friction ($\mu=\mu_s$),
- the relative acceleration would be 0 ($ma_{p/t}=0$).

With $f = \mu_s N$, we have the equations:
$$
\left\{
\begin{align}
\mu_s N cos\alpha-Nsin\alpha&=ma_t&(1)\\
Ncos\alpha-\mu_s N sin\alpha&=0&(2)
 \end{align}
\right.
$$
where 2 equations and 2 unknowns $a_t,N$, we can solve the minimum acceleration $a_t$ to be:
$$
a_t=g\frac{\mu_s cos 20^o-sin20^o}{cos 20^o+\mu_s sin20^o}
$$
and $a_t=0.31m/s^2$

**(b).** The analysis are similar to **(a)**, but the differences are:

- friction would be kinetic friction, so $f = \mu_k N$

- $a_{p/t}$ is an unknown value.

But before we solve $a_t$, we might use given conditions to solve $a_{p/t}$.  Note that starting position and velocity are all 0.

$$
\begin{align}
x_{p/t}(t)&=x_{p/t}|_{t=0}+v_{p/t}|_{t=0}t+\frac{1}{2}a_{p/t}t^2\\
&=\frac{1}{2}a_{p/t}t^2
 \end{align}
$$
Plug in $x_{p/t}(t)=2m$ and $t=0.9s$, we can find $a_{p/t}=4.94m/s^2$

 This time, the dynamics equations should be:
$$
\left\{
\begin{align}
\mu_k N cos\alpha-Nsin\alpha&=ma_t-ma_{p/t}cos\alpha&(1)\\
Ncos\alpha-\mu_k N sin\alpha&=-ma_{p/t}sin\alpha&(2)
 \end{align}
\right.
$$
With 2 equations and 2 unknown variables ($a_t$ and $N$), we can solve:
$$
a_t=\frac{\mu_k cos 20^o-sin20^o}{cos 20^o+\mu_k sin20^o}(g-a_{p/t}sin20^o)+a_{p/t}cos20^o
$$
So, $a_t=4.17m/s^2$.

## Problem 3

![](D:\UWM\Dynamics_TA\Discussion_3_3_Sol\Prob3.png)