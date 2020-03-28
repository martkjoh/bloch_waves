# bloch_waves
An exploration of the wave functions of particles in periodic boundary conditions.

Given a periodic potential with a period a,

![equation](https://latex.codecogs.com/gif.latex?V%28x%20&plus;%20a%29%20%3D%20V%28a%29)

we get a hamiltonian which commutes with the discrete transelation operator

![equation](https://latex.codecogs.com/gif.latex?%5Chat%20T_n%20%5Cpsi%28x%29%20%3D%20%5Cpsi%28x%20&plus;%20na%29),

and they thus have a common set of eigenvectors, 

![equation](https://latex.codecogs.com/gif.latex?%5Chat%20T_n%20%5Cpsi_k%28x%29%20%3D%20%5Cexp%28ikna%29%5Cpsi_k%28x%29%2C%20%5C%2C%5C%2C%20%5Chat%20H%20%5Cpsi_k%28x%29%20%3D%20E_k%20%5Cpsi_k%28x%29.)

This is Blochs theorem. 


First, we have free waves with the periodic boundary condition,

![equation](https://latex.codecogs.com/gif.latex?%5Cpsi%28x%20&plus;%20L%29%20%3D%20%5Cpsi%28x%29).

![img](figs/vecs_0.png).

The eigenvalues, as a function of k, forms a parabola (For low values. High values will have deviacies from the errors in finite difference.) If we plot this insed the first brillouin zone, we get:

![img](figs/vals_0.png)

Adding a periodic disturbance, 

![equation](https://latex.codecogs.com/gif.latex?V%20%3D%20V_0%20%5Ccos%282pi/a%20x%29)

we get a bloch function

![img](figs/vecs_1.png)

and a band gap

![img](figs/vals_1.png) 

Continuing to add more frequencies

![eq](https://latex.codecogs.com/gif.latex?V%20%3D%20V_0%20%28%5Ccos%282pi/a%20x%29%20&plus;%20%5Ccos%284pi/a%20x%29%20&plus;%20%5Cdots%29)

give more gaps

![img](figs/vals_2.png)
![img](figs/vals_3.png)

Equation from [codecogs](https://www.codecogs.com/latex/eqneditor.php)
