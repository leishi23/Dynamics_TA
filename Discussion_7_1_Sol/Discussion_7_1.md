## Problem 1

<!-- ![image-20231107195436910](./Screenshot%202023-11-28%20133131.png) -->
<img src="./Screenshot%202023-11-28%20133131.png" alt="oblique_impact" style="zoom:37%; center;" />

### Review
- For the moment of inertia about an axis:
  - $I_{\text{axis}} = \int r^2 dm$
    - $r$ is the distance from the axis of rotation to the mass element
    - $dm$ is the mass element
- Radius of gyration:
  - $k^2 = \frac{I_{\text{axis}}}{m}$
    - $k$ is the radius of gyration
    - $I_{\text{axis}}$ is the moment of inertia about the axis
    - $m$ is the mass of the object

<div style="page-break-after: always;"></div>

### Solution

$$
I_G = \int r^2 dm = \int_{-L/2}^{L/2} r^2 dm \\
$$
As for the mass element, we can use the linear density $\rho$ to represent it:
$$
dm = \rho dV = \rho Adr = \rho \pi b^2 dr \\
$$
where $A$ is the cross-sectional area of the rod, $b$ is the radius of the cross-section, and $dx$ is the length of the mass element. Therefore, we can rewrite the moment of inertia as:
$$
\begin{align}  \nonumber
I_G &= \int_{-L/2}^{L/2} r^2 dm \\ \nonumber
&= \int_{-L/2}^{L/2} r^2 \rho \pi b^2 dr \\ \nonumber
&= \rho \pi b^2 \int_{-L/2}^{L/2} r^2 dr \\ \nonumber
&= \rho \pi b^2 \left[ \frac{r^3}{3} \right]_{-L/2}^{L/2} \\ \nonumber
&= \rho \pi b^2 \left[ \frac{L^3}{24} - \frac{(-L)^3}{24} \right] \\ \nonumber
&= \rho \pi b^2 \left[ \frac{L^3}{12} \right] \\ \nonumber
&= \frac{1}{12} \rho \pi b^2 L^3 \\ \nonumber
\end{align}
$$
As for the mass of the rod, we can use the linear density $\rho$ to represent it:
$$
m = \rho V = \rho AL = \rho \pi b^2 L \\
$$
Therefore, we can rewrite the inertia as:
$$
\begin{align}  \nonumber
I_G &= \frac{1}{12} \rho \pi b^2 L^3 \\ \nonumber
&= \frac{1}{12} \rho \pi b^2 L L^2 \\ \nonumber
&= \frac{1}{12} m L^2 \\ \nonumber
\end{align}
$$
As for the radius of gyration, we have $ k^2 = \frac{I_{\text{axis}}}{m} $, so:
$$
\begin{align}  \nonumber
k = \sqrt{\frac{I_{\text{axis}}}{m}} &= \sqrt{\frac{\frac{1}{12} m L^2}{m}} \\ \nonumber
&= \sqrt{\frac{1}{12} L^2} \\ \nonumber
&= \frac{L}{\sqrt{12}} \\ \nonumber
&= \frac{L}{2\sqrt{3}} \\ \nonumber
\end{align}
$$

<div style="page-break-after: always;"></div>

## Problem 2
<img src="./Screenshot%202023-11-28%20140302.png" alt="oblique" style="zoom:37%;  center;" />

> ATTENTION: 
> - Denote the center of mass as **G** and the pivot point as **B**.
> - There are two **$h$** in the figure: the left one is the distance from the center of mass to the force application point, and the right one is the height of the block. Now, we are going to use **$l$** to represent the height of the block.

### Review
- For the force and moment equilibrium:
  - (x) $P = ma_x$
  - (y) $0 = ma_y \rightarrow a_y = 0$, because the block is not moving in the y-direction
  - ($\theta$) $-Ph = I\alpha = \frac{1}{12}ml^2\alpha$
- $\vec{a_B} = \vec{a_G} + \vec{\alpha} \times \vec{r_{B/G}} - \vec{\omega}^2 \times \vec{r_{B/G}}$
  - $\vec{a_B}$ is the acceleration of point B
  - $\vec{a_G}$ is the acceleration of point G, i.e. the center of mass
  - $\vec{\alpha}$ is the angular acceleration of the block
  - $\vec{r_{G/B}}$ is the position vector from point B to point G
  - $\vec{\omega}$ is the angular velocity of the block, which is **ZERO** in this case.
    - Because $G$ and $B$ are rotating together, so there is no relative rotation between them.

<div style="page-break-after: always;"></div>

### Solution

​	(1) Solving for $\vec{a}_B=0$, we start from analyzing the acceleration equation of $B$.
$$
\vec{a_B} = \vec{a_G} + \vec{\alpha} \times \vec{r_{B/G}} - \vec{\omega}^2 \times \vec{r_{B/G}}
$$
​	Plugging in $\vec{\omega}=0$, $\vec{a}_B=0$, we first have:
$$
\begin{align}
\vec{a_G} &= -\vec{\alpha}\times \vec{r_{B/G}}\\
\vec{a_G} &= -\alpha\hat{k}\times (-\frac{l}{2})\hat{j}\\
\vec{a_G} &= -\frac{\alpha l}{2}\hat{i}\tag{1}   \\
\end{align}
$$
​	In this equation, $\vec{a_G}$ and $\alpha$ remain unknown, so we need to derive their form using our analysis. We have:
$$
\begin{align}
\vec{a_G} &= a_x\hat{i} + a_y\hat{j} \\
\vec{a_G} &= \frac{P}{m}\hat{i}\tag{2}\\
\end{align}
$$

​	And:

$$
\begin{align}
-Ph &= \frac{1}{12}ml^2\alpha\\
\alpha &= -\frac{12Ph}{ml^2}\tag{3}
\end{align}
$$

​	By plugging in (2) and (3) into (1).  We then have an equation containing h and other known values.
$$
P/m = 6Ph/ml\\
h = l/6
$$
​	Which is independent to mass and force.

​	(2) Using similar equation: 
$$
\begin{align}
\vec{a_A} &= \vec{a_G} + \vec{\alpha} \times \vec{r_{A/G}} - \vec{\omega}^2 \times \vec{r_{A/G}}\\
\vec{a_A} &= P/m\hat{i} + -\frac{12Ph}{ml^2}\hat{i}\times (l/2-l/6)+0
\end{align}
$$
​	And we have: $\vec{a_A}=2P/m\hat i$

<div style="page-break-after: always;"></div>

## Problem 3

![image-20231107195436910](./Screenshot%202023-11-28%20140148.png)