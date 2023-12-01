## Problem 1

<!-- ![image-20231107195436910](./Screenshot%202023-11-28%20133131.png) -->
<img src="./Screenshot 2023-11-30 232634.png" alt="oblique_impact" style="zoom:37%; center;" />

### Review and Hints
- For the force analysis:
  - x-dimension: $ -f=ma_x$
  - y-dimension: $ N-mg=ma_y$
  - $\theta$-dimension: $ NL - fL = I\alpha = mL^2\alpha$
  - Hence, we have 3 equations but 5 unknowns: $N$, $f$, $a_x$, $a_y$, and $\alpha$.
- Let's solve for $a_x$ and $a_y$ first:
  - $\vec{a}_c = \alpha (-L \hat{i})$
  - $\vec{a}_G = \vec{a}_c + \vec{\alpha} \times \vec{r_{G/c}} - \vec{\omega}^2 \times \vec{r}_{G/c}$
    - where $\vec{a}_G$ is the acceleration of point G, i.e. the center of mass
    - $\vec{a}_c$ is the acceleration of point c, i.e. the center of tthe circle 
    - $\vec{\omega}$ is the angular velocity of relative rotation, which is **ZERO** in this case.
      - Because $G$ and $c$ are rotating together, so there is no relative rotation between them.
  - so, $\vec{a}_G = -\alpha L \hat{i} + \vec{\alpha} \times \vec{r_{G/c}} = -\alpha L \hat{i} + \alpha \hat{k} \times (-L\hat{i}) = -\alpha L \hat{i} - \alpha L \hat{j} $
  - $a_x = -\alpha L$, $a_y = -\alpha L$

<div style="page-break-after: always;"></div>

### Solution

$$
\begin{align} \nonumber
f &= mL\alpha\\ \nonumber
N-mg &= -mL\alpha\\ \nonumber
NL - fL &= mL^2\alpha\\ \nonumber
\end{align}
$$
Hence, we have:
$$
\begin{align} \nonumber
N &= mg - mL\alpha\\ \nonumber
f &= mL\alpha\\ \nonumber
\alpha &= \frac{g}{3L}\\ \nonumber
\end{align}
$$

for no slipping condition, we have: $f \leq \mu_s N$, so:
$$
\begin{align} \nonumber
N &= mg - mL\alpha = \frac{2}{3}mg\\ \nonumber
f &= mL\alpha = \frac{1}{3}mg\\ \nonumber
\end{align}
$$
And $f \leq \mu_s N$ becomes:
$$
\begin{align} \nonumber
\frac{1}{3}mg &\leq \mu_s \frac{2}{3}mg\\ \nonumber
\mu_s &\geq \frac{1}{2}\\ \nonumber
\end{align}
$$

<div style="page-break-after: always;"></div>

## Problem 2
<img src="./Screenshot 2023-11-30 234839.png" alt="oblique_impact" style="zoom:97%; center;" />

<div style="page-break-after: always;"></div>

<img src="./Screenshot 2023-11-30 234854.png" alt="oblique_impact" style="zoom:77%; center;" />

