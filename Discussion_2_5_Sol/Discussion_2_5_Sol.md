#Problem 1
![Problem 1](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-42-53.png?raw=true)
> Notice: $y = -0.003x^2$, the $m^{-1}$ is just about the unit. 


## Recall on lecture slides
- A path described by Cartesian Coordinates, $y = y(x)$, has the radius of curvature:
$$\rho = \frac{(1 + \frac{dy}{dx}^2)^{3/2}}{\vert\frac{d^2y}{dx^2}\vert}$$
- The acceleration of a rotation object is:
$$ \vec{a} = \dot{v}\hat{u_t} + \frac{v^2}{\rho}\hat{u_n}$$
- At the top of the hill, the tangent to the path is horizontal, so the normal direction coincides with the gravity direction.
- The question "loss contact of the ground" means the normal force equals to gravity, i.e. $a_n = g = \frac{v^2}{\rho}$. Because gravity has two functions: to provide the normal force and to pull the object down. If gravity doesn't pull object down, it means *all* gravity is for normal force.

![Acceleration](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-58-02.png?raw=true)

##Solution:
$a_n = g = \frac{v^2}{\rho}$ means $\frac{v^2}{\rho} = g$.

The question is about the minimum velocity, so:$\frac{v_{min}^2}{\rho \vert_{x=0}} = g \rArr v_{min} = \sqrt{g\rho \vert_{x=0}}$

For $y = -0.003x^2$, we have:
$$\frac{dy}{dx} = -0.006x\\ 
\frac{d^2y}{dx^2} = -0.006$$
So, for $x=0$, $\frac{dy}{dx}\vert_{x=0} = 0$ and $\frac{d^2y}{dx^2}\vert_{x=0} = -0.006$.
So, $\rho \vert_{x=0} = \frac{(1 + (\frac{dy}{dx}\vert_{x=0})^2)^{3/2}}{\vert\frac{d^2y}{dx^2}\vert_{x=0}\vert} = \frac{(1 + 0^2)^{3/2}}{\vert-0.006\vert} = \frac{1}{0.006} = 166.67 m$.
And $v_{min} = \sqrt{g\rho \vert_{x=0}} = \sqrt{9.8 \times 166.67} = 42.4 m/s = 145.6 km/h$.



#Problem 2
![Problem 2](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_2_5_Sol/Screenshot%20from%202023-09-21%2021-43-14.png?raw=true)

