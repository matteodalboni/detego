# Detego
A linear algebra library offering a wide selection of matrix decompositions and direct solvers for real-valued dense matrices.

One of the distinctive traits of *Detego* is that all the algorithms are built around in-place operations, ensuring a minimal memory footprint. Fully implemented in plain C, the library adopts single-precision arithmetic and avoids dynamic memory allocation. All of these features make *Detego* ideal for embedded systems.

## Testing on Linux
gcc -o mydemo demo/mydemo.c src/detego.c -lm -I inc

## References
[1] Golub, Gene H., and Charles F. Van Loan. *Matrix computations*. JHU press, 2013.\
[2] Nash, John C. *Compact numerical methods for computers: linear algebra and function minimisation*. Routledge, 2018.\
[3] MATLAB documentation.
