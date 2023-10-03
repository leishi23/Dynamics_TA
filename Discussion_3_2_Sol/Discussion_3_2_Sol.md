# Problem 1
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_2_Sol/Screenshot%202023-10-03%20135250.png?raw=true" alt="Image Description">
</div>

---

## Recall 
- Curvilinear motion
    - $a_r = \ddot{R} - R\dot{\theta}^2$, direction is outward the center of curvature
    - $a_{\theta} = R\ddot{\theta} + 2\dot{R}\dot{\theta}$, direction is perpendicular to the radial direction
- Friction: $F_f \leq \mu F_N$, where $F_N$ is the normal force

## Analysis

- The rod and the collar is in rotation. The faster they rotate, the further the collar is away from the center of rotation. The question is about `the range of speed`, i.e. the **maximum** speed when the collar is going up and the **minimum** speed when the collar is going down.
- $\sum F_{\theta} = 0$, due to constant angular velocity
- $\sum F_{Z} = ma_Z$, where $a_Z=0$ because the question is about collar will not slide along the rod.
- $\sum F_{r} = a_r$,  

- Draw FBD
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_2_Sol/%E5%9B%BE%E7%89%87_20231003141546.jpg?raw=true" alt="Image Description" width="500"
  >
</div>

> Note: the normal force is perpendicular to the surface, and the friction force is parallel to the surface which is either up or down. 
> When the object tends to slide down but is not sliding, the friction force is up. When the object tends to slide up but is not sliding, the friction force is down.

--- 
## Solution

- $\sum F_{Z} = ma_Z$:
For first case, the friction is up:
$$
F_f \cos \alpha + N \sin \alpha - mg = ma_Z = 0
$$
For second case, the friction is down:
$$
-F_f \cos \alpha + N \sin \alpha - mg = ma_Z = 0
$$
So, $F_f = \pm \mu N$, $N = \frac{mg}{\sin \alpha \pm \mu \cos \alpha}$, where $+$ is for the first case and $-$ is for the second case.

<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_2_Sol/%E5%9B%BE%E7%89%87_20231003141546.jpg?raw=true" alt="Image Description" width="400"/>
</div>

- $\sum F_{r} = a_r$:
$$
F_f \sin \alpha - N \cos \alpha = ma_r  \\
\pm \mu N \sin \alpha - N \cos \alpha = ma_r \\
a_r = \frac{N}{m}( \pm \mu \sin \alpha - \cos \alpha) \\
a_r = \frac{1}{m} \frac{mg}{\sin \alpha \pm \mu \cos \alpha} ( \pm \mu \sin \alpha - \cos \alpha) = \frac{g}{\sin \alpha \pm \mu \cos \alpha} ( \pm \mu \sin \alpha - \cos \alpha)
$$

Since the collar is not sliding, no change in radius i.e. $\ddot{r} = 0$, so $a_r = \ddot{r} - r \dot{\theta}^2 = -r \dot{\theta}^2$. And $\dot{\theta} = \sqrt{-\frac{a_r}{r}}$

Plug in the expression of $a_r$:
$$
\dot{\theta} = \sqrt{-\frac{g}{r} \frac{\pm \mu \sin \alpha - \cos \alpha}{\sin \alpha \pm \mu \cos \alpha} }
$$

Plug the value of $r$ and $\alpha$: $\dot{\theta} = 3.09$ or $\dot{\theta} = 6.52 rad/s$

$$
\vec{v} = \dot{r} \hat{u_r} + r \dot{\theta} \hat{u_{\theta}}\\
\vec{v} = 0 \hat{u_r} + r \dot{\theta} \hat{u_{\theta}}\\
\vec{v}_{min} = 6.18 \hat{u_{\theta}} ft/s\\
\vec{v}_{max} = 13.04 \hat{u_{\theta}} ft/s
$$
<div STYLE="page-break-after: always;"></div>

# Problem 2
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_2_Sol/Screenshot%202023-10-03%20152942.png?raw=true" alt="Image Description">
</div>

---

## Recall and Analysis
<div style="text-align:center">
  <img src="https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_3_2_Sol/Screenshot%202023-10-03%20153154.png?raw=true" alt="Image Description" width="700"/>   
</div>

- $a_r = \ddot{R} - R\dot{\theta}^2$, direction is outward the center of curvature
- $a_{\theta} = R\ddot{\theta} + 2\dot{R}\dot{\theta}$, direction is perpendicular to the radial direction

---

## Solution
- Transverse direction: $\sum F_{\theta} = ma_{\theta}=m(R\ddot{\theta} + 2\dot{R}\dot{\theta})$
- Radial direction: $\sum F_{r} = ma_r = m(\ddot{R} - R\dot{\theta}^2)$

For radical direction, since $T$ is inwards and $a_r$ is outward, so:
$$
\begin{aligned}\nonumber
-T = ma_r \\
T = -ma_r \\
T = m(R\dot{\theta}^2 - \ddot{R})
\end{aligned}
$$
where, $R = l - w_s b t$ and $\dot{R} = -w_s b $, $\ddot{R} = 0$; also $\dot{\theta} = w_b$ 
So, $T = m(l-w_s b t) w_b^2$

For transverse direction:
$$
F_{\theta} = ma_{\theta} \\
F_{\theta} = m(R\ddot{\theta} + 2\dot{R}\dot{\theta}) \\
$$
where, $R = l - w_s b t$ and $\dot{R} = -w_s b $, $\ddot{R} = 0$; also $\dot{\theta} = w_b$, $\ddot{\theta} = 0$
So, $F_{\theta} = -2m w_s b w_b$, if $w_s$ is positive, then it moves inward, otherwise it moves outward.
