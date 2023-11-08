## Problem 1

![image-20231107195436910](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_6_1_Sol/Prob1.png?raw=true)

### Recall

​	We first review the cross product of vectors.
$$
\vec{a} \times \vec{b} = 
\left|
\begin{matrix}
i & j & k\\
a_x & a_y & a_z\\
b_x & b_y & b_z\\
\end{matrix}
\right|=
(a_yb_z-a_zb_y)\hat{i}+
(a_zb_x-a_xb_z)\hat{j}+
(a_xb_y-a_yb_x)\hat{k}
$$
​	Where $\hat{i},\hat{j},\hat{k}$ are unit vectors of positive $x,y,z$ direction. And by definition, we knows that: $\vec{a} \times \vec{b}=-\vec{b} \times \vec{a}$, and $\vec{a} \times \vec{a}=\vec{0}$.

​	Specifically, we have: 
$$
\vec{i}\times\vec{j}=\vec{k}\\
\vec{j}\times\vec{k}=\vec{i}\\
\vec{k}\times\vec{i}=\vec{j}\\
$$
​	For rigid body rotating to a fixed axis at A, for any point B on the object, we have:
$$
\vec{v}_{B/A} = \vec\omega_{AB}\times \vec R_{B/A}
$$

<div style="page-break-after: always;"></div>


### Solution

​	For this problem, we first find $\vec{r}$ and $\vec{\omega}$ for the fixed rotation
$$
\vec{r}_{A/O}=R(sin\varPhi\cdot \hat{i} + cos\varPhi\cdot \hat{j})\\
\vec{r}_{B/O}=-R/2\cdot \hat{i}
$$
  We can find $\omega$ using given velocity of A and radius. Since: $v_A=|\omega| R$, z axis is pointing outwards of the plane, and the turbine is rotating clockwise (angular vector pointing inwards), we have
$$
\vec \omega = -v_A/R\cdot \hat{k}
$$
 therefore,  
$$
\begin{align}
\vec v_B&= \vec \omega \times \vec R\\
&=-v_A/R\cdot \hat{k}\times (-\frac{R}{2}\cdot \hat{i})\\
&=\frac{v_A}{2}\hat j\\
&=146\hat j\ ft/s
\end{align}
$$

<!-- page segamentation -->
<div style="page-break-after: always;"></div>

## Problem 2
![image-20231107195436910](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_6_1_Sol/Screenshot%202023-11-07%20223331.png?raw=true)

### Recall
- Rotation of a Rigid Body About a Fixed Axis：
![image-20231107195436910](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_6_1_Sol/Screenshot%202023-11-07%20230329.png?raw=true)
- For this problem, we regard the rotation around the A axis as the fixed axis rotation. And the rotation positive direction is counter-clockwise.
  - For example:
    $$
    \vec{v}_{B/A} = \vec\omega_{AB}\times \vec r_{B/A} \\
    v_0\hat{i} = \omega_{AB}\hat{k}\times l\hat{j} 
    $$
    where $\vec{v}_{B/A}$ is the velocity of point B relative to point A, $\vec\omega_{AB}$ is the angular velocity of the rigid body, and $\vec r_{B/A}$ is the position vector of point B relative to point A.

<div style="page-break-after: always;"></div>

### Solution
Since the bucket is in a fixed axis rotation about point A, we have:
$$ 
\vec{v}_{B} = \vec\omega_{AB}\times \vec r_{B/A} =  v_0\hat{i} \\
v_0\hat{i} = \omega_{AB}\hat{k}\times l\hat{j} \\
-\omega_{AB}l\hat{i} = v_0\hat{i} \\
\omega_{AB} = -\frac{v_0}{l} = -0.2778rad/s\\
$$
Plug in the value of $\omega_{AB}$, we have:
$$
\vec{v}_{C} = \omega_{AB}\hat{k}\times \vec r_{C/A} =  \omega_{AB}\hat{k}\times [w\hat{i}-(h-l)\hat{j}] \\
\vec{v}_{C} = (h-l)\omega_{AB}\hat{i}+w\omega_{AB}\hat{j} \\
\vec{v}_{C} = (-0.292\hat{i} - 0.736\hat{j}) ft/s \\
$$
Since $\alpha_{AB} = 0$, $\vec{a}_{C} = -\omega_{AB}^2\vec r_{C/A} = -v_0^2[w\hat{i}-(h-l)\hat{j}]$,which means that:
$\vec{a}_{C} = (-0.204\hat{i} + 0.081\hat{j}) ft/s^2$


<!-- page segamentation -->
<div style="page-break-after: always;"></div>

## Problem 3
![image-20231107195436910](https://github.com/leishi23/Dynamics_TA/blob/main/Discussion_6_1_Sol/Screenshot%202023-11-07%20223342.png?raw=true)

### Recall
We can define the length of the rope as:
$$
L = y_D + 2y_A
$$
Taking two time derivatives of this equation, and remembering that the overall length isconstant because the rope is inextensible, we have:
$$
\begin{align}
0 = \dot{y}_D + 2\dot{y}_A \rightarrow \dot{y}_D = -2\dot{y}_A = 2v_0 \\
0 = \ddot{y}_D + 2\ddot{y}_A \rightarrow \ddot{y}_D = -2\ddot{y}_A = 2a_0
\end{align}
$$

### Solution
Because the point Q is contacting the rope, and the rope is not slipping, point Q has thesame velocity and vertical component of acceleration as D.
$$
\begin{align}
\vec{v}_Q = \vec{v}_D = 2v_0 = \omega_{C}\frac{l}{2} \rightarrow \vec{\omega}_C = \frac{4v_0}{l} = 40.0\hat{k} rad/s \\
\vec{a}_{Qy} = \vec{a}_D = 2a_0 = \alpha_{C}\frac{l}{2} \rightarrow \vec{\alpha}_C = \frac{4a_0}{l} = 5.20\hat{k} rad/s^2
\end{align}
$$
