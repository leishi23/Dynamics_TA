# Discussion_3_3_Sol

## Problem 1

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/Prob1.png?raw=true" width="500"/>   
</div>


### Recall & Analysis

- The tension along the rope is uniform.(set as $T$)
- friction can be calculated as: $f=\mu N$
- The length of the string is constant.

We can try to draw Full Body Diagram of both $A$ and $B$, and define their direction of acceleration. The external forces applied on A are gravity and tension on the rope.

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/FBD_A.jpg?raw=true" alt="FBD_A" style="zoom:33%;" />

The external forces applied on B are gravity, Normal force by the plan, friction and Tension on the rope.

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/FBD_B.jpg?raw=true" alt="FBD_B" style="zoom:33%;" />

​	We can also use kinematic analysis to determine the relationship between displacement of $A$ and $B$. Where: $\Delta L = 2x_A-x_B=0$

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/Kinematics.jpg?raw=true" alt="FBD_B" style="zoom:33%;" />

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

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/Prob2.png?raw=true" alt="Image Description" width="500"/>   
</div>


### Recall & Analysis

Newton 2nd Law in Cartesian Coordinate system:
$$
\sum F_x=ma_x\\
\sum F_y=ma_y
$$

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/FBD_P.jpg?raw=true" style="zoom:33%;" />

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

# Problem 3
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/Screenshot%202023-10-05%20205225.png?raw=true" alt="Image Description">
</div>

---

## Recall and Analysis
- For this system, it has two contacted objects on the incline and one cable-pulley.
  - Objects keep contacting with the incline, so they have the same acceleration in the direction of the incline.
  - The cable-pulley is frictionless, so the tension is the same on both sides of the cable. As usual, we could use **"the length of the cable is constant"**.
- Build a coordinate system with **$x$-axis along the incline and $y$-axis perpendicular to the incline**.
- For B object, its motion has two parts: 
  - $a_{B/A}$: the acceleration of B object relative to A object, i.e. **y-axis**.
  - $a_{incline}$: the acceleration of B object sliding on the incline, i.e. **x-axis**.

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/%E5%9B%BE%E7%89%87_20231005211725.jpg?raw=true" alt="Image Description" width="700"/>   
</div>

- Obj A: 
  - **y-axis**: $\sum F_y = ma_y = 0$, with normal force from incline, cabel tension and gravity's component.
  - **x-axis**: $\sum F_x = ma_x$, with gravity's component, cabel tension and normal force from B.

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/%E5%9B%BE%E7%89%87_20231005211732.jpg?raw=true" alt="Image Description" width="700"/>   
</div>

- Obj B: 
  - **y-axis**: $\sum F_y = ma_y = 0$, with cabel tension and gravity's component.
  - **x-axis**: $\sum F_x = ma_x$, with gravity's component and normal force from A.

---

## Solution

- Obj A:
  - **y-axis**: $N_{A} - T - w_A\cos20 \degree = 0$
  - **x-axis**: $w_A\sin20 \degree + N_{AB} - T = m_Aa_A$
- Obj B:
  - **y-axis**: $ w_B\cos20 \degree - T= m_Ba_{B/A}$
  - **x-axis**: $w_B\sin20 \degree - N_{AB} = m_Ba_A$, because B has the same acceleration as A in the direction of the incline.
- 4 equations and 5 unknowns: $N_A, N_{AB}, T, a_A, a_{B/A}$.
- Cable length is constant: $S_A + S_{B/A} = constant$, so $a_A + a_{B/A}=0$, COOL! Now we have 4 equations and 4 unknowns. So we could solve them.
  ![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_3_Sol/%E5%9B%BE%E7%89%87_20231005215134.jpg?raw=true=200x)

$$
a_A = (\frac{w_A\sin20 \degree + w_B(\sin20 \degree - \cos20 \degree)}{w_A + 2w_B})g= -0.243 ft/{s^2}\\
T = (\frac{w_A+ w_B}{g})(g\sin20 \degree - a_A)=27.96lb\\
$$
