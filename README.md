# ODEs

Basic Ordinary Differential Equation solvers implemented in Julia.
Book: Steven C. Chapra, Applied Numerical Method with MATLAB® for Engineers and Scientists. Third Edition, 2008

This is an unregistred package. To install on Julia use:

    Pkg.clone("git://github.com/Kelvyn88/ODEs.jl")
    
To track changes across versions, the package should be registered into the local METADATA. Pull requests are always highly welcome to fix bugs, add solvers, or anything else!

# Current status of the project
The first release v0.0.1, contains the basic functionality including:

* Euler's method (euler)
* Heun's method with iterations (heun)
* Runge Kutta 5th order (rk5)

all of which have the following basic API:

    tout, yout = solver(F, tspan, y0; keywords...)

# Keywords
* h, step size (default = 1)
* AbsTol, Error tolerance (default =  0.00001)


Developed at the Instituto Tecnologico de Orizaba, Mexico.

Ph D Kelvyn Baruc Sánchez Sánchez.
email: kelvyn.baruc@gmail.com
