# Land-subsidence
inversion calculation for land subsidence

The finite layer method can make use of the orthogonality of analytical functions to achieve the decoupling between various series terms. In view of the decoupling of finite layer method, which can be optimized by the paralleled method to improve the efficiency of solving large-scale complex problems. On this basis, combined with the nonlinear homotopy method, a new land subsidence inversion method is proposed. A corresponding program was compiled by means of MATLAB.

LSTIME is the forward modeling program, which is the main command flow of the software. It calculates the land subsidence by inputting different formation parameters. INVERSION PROGRAM is an inversion program, which can also be used to record the running time of the program. PARALLEL PROGRAM can call MATLAB parallel library, make full use of computer CPU, and effectively reduce the running time. GUASS is the command stream of the guass function required for calculation in the program.

