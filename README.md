# ODEs

Basic Ordinary Differential Equation solvers implemented in Julia.
Book: Steven C. Chapra, Applied Numerical Method with MATLAB® for Engineers and Scientists. Third Edition, 2008

Pull requests are always highly welcome to fix bugs, add solvers, or anything else!

# Current status of the project
The first release (beta), v0.0, contains the basic functionality including:

* Euler's method
* Heun's method with iterations
* Runge Kutta 5th order

all of which have the following basic API:

    tout, yout = solver(F, tspan, y0; keywords...)

# Keywords
* h, step size (default = 1)
* AbsTol, Error tolerance (default =  0.00001)


Developed at the Instituto Tecnologico de Orizaba, Mexico.
PhD Kelvyn Baruc Sánchez Sánchez
