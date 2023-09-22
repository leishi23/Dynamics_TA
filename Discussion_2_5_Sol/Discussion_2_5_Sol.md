# Problem 1
![Problem 1](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-42-53.png?raw=true)
> Notice: $y = -0.003x^2$, the unit $m^{-1}$ in the monomial is to align the dimensions of $x$ and $y$

## Recall and Analysis:

- A path described by Cartesian Coordinates, $y = y(x)$, has the radius of curvature:
  $$
  \rho = \frac{(1 + \frac{dy}{dx}^2)^{3/2}}{\vert\frac{d^2y}{dx^2}\vert}​
  $$
  The acceleration in N-T coordinate is:
  $$
   \vec{a} = \dot{v}\hat{u_t} + \frac{v^2}{\rho}\hat{u_n}
  $$
- At the top of the hill, the tangent to the path is horizontal, so the normal direction coincides with the gravity direction.

- The question "loss contact of the ground" means the normal force equals to gravity, i.e. $a_n = g = \frac{v^2}{\rho}$. Because gravity has two functions: to provide the normal force and to pull the object down. If gravity doesn't pull object down, it means *all* gravity is for normal force.

<img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-58-02.png?raw=true" alt="Acceleration" style="zoom:67%;" />









## Solution:

​	The condition "the car lose contact at top of the hill"  indicates that the ground contact force to the car is zero, which means at the minimum speed which meets the condition:
$$
a_n = g = \frac{v^2}{\rho}
$$
The question is about the minimum velocity, so:$\frac{v_{min}^2}{\rho \vert_{x=0}} = g \rArr v_{min} = \sqrt{g\rho \vert_{x=0}}$

For $y = -0.003x^2$, we have:
$$
\left\{
\begin{align}
\frac{dy}{dx} = -0.006x\\ 
\frac{d^2y}{dx^2} = -0.006
\end{align}
\right.
$$

Therefore, for $x=0$, $\frac{dy}{dx}\vert_{x=0} = 0$ and $\frac{d^2y}{dx^2}\vert_{x=0} = -0.006$.

By plugging these values to our equation, we have: 

$$
\rho \vert_{x=0} = \frac{(1 + (\frac{dy}{dx}\vert_{x=0})^2)^{3/2}}{\vert\frac{d^2y}{dx^2}\vert_{x=0}\vert} = \frac{(1 + 0^2)^{3/2}}{\vert-0.006\vert} = \frac{1}{0.006} = 166.67 m
$$

And $v_{min} = \sqrt{g\rho \vert_{x=0}} = \sqrt{9.8 \times 166.67} = 42.4 m/s = 145.6 km/h$.































# Problem 2

![Problem 2](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-43-14.png?raw=true)

## Recall and Analysis:

- The acceleration in N-T is:
$$ \vec{a} = \dot{v}\hat{u_t} + \frac{v^2}{\rho}\hat{u_n}$$
- "constant speed" means $\dot{v} = 0$ and $v = v_0$.
- Given conditions: $r,\theta,v_0,L_0$





## Solution:

**1.**
	$\rho = L_0 - r\theta$. So, $\vec{a} = \frac{v_0^2}{L_0 - r\theta}\hat{u_n}$.

**2.**
	Because $\dot{v} = 0$, there is no tangential acceleration, i.e. $\hat{u_t}$ part.

​	Therefore, we only have the normal acceleration, i.e. $\hat{u_n}$ part. To convert the $\hat{u_t}$ in N-T coordinate into $\hat{i}, \hat{j}$ in Cartesian coordinate, we just need to find the components in Cartesian Coordinates, by observing the direction of the rope, we have:
$$
\hat{u_n} = \sin\theta\hat{i} - \cos\theta\hat{j}
$$
​	Then we can derive the acceleration $\vec{a}$:
$$
\vec{a} = \frac{v_0^2}{L_0 - r\theta}\hat{u_n} = \frac{v_0^2}{L_0 - r\theta}(\sin\theta\hat{i} - \cos\theta\hat{j})​
$$
​	To check if the answer is correct, we can calculate the magnitude of the acceleration:
$$
\vert\vec{a}\vert = \frac{v_0^2}{L_0 - r\theta}\sqrt{\sin^2\theta + \cos^2\theta} = \frac{v_0^2}{L_0 - r\theta}
$$
​	Which equals to the answer we derive in 1.

