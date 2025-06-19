
Consider N molecules in a gas of volume V. Ignore all interactions between particles. The molecules are spheres which will allow collisions to occur. 

We start with the Maxwell-Boltzmann probability distribution for the velocities in a gas

<p style="text-transform: uppercase; font-size: 0.8em; font-weight: bold; margin-bottom: 0;text-align: center;"> Maxwell-Boltzmann Distribution</p>

$$
 f(\mathbf{v})d^3v = \left(\frac{m}{2\pi k_{b}T}\right)^{3/2}\exp\left( -\frac{1}{2} mv^2 /k_{b}T\right) d^3v
$$
which is three dimensional counterpart of the [[1.3.1 Maxwellian Distribution|one-dimensional Maxwellian distribution]]. Again the interpretation is that $f(\mathbf{v})d^3v$ is the probability that a molecule has velocity within a small volume $d^3v$ in the neighbourhood of $\mathbf{v}$ (between $\mathbf{v}$ and $\mathbf{v}+d\mathbf{v}$). 

Denote the diameter of the particle as $d$ (radius $\frac{d}{2}$). Viewed head-on, the particle appears as a disc with area $\pi (d /2)^2$. We define the *effective cross-sectional area of the particle* $\pi d^2$. Particle A will collide with a particle B if the distance from the centre of A to the centre of B is less than the sum of their radii. So the 'effective' cross-sectional area is that of a circle of radius $r_{a} + r_{b}$. In our system all particles have the same radius so the effective cross sectional area is $\pi d^2$. 

If the particle travels through the gas a distance $l$, the volumes swept out is $\pi d^2 l$. It will collide with any other particle whose centre lies within this volume. 

The *mean free path* $\lambda$ is the average distance travelled by the molecule between each collision. Imagine a particle that undergoes a large number $N$ of collisions. The total length the particle will travel is $L = N\lambda$, since the average distance between collisions is $\lambda$.  The total volume swept out will be $V =\pi d^2 L =\pi d^2 N \lambda$. Assume now that the number density inside the swept-out volume is the same as the number density of the whole gas, so $n = \frac{N}{V}$.  Then
$$
 n = \frac{N}{V} = \frac{N}{\pi d^2 N \lambda} = \frac{1}{\pi d^2 \lambda}
$$
The mean free path is then 
<p style="text-transform: uppercase; font-size: 0.8em; font-weight: bold; margin-bottom: 0;text-align: center;"> Mean Free Path</p>

$$
\lambda = \frac{1}{n \pi d^2} 
$$
The mean free path goes down as the number density goes up, as expected. We have also assumed that the number of collisions is the number of particles inside the volume.    