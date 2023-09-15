## Problem 1

![image](https://github.com/leishi23/Lei_TA/blob/main/Screenshot%20from%202023-09-14%2019-45-47.png?raw=true)

### Solution


First, split the velocity and acceleration into x and y components:
$$ a_x = 0 \\
 a_y = -g = -32.2 \frac{ft}{s^2}\\
    v_{0x} = v_0 \cos \alpha \\
    v_{0y} = v_0 \sin \alpha $$

Then, we can work for the displacement in x and y directions:
For y direction:
$$ y = y_0 + v_{0y}t + \frac{1}{2}a_yt^2 \\
    y = 0 + v_0 \sin \alpha t - \frac{1}{2}gt^2 $$

For x direction:
$$ x = x_0 + v_{0x}t + \frac{1}{2}a_xt^2 \\
    x = 0 + v_0 \cos \alpha t + 0 $$

Then, what about the relationship between x and y? 
At point **B**, it should be:
$$ y(t) = -x(t)\tan \theta $$
that is:
$$ v_0 \sin \alpha t - \frac{1}{2}gt^2 = -v_0 \cos \alpha t \tan \theta $$
so, the time $t$ can be solved as:
$$ t = \frac{2v_0 \sin \alpha}{g(1+\tan^2 \theta)} \approx 6.6636 s $$

Then, we can plug the time $t$ into the equation of $x(t)$ to get the distance $x$:
$$ x = v_0 \cos \alpha t = 250 \cos 15 \times 6.6636 \approx 1609.1 ft $$


## Problem 2
![image](https://github.com/leishi23/Lei_TA/blob/main/Screenshot%20from%202023-09-14%2020-44-20.png?raw=true)

### Solution
Recall the chain rule:
$$ \frac{dy}{dx} = \frac{dy}{dt} \frac{dt}{dx} $$
So, we can get:
$$ a = \frac{dv}{dt} = \frac{dv}{ds} \frac{ds}{dt} = \frac{dv}{ds} v $$
Then, we can get:
$$ ads = vdv $$

Now, we can integrate both sides, but what about the bounds?
Recalling $v=0$ for $s=\frac{\lambda}{4}$, so we can integrate from $v=0$ to $v=v$ and from $s=\frac{\lambda}{4}$ to $s=s$:
$$ \int_{0}^{v} vdv = \int_{\frac{\lambda}{4}}^{s} ads \\
 \int_{0}^{v} vdv = \int_{\frac{\lambda}{4}}^{s} a_0\sin(2\pi s / \lambda)ds $$

which gives:
$$ \frac{1}{2}v^2 = -\frac{a_0\lambda}{2\pi} \cos(2\pi s / \lambda) \bigg|_{\frac{\lambda}{4}}^{s} \\
 v^2 = -\frac{a_0\lambda}{\pi} \cos(2\pi s / \lambda) - (-\frac{a_0\lambda}{\pi} \cos(\pi/2))\\
  v^2 = -\frac{a_0\lambda}{\pi} \cos(2\pi s / \lambda)$$

Since $v^2 \geq 0$, so we can get: **$ \cos(2\pi s / \lambda) \leq 0 $**
    
Then, we can get:
$$ \frac{1}{2}\pi + 2\pi n \leq 2\pi s / \lambda \leq \frac{3}{2}\pi + 2\pi n \\
 \frac{1}{4}\lambda + n \leq s \leq \frac{3}{4}\lambda + 3n,  n= \pm 1, \pm 2, \pm 3, ...$$

> **Note**: The sphere CAN NOT jump from one admissible range to the next. So, the sphere can only be in **_one_** range.

Observing that $a=a_0=8>0$ for $s=\frac{\lambda}{4}$, so the sphere is accelerating in the right direction. So, the sphere is in the range of $s \in [\frac{1}{4}\lambda, \frac{3}{4}\lambda]$.

So, the final result is: **$s \in [0.0625m, 0.1875m]$**


## Problem 3
![image](https://github.com/leishi23/Lei_TA/blob/main/Screenshot%20from%202023-09-14%2021-47-49.png?raw=true)

### Solution
![image](https://github.com/leishi23/Lei_TA/blob/main/Screenshot%20from%202023-09-14%2021-48-30.png?raw=true)

First, we can get the acceleration of the block:
$$ a = g\sin \theta \hat{i} - g\cos \theta \hat{j}\\
   a_x = g\sin \theta \\
    a_y = -g\cos \theta $$

Then, we can get:
$$ v_y^2 = v_{0y}^2 + 2a_y(y-y_0)$$

When jaguar A reaches the `h_{max}`, $v_y=0$, so we can get:
$$ 0=(v_0\sin \beta)^2 - 2g\cos \theta (h_{max}-h_0), h_0=0 $$
So, $h_{max} = \frac{(v_0\sin \beta)^2}{2g\cos \theta}$
