## Problem 1

![image-20231107195436910](./Screenshot%202023-11-28%20133131.png)

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
![image-20231107195436910](./Screenshot%202023-11-28%20140302.png)

> ATTENTION: 
> - Denote the center of mass as **G** and the pivot point as **B**.
> - There are two **$h$** in the figure: the left one is the distance from the center of mass to the force application point, and the right one is the height of the block. Now, we are going to use **$l$** to represent the height of the block.

### Review
- For the force and moment equilibrium:
  - (x) $P = ma_x$
  - (y) $0 = ma_y \rightarrow a_y = 0$, because the block is not moving in the y-direction
  - ($\theta$) $-Ph = I\alpha = \frac{1}{12}ml^2\alpha$
- $\vec{a_B} = \vec{a_G} + \vec{\alpha} \times \vec{r_{G/B}} - \vec{\omega}^2 \times \vec{r_{G/B}}$
  - $\vec{a_B}$ is the acceleration of point B
  - $\vec{a_G}$ is the acceleration of point G, i.e. the center of mass
  - $\vec{\alpha}$ is the angular acceleration of the block
  - $\vec{r_{G/B}}$ is the position vector from point B to point G
  - $\vec{\omega}$ is the angular velocity of the block, which is **ZERO** in this case.
    - Because $G$ and $B$ are rotating together, so there is no relative rotation between them.

<div style="page-break-after: always;"></div>

### Solution

<div style="page-break-after: always;"></div>

## Problem 3
![image-20231107195436910](./Screenshot%202023-11-28%20140148.png)