## Problem. 1 Alternative

We only use polar coordinate system to find the real acceleration, we first try to proof $\vec{a}=a_r$.

$\because a_z=0$, and $a_\theta=\ddot{\theta}r+2\dot{\theta}\dot{r}=0$

$\therefore \vec{a}=a_r$

Then we draw the FBD, and suppose $f$ points up(negative $f$ will be pointing down). Instead of writing x-y composition, we list equations of forces along and perpendicular to the rail:
$$
\left\{
\begin{align}
m\frac{v^2}{r}sin\alpha&=f-mgcos\alpha\\
0&=N-mgsin\alpha+m\frac{v^2}{r}cos\alpha
 \end{align}
\right.
$$
(we can call $m\frac{v^2}{r}$ centrifugal force).

We know that friction force range:
$$
-\mu N \leq f \leq \mu N
$$
plug in the representation of $f$ and $N$:
$$
-\mu(mgsin\alpha-m\frac{v^2}{r}cos\alpha)
\leq
m\frac{v^2}{r}sin\alpha+mgcos\alpha
\leq
\mu(mgsin\alpha-m\frac{v^2}{r}cos\alpha)
$$
only $v$ is unknown in this inequation. Solve range of $v$:
$$
rg\frac{cos\alpha+\mu sin\alpha}{sin\alpha-\mu cos\alpha}
\leq
v^2
\leq
rg\frac{cos\alpha-\mu sin\alpha}{sin\alpha+\mu cos\alpha}
$$
so $v\in [6.18,13.04]ft/s$

