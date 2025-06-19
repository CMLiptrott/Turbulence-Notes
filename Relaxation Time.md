The average time between collisions is the **scattering time** or **relaxation time**,
$$
\tau=\frac{\lambda}{\langle v_{\text{rel}}\rangle}
$$
Here $\langle v_{\text{rel}}\rangle$ is *not* the average speed of a given particle. We're interested in the rate of collisions, so the speed of other particles approaching is just as important as the speed of the particle you're looking at.  We should take $v_{\text{rel}}$ to be the **relative speed** of the particles. The average relative speed of $\mathbf{v}$ and $\mathbf{v}'$ is
$$
v_{\text{rel}}^2 =  \langle (\mathbf{v}-\mathbf{v}')^2 \rangle = \int d^3\mathbf{v}\int d^3\mathbf{v}' (\mathbf{v}-\mathbf{v}')^2 f(\mathbf{v})f(\mathbf{v}') = \langle v^2\rangle +\langle v'^2\rangle -2\langle \mathbf{v}\cdot \mathbf{v}'\rangle 
$$
where $f(\mathbf{v})$ is the [[Collisions|Maxwell-Boltzmann distribution]]. 