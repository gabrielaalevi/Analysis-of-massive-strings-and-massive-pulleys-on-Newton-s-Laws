## Ideal string on an ideal pulley}
We begin analysing the easiest case possible. A massive object $M_1$, with mass $m_1$, stands on a flat surface with kinetic friction coefficient $\mu_k$, and is tied to another massive 
object $M_2$, with mass $m_2$, that hangs outside of the surface. The objects are tied through a massless, frictionless and inextensible string, that passes through a massless and 
frictionless pulley. The whole system can be seen in the next figure:

![b2e5a81c9eb457725193b40c29ed88de17d5a440](https://github.com/user-attachments/assets/6fa2c87c-ba5f-4c07-abb5-e6ef59a984be)


Since the rope is massless, we can consider the tension to be equal on all of its points. This can be proved by analysing the forces on a infinitesimal length of the string.

Consider a transversal section of the string:

![263ae41a2c305340ed6acd327be89e3526c191de](https://github.com/user-attachments/assets/f1ede7a0-8fbb-4f82-874e-b0529212fa21)

If we apply a force on one of the string's extremities, this infinitesimal length of string will feel a tension $\Vec{T}_1$ acting in one of it's sides. 
However, due to the internal forces that keep the string together, this element of length will feel a force that resists the movement of the string, causing a force $\Vec{T}_2$
on the opposite direction of $\Vec{T}_1$.

That means that the resultant force is:

$$\Vec{F}_R = \Vec{T}_1 - \Vec{T}_2$$

Then, using Newton's Second Law:

$$\Vec{F}_R = m \Vec{a}$$

But, for a massless string, $m = 0$. Therefore:

$$\Vec{F}_R = \Vec{T}_1 - \Vec{T}_2 = 0$$

$$\rightarrow |\Vec{T}_1| = |\Vec{T}_2|$$

Further discussions about this theme can be found in [Newburgh (1997)](https://iopscience.iop.org/article/10.1088/0031-9120/32/3/020).

For the following work in this case, we will call $\Vec{T}_1 = \Vec{T}_2 = \Vec{T}$ for simplicity.
Considering a massless and frictionless pulley means that the string will slip over it, without causing rotation. 

Analysing the diagram in Fig. \ref{fig:diagrama sistema}, we can write expressions for the total forces acting on both objects.
On object 1, there is no movement on the vertical axis caused by its gravitational force or by the normal force caused by the surface. Therefore, we can conclude that these forces cancel each other:

$$|\Vec{G}_1| = |\Vec{N}_1| \label{eq: g1 equal n1}$$

On the horizontal plane, for object 1, we have only friction force $\Vec{F}_{FR}$, and the tension $\Vec{T}$ acting. On the diagram, we assumed that object 1 is moving to the left. Because of that, friction force points to the right. In this scenario, because the object is moving, we have $|\Vec{T}| > |\Vec{F}_{FR}|$ (otherwise, if this was not true, the object would be stationary). The resultant force on this body is then:

$$\Vec{F}_1 = \Vec{T} - \Vec{F}_{FR}$$

For the second object, we assume that $|\Vec{G}_2| > |\Vec{T}|$, for the movement to occur. Therefore:

$$\Vec{F}_2 = \Vec{G}_2 - \Vec{T}$$

Applying Newton's Second Law to both objects:

$$\Vec{F}_1 = \Vec{T} - \Vec{F}_{FR} = m_1 \Vec{a}_1$$
$$\Vec{F}_2 = \Vec{G}_2 - \Vec{T} = m_2 \Vec{a}_2$$

Here, it is useful to note that, because the string is inextensible, it is mandatory that $|\Vec{a_1}| = |\Vec{a_2}|$. The reason behind this statement comes from the fact that, because the string has always the same size and is never hanging loosely, the blocks should have the same displacement, when compared with their initial positions. Knowing that both movements happen in the same time interval, we can conclude that they have to have the same acceleration for it to be possible. Then, using $|\Vec{a}_1| = |\Vec{a}_2| = |\Vec{a}|$, we obtain:

$$\Vec{F}_1 = \Vec{T} - \Vec{F}_{FR} = m_1 \Vec{a}$$
$$\Vec{F}_2 = \Vec{G}_2 - \Vec{T} = m_2 \Vec{a}$$

Adding these equations:

$$\Vec{G}_2 - \Vec{F}_{FR} = (m_1 + m_2) \Vec{a}$$

Which means that:

$$\Vec{a} = \frac{\Vec{G}_2 - \Vec{F}_{FR}}{(m_1 + m_2)}$$

Hence, using:

$$\Vec{G}_2 = m_2 \Vec{g}$$

$$\Vec{F}_{FR} = \Vec{N}_1 \mu_k$$

And, as we already saw in Eq. \ref{eq: g1 equal n1}, for object 1 $\Vec{N}_1 = \Vec{G}_1 = m_1 \Vec{g}$:

$$\Vec{F}_{FR} = m_1 \Vec{g} \mu_k$$

We finally see that:

$$\Vec{a} = \frac{\Vec{g} (m_2 - m_1 \mu_k)}{(m_1 + m_2)}$$

All of these values are constant in time, which means that the system acceleration is constant, and therefore the force acting on both objects in also constant.

## Ideal string on a massive pulley

We can increase the difficulty of our work by trying to take into consideration the mass and rotational movement of the pulley. In this case, we do not consider this body to be frictionless anymore. So, when the string moves on the pulley, it creates a friction force between both agents. This force is responsible for creating the torque that will make the pulley to rotate.

While we are considering a massless string for this analysis, we can't assume the tension to be the same on all points of the string, due to the friction force between the string and the pulley. Because of this, we consider $|\Vec{T}_1| \neq |\Vec{T}_2|$.

We can write the torque the pulley suffers using Newton's Second Law for rotations:

$$\Vec{\tau} = I_{CM} \Vec{\alpha}$$

with $I_{CM}$ being the moment of inertia of the pulley about the center of mass, and $\Vec{\alpha}$ the angular acceleration of the pulley.
For both objects, using the Newton's Second Law:

$$\Vec{F_1} = m_1 \Vec{a_1}$$
$$\Vec{F_2} = m_2 \Vec{a_2}$$

Since the string is inextensible, |$\Vec{a}_1| = |\Vec{a}_2| = |\Vec{a}|$, as discussed in Sec. \ref{sec:ideal-string-ideal-pulley}. Accordingly:

$$\Vec{F_1} = m_1 \Vec{a}$$
$$\Vec{F_2} = m_2 \Vec{a} \label{eq: objects motion}$$

As we saw previously, an analysis of Fig. \ref{fig:diagrama sistema} allows us to write:

$$\Vec{T}_1 - \Vec{F}_{FR} = m_1 \Vec{a}$$

$$\Vec{G}_2 - \Vec{T}_2 = m_2 \Vec{a}$$

Then, we need to make a deep analysis of the forces the pulley is under. Taking a look at:

![af028c16db62627e4a021d01ef01a1f221ab6263](https://github.com/user-attachments/assets/b1ce7952-e5f5-4e5e-8c40-aff317ef3ae4)

We can see that $\Vec{T}_1$ generates a torque that points inside the page, and $\Vec{T}_2$ generates a torque that points outside the page.

The rotational motion of the pulley is caused by the difference $|\Vec{T}_1| - |\Vec{T}_2|$. Choosing the direction that points into the page as the positive direction of motion, we can write:

$$\Vec{T}_2 R - \Vec{T}_1 R = I_{CM} \Vec{\alpha}$$

We know that $\Vec{\alpha}$ depends on the objects' acceleration $\Vec{a}$, so that:

$$\Vec{a} = R \Vec{\alpha}$$

$$\Vec{T}_2 R - \Vec{T}_1 R = I_{CM} \frac{\Vec{a}}{R} \label{pulley motion}$$

Using Eq. \ref{eq: objects motion}, we can rewrite the tensions on the string as:

$$\Vec{T}_1 = m_1 \Vec{a} + \Vec{F}_{FR}$$
$$\Vec{T}_2 = \Vec{G}_2 - m_2 \Vec{a}$$

Then, substituting that in Eq. \ref{pulley motion}, we obtain:

$$(\Vec{G}_2 - m_2 \Vec{a})R - (m_1 \Vec{a} - \Vec{F}_{FR})R = I_{CM} \frac{\Vec{a}}{R}$$

$$\Vec{G}_2 R - \Vec{F}_{FR} R = \Vec{a} \left(\frac{I_{CM}}{R} + m_1 R + m_2 R \right)$$

$$\Vec{a} = \frac{\Vec{G}_2 R - \Vec{F}_{FR} R}{\left(\frac{I_{CM}}{R} + m_1 R + m_2 R \right)}$$

Hence, using that:

$$\Vec{G}_2 = m_2 \Vec{g}$$
$$\Vec{F}_{FR} = m_1 \Vec{g} \mu_k$$

we arrive at:
    
$$\Vec{a} = \frac{\Vec{g} R (m_2 - m_1 \mu_k)}{\left(\frac{I_{CM}}{R} + m_1 R + m_2 R \right)}$$


All of these parameters are constant in our system, which means that the acceleration in the system is constant throughout the movement.

##Massive string on an ideal pulley

Taking in consideration a massive string is a slight trickier case. We consider the string to be massive, but still inextensible. The pulley is massless and frictionless, and the string slips on the pulley, so that there is no rotational movement being caused in the pulley.
For this analysis, we need to use Newton's Second Law as:

$$\Vec{F}_1 = \frac{d \Vec{p}}{dt}$$

Calling the length of rope that is hanging from the surface as $l(x)$, and the total length of he rope $L$, we obtain, for the first object:

$$\Vec{p} = m \Vec{v} = [m_1 + (L - l(x)) \lambda] \Vec{v}$$

where $\lambda$ represents the string's linear mass density.
Hence:

$$\Vec{F}_1 = \frac{d \Vec{p}}{dt} = m \frac{d \Vec{v}}{dt} + \Vec{v} \frac{d m}{dt}$$

$$\Vec{F}_1 = [m_1 + (L -l(x)) \lambda] \Vec{a} + \lambda \frac{d l(x)}{dt} \Vec{v}$$

we can use chain rule for derivatives to write:

$$\frac{d l(x)}{dt} = \frac{d l(x)}{dx} \frac{d x}{dt} = \frac{d l(x)}{dx} v$$

$$\Vec{F}_1 = [m_1 + (L -l(x)) \lambda] \Vec{a} - \lambda \frac{d l(x)}{dx} v^2 \,,\label{f1}$$

where we are already using our constraint $|\Vec{a}_1| = |\Vec{a}_2| = |\Vec{a}|$, that, as we saw, comes from the fact that the string is inextensible.
Then, for object 2:

$$\Vec{p} = m \Vec{v} = [m_2 + \lambda l(x)] \Vec{v}$$

$$\Vec{F}_2 = [m_2 + \lambda l(x)] \Vec{a} + \lambda \frac{d l(x)}{dx} v^2 \,,\label{f2}$$

Analysing the diagram for the system, presented in Fig. \ref{fig:diagrama sistema}, we conclude that:

$$\Vec{T}_1 - \Vec{F}_{FR} = \Vec{F}_1$$
$$\Vec{G}_2 - \Vec{T}_2 = \Vec{F}_2 \,,\label{motion massive string ideal pulley}$$

where we have assumed that the system is moving, and object $M2$ is descending, pulling object $M1$ to the left.
Then, we need to take a closer look at what happens where the string connects to object 1. The string applies a force on object 1, that we will call $\Vec{F}_{S,1}$. 
According to Newton's Third Law, we expect the object to apply an equivalent force, but with contrary direction, on the string, which we will call $\Vec{F}_{1,S}$. 
Both forces can be seen in:

![c674ee9762920d94a555ec4d78960e7661aee707](https://github.com/user-attachments/assets/e6033daa-cac2-407f-8b72-80a5c599d12a)


We can see that the force $\Vec{F}_{S,1}$ is what the call $\Vec{T}_1$. So, through Newton's Third Law:

$$\Vec{T}_1 = -\Vec{F}_{1,S}$$

The tension on the string depends on how much mass each infinitesimal length of string needs to hold. At the point where the string connects to object 2, the tension is smaller, and is proportional to $m_2$. As we move further up from this point, the tension increases, as the infinitesimal part $dx$ needs to hold $m_2$ and the mass of the string that is hanging under it.

Applying Newton's Second Law to the string hanging between object 1 and the pulley:

$$\Vec{T}(\text{x=pulley}) - \Vec{F}_{1,S} = \lambda [L-l(x)] \Vec{a}$$

But, as we saw, $\Vec{F}_{1,S} = -\Vec{T}_1$. Then, using Eq. \ref{motion massive string ideal pulley}:

$$\rightarrow \Vec{T}(\text{x=pulley}) = \lambda [L-l(x)] \Vec{a} - \Vec{F}_1 - \Vec{F}_{FR}$$

$$\rightarrow \Vec{T}(\text{x=pulley}) = \lambda [L-l(x)] \Vec{a} - [m_1 +(L-l(x))\lambda] \Vec{a} + \lambda \frac{d l(x)}{dx} v^2 - \Vec{F}_{FR}$$

Doing the same procedure for the string hanging between object 2 and the pulley, we can identify that $\Vec{F}_{2,S} = -\Vec{T}_2$, so that:

$$\Vec{F}_{2,S} - \Vec{T}(\text{x=pulley}) = l(x) \lambda \Vec{a}$$

$$\rightarrow -\Vec{T}_2 - \Vec{T}(\text{x=pulley}) = l(x) \lambda \Vec{a}$$

$$\rightarrow \Vec{T}(\text{x=pulley}) = - \lambda l(x) \Vec{a} -\Vec{G}_2 + \Vec{F}_2 $$

$$\rightarrow \Vec{T}(\text{x=pulley}) = -l(x) \lambda \Vec{a} - \Vec{G}_2 + [m_2 - \lambda l(x)] \Vec{a} + \lambda \frac{d l(x)}{dx} v^2$$

That way, when we equate both expressions for $\Vec{T}(\text{x=pulley})$, as they were calculated on the same point:

$$\lambda [L-l(x)] \Vec{a} -[m_1 +(L-l(x))\lambda] \Vec{a} + \lambda \frac{d l(x)}{dx} v^2 - \\\Vec{F}_{FR} = -l(x) \lambda \Vec{a} - \Vec{G}_2 + [m_2 - \lambda l(x)] \Vec{a} + \lambda \frac{d l(x)}{dx} v^2$$

which we can rearrange as:

$$[m_1 + m_2 + L \lambda] \Vec{a} + \Vec{F}_{FR} - \Vec{G}_2 = 0$$

which is a second-order linear ODE.

At first glance, it may seem that the acceleration will be constant throughout the movement. However, we can see that $\Vec{G}_2$ changes with time, as the length of the string that is hanging from the surface increases:

$$\Vec{G}_2 = [m_2 + l(x) \lambda] \Vec{g} \label{gravitational force with time}$$

Considering the string to be inextensible implies that, when object 1 has a displacement of $x$, $l(x)$ will increase with $x$. If at $t = 0$ we have $l(x = 0) = l_0$, then:

$$l(x) = l_0 + x \label{l with x}$$

So, rewriting the final equation gives us:

$$\left[m_1 + m_2 + L \lambda \right] \frac{d^2 x}{d t^2} - g \lambda x +g (\mu_k m_1 - [m_2 + l_0 \lambda]) = 0$$

where we have used that, for object 1, the normal force $\Vec{N}$ is equal to the gravitational force $\Vec{G}_1$, as we previously saw in Eq. \ref{eq: g1 equal n1}.

Therefore, as the gravitational force $\Vec{G}_2$ changes with time, we can conclude that the acceleration (and consequently, the force felt by both objects and the string) is variable during the movement of the system. The resulting acceleration of the system depends on the displacement that have already occurred; hence, it is necessary to solve the 2º degree ODE to successfully describe the system.

## Massive string on a massive pulley

For the last case, we abandon almost all of our approximations. The only restraints we will maintain are that the string is still inextensible and that the string does not slip in the pulley.

In this system, the forces acting on objects 1 and 2 are the same as in the last subsection, so that we can use Eq. \ref{f1}, Eq. \ref{f2} and Eq. \ref{motion massive string ideal pulley} for this occasion.
What will be different is that we now have torque rotating the pulley, hence:

$$\Vec{\tau} = I_{CM} \Vec{\alpha}$$

And, as we've analysed with Fig. \ref{fig:pulley}, the torque is equal to:

$$\Vec{\tau} = \Vec{T}_2 R - \Vec{T}_1 R$$

Then, using our expressions for $\Vec{F}_1$, $\Vec{F}_2$, $\Vec{T}_1$, $\Vec{T}_2$ and $\Vec{\tau}$, we obtain:

$$[m_1 + (L - l(x))\lambda] \Vec{a} - \lambda \frac{d l(x)}{dx} v^2 + [m_2 + l(x) \lambda] \Vec{a} \\+ \lambda \frac{d l(x)}{dx} \Vec{v}^2 + \Vec{F}_{FR} - \Vec{G}_2 = \frac{I_{CM}}{R^2} \Vec{a} $

which can be rearranged as:

$$\left[m_1 + m_2 + L \lambda + \frac{I_{CM}}{R^2} \right] \Vec{a} + \Vec{F}_{FR} - \Vec{G}_2 = 0$$


Once more, we need to note that $\Vec{G}_2$ is not constant with time. As we saw in Eq. \ref{gravitational force with time}, it increases as object 1 moves, and there is more string hanging from the surface.

Hence, using the Eq. \ref{l with x} to substitute $l(x)$, we get that the final expression for this system is:

$$\left[m_1 + m_2 + L \lambda + \frac{I_{CM}}{R^2}\right] \frac{d^2 x}{d t^2} - g \lambda x + g (\mu_k m_1 - [m_2 + l_0 \lambda]) = 0$$
