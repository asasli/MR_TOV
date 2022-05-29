# Application in General Relativity: M-R solving TOV equations for spherical stars 

**The Tolman-Oppenheimer-Volkoff system** in units $c=G=1$ is
$$ P = P(\epsilon),$$


$$ \frac{dP}{dr} = -\frac{(\epsilon+P)(m+4\pi r^3P)}{r(r-2m)},$$


$$ \frac{dm}{dr} = 4\pi r^2 \epsilon$$

m reminds us the Newtonian mass.

$$ \frac{d\nu}{dr} = -\frac{2}{\epsilon+P}\frac{dP}{dr}=\frac{2(m+4\pi r^3P)}{r(r-2m)},$$

which looks like the expression for the Newtonian potential with some additional terms that look like corrections to the gravitational mass and the radial distance. In fact at the weak field limit, the Newtonian potential is $\Phi=\nu/2$. 


$$ \lambda = -\ln\left(1-\frac{2m}{r}\right),$$
 

### Initial Condintions
We now have the full system of equations, which we can close with the choice of an EoS $ P = P(\epsilon)$. The system is supplemented by a set of initial conditions at the center of the star,

$$ P(0) = P_c,$$
or
$$ \epsilon(0) = \epsilon_c,$$
$$ m(0) = 0,$$
$$ \nu(0) = -1.$$

where the last choice is arbitrary (after the interior solution is obtained, $\nu$ will be shifted to match the Schwarzschild exterior solution at the surface).

Near the center, a series expansion gives for the behaviour of the various quantities,

$$P(r) \simeq P_c -(2\pi)(\epsilon_c+P_c) \left( P_c+\frac{1}{3}\epsilon_c \right) r^2 + O(r^4),$$
$$ m(r) \simeq \frac{4}{3}\pi\epsilon_c r^3 + O(r^4),$$
$$ \nu(r) \simeq \nu_c + 4\pi \left(P_c+ \frac{1}{3}\epsilon_c \right)r^2 + O(r^4).$$

On the other hand, the value of $\nu$ at the surface is 

$$ \nu_\star = -\lambda_\star = \ln\left(1-\frac{2M}{R}\right).$$

Furthermore, the gravitational mass can be obtained as 

$$ M = \int_0^R 4\pi r^2\epsilon dr,$$
or as
$$ M = \int_0^R 4\pi r^2 e^{(\nu+\lambda)/2}(\epsilon +3P)dr,$$

while the baryon mass of the star is

$$ M_0 = \int_0^R 4\pi r^2 e^{\lambda/2}\rho dr. $$

## Polytropic Equation
The polytropic equation of state is
$$P = K\rho^\Gamma,$$
Integrating the first law of thermodynamics for barotropic fluids
$$ d\frac{\epsilon}{\rho} = - P d\frac{1}{\rho}$$
yields 
$$ \epsilon = \rho + \frac{P}{\Gamma-1}$$
