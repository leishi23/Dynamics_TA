# Problem 1

![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/Screenshot%20from%202023-09-19%2019-31-43.png?raw=true)

## Solution

The question is to find the $\vec{v}$ and $\vec{a}$ at $\theta=30^o$ in radial-transverse coordinates.

Recall the position vector in radial-transverse coordinates taught in class:
![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/Screenshot%20from%202023-09-19%2020-04-39.png?raw=true)
where:

$$
\vec{r}=r\hat{e}_r=(0.9-0.12t^2)\hat{e}_r
$$
Recall the velocity vector in radial-transverse coordinates taught in class:
![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/Screenshot%20from%202023-09-19%2020-07-30.png?raw=true)
where:
$$
\vec{v}=\dot{r}\hat{e}_r+r\dot{\theta}\hat{e}_\theta
$$

to get $\dot{r}$ and $\dot{\theta}$, we need to do some differentiation:
$$
\left\{
\begin{align}
\nonumber \dot{r}&=-0.24t\\
\nonumber \dot{\theta}&=0.3t
\end{align}
\right.
$$

therefore velocity is:
$$
\vec{v}=-0.24t\hat{e}_r+(0.9-0.12t^2)(0.3t)\hat{e}_\theta
$$
When $\theta=30^o$:
recall $\theta=0.15t^2$, so $t^2=\theta/0.15$, i.e.: $t=\sqrt{\frac{\theta}{0.15} }=1.87s$
$$
\vec{v}=-0.45\hat{e}_r+0.27\hat{e}_\theta
$$
for acceleration, recall the formula taught in class:
![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/Screenshot%20from%202023-09-19%2020-00-08.png?raw=true)
$$
\vec{a}=(\ddot{r}-r\omega^2)\hat{e}_r+(r\alpha+2\dot{r}\omega)\hat{e}_\theta
$$
where:
$$
\left\{
\begin{align}
\nonumber r&=0.9-0.12t^2\\
\nonumber \dot{r}&=-0.24t\\
\nonumber \omega&=\dot{\theta}=0.3t
\end{align}
\right.
$$
In acceleration, we know everything except $\ddot{r}$ and $\alpha$, to get them, we need to do some differentiation:
$\ddot{r}=\frac{d\dot{r}}{dt}=-0.24$, $\alpha=\frac{d\omega}{dt}=0.3$ 
Now, we can get the acceleration:
$$
\vec{a}=-0.391\hat{e}_r-0.358\hat{e}_\theta
$$


# Problem 2
![image](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/Screenshot%20from%202023-09-19%2020-35-48.png?raw=true)
## Solution

The acceleration of radial-transverse coordinates:
$$
\begin{align}
\vec{a}&=(\ddot{r}-r\omega^2)\hat{e}_r+(r\alpha+2\dot{r}\omega)\hat{e}_\theta
\end{align}
$$
where: $\alpha = \empty, \ddot{r}=\empty$

therefore:
$$
\vec{a}=-r\omega^2\hat{e}_r++2\dot{r}\omega\hat{e}_\theta
$$
The first term stands for simulated gravity term: $g_s$ (since the direction of $\hat{e_r}$ is outward, while the gravity is downward, so we need to add a negative sign):
$$
g_s=-(-r\omega^2)\geq \frac{g}{2}
$$
The second term stands for lateral acceleration $a_L$:
$$
a_L=2\dot{r}\omega\leq \frac{g}{20}
$$
given the conditions $\dot{r}=2m/s$, we have:
$$
\left\{
\begin{align}
\nonumber r\omega^2 \geq g/2\\
\nonumber \omega \leq g/80\\
\end{align}
\right.
$$
$$
\left\{
\begin{align}
\nonumber r \geq g/(2\omega^2)\\
\nonumber \omega \leq g/80\\
\end{align}
\right.
$$
To get the minimum radius, we need to maximize $\omega$ because the radius is inversely proportional to $\omega^2$:
$$
r_{min}=\frac{g}{2\omega^2}=\frac{g}{2(\frac{g}{80})^2}=\frac{3200}{g}\approx 326m(i.e. 1070ft)
$$
![plot](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_4_and_2_6_Sol/output2.png?raw=true)

