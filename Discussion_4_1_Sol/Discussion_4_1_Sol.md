# Problem 1
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_4_1_Sol/Screenshot%202023-10-10%20190334.png?raw=true" width="500"/>   
</div>

## Recall and Analysis
- Variance of kinetic energy: $U_{1 \rightarrow 2} = T_2 - T_1 =\frac{1}{2} m v_2^2 - \frac{1}{2} m v_1^2$
- Work done by the force: $W_{1 \rightarrow 2} = \int_{1}^{2} \vec{F} \cdot d \vec{r}$
- The work done by the forces acting on the particle as it moves from position 1
to position 2 is equal to the change in the particle’s kinetic energy between those two positions, i.e., $W_{1 \rightarrow 2} = U_{1 \rightarrow 2}$

- Here, it's about stopping distance, so $v_2 = 0$, $v_1 = v$, $U_{1 \rightarrow 2} = - \frac{1}{2} m v^2$
- For the work done by the force, we have gravity and friction. (_Direction_)

<!-- Segmention page -->
<div style="page-break-after: always;"></div>

## Solution
The vehicle is driving down, the gravity has a projection on the direction of motion, so it's positive. The friction is against the direction of motion, so it's negative.

External forces: $\vec{F} = \vec{F}_g + \vec{F}_f = mg \sin \theta - \mu_k mg \cos \theta$
So:
$$
\begin{aligned}
W_{1 \rightarrow 2} &= \int_{1}^{2} \vec{F} \cdot d \vec{r} \\
&= (mg \sin \theta - \mu_k mg \cos \theta) \int_{1}^{2}  (1)\cdot d \vec{r} \\
&= (mg \sin \theta - \mu_k mg \cos \theta) (r_2 - r_1) \\
&= (mg \sin \theta - \mu_k mg \cos \theta) d\\
\end{aligned}
$$
where $d$ is the stopping distance.

Since $W_{1 \rightarrow 2} = U_{1 \rightarrow 2}$, we have:
$$
\begin{aligned}
W_{1 \rightarrow 2} &= U_{1 \rightarrow 2} \\
(mg \sin \theta - \mu_k mg \cos \theta) d &= - \frac{1}{2} m v^2 \\
d &= \frac{- \frac{1}{2} m v^2}{mg \sin \theta - \mu_k mg \cos \theta} \\
&= \frac{v^2}{2g(\mu_k \cos \theta - \sin \theta)} \\
&= 25.22 \text{ m}
\end{aligned}
$$

<!-- Segmention page -->
<div style="page-break-after: always;"></div>

# Problem 2

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_4_1_Sol/Screenshot%202023-10-10%20193308.png?raw=true" width="500"/>   
</div>

## Recall and Analysis
- $W_{1 \rightarrow 2} = U_{1 \rightarrow 2}$:
  - where $W_{1 \rightarrow 2}$ is the work done by the impact force, and $U_{1 \rightarrow 2}$ is the change in kinetic energy.
  - The bumper is to slown down the boat until it stops, so $v_2 = 0$.

<div style="page-break-after: always;"></div>

## Solution
- External forces: $\vec{F} = \vec{F}_i = -\beta x^3$, the impact force is negative because it's against the direction of motion.
- So:
$$
\begin{aligned}
W_{1 \rightarrow 2} &= \int_{1}^{2} \vec{F} \cdot d \vec{r} \\
&= -\beta \int_{1}^{2} x^3 \cdot d \vec{r} \\
& = -\beta \frac{1}{4} x^4 \Big|_{0}^{d} \\
&= - \frac{\beta}{4} d^4 \\
\end{aligned}
$$
where $d$ is the stopping distance.
- For the change in kinetic energy, we have:
$$
\begin{aligned}
U_{1 \rightarrow 2} &= T_2 - T_1 \\
&= \frac{1}{2} m v_2^2 - \frac{1}{2} m v_1^2 \\
&= 0 - \frac{1}{2} m v_1^2 \\
\end{aligned}
$$
where $v_1$ is the initial velocity.

- Since $W_{1 \rightarrow 2} = U_{1 \rightarrow 2}$, we have:
$$
\begin{aligned}
W_{1 \rightarrow 2} &= U_{1 \rightarrow 2} \\
-\frac{\beta}{4} d^4 &= - \frac{1}{2} m v_1^2 \\
&v = \sqrt{\frac{2 \beta}{4m} d^4} \\
&= 7.093 \text{ ft/s}
\end{aligned}
$$  