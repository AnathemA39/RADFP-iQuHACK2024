# RADFP-iQuHACK2024 Repository
This repository encompasses the code and documentation for the project crafted by Team RADFP during the 2024 MIT's iQuHACK.

Our project is centered around tackling the [Classiq challenge,](https://github.com/iQuHACK/2024_Classiq/tree/main) harnessing quantum computing techniques to discover the most precise approximation of tanh(x) within the domain:

    f(x):(0,1]→(0,1]

We adeptly employed a second-order polynomial approximation to approximate tanh(x) within the domain (0,1]. The polynomial was derived by fitting a second-order polynomial to the hyperbolic tangent function.

In Stage 1, we achieved a precision of 4 with a max_distance of approximately 0.07170, utilizing only 25 qubits. Progressing to Stage 2, we elevated the precision to 7 while achieving a circuit depth of 2260.

For a more in-depth exploration of the challenge, kindly refer to the document titled "Classiq’s Generalized Arithmetic Challenge.pdf."
