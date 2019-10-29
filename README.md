# complex_lms_adaptive_fir_filter
Complex LMS adaptive FIR filter reference implementation.

Industry standard and documented (inline) C API.

Example usage provided in main.cpp.

Real valued LMS adaptive FIR filter can be accomplished by setting all imaginary values to zero.

Optimization is easily possible through vectorization (SIMD).

**References**
B. Widrow, J McCool, and M. Ball, "The Complex LMS Algorithm", Proceedings of the IEEE, April 1975. p 719-720.
