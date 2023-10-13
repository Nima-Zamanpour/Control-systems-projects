This Repository contains the MATLAB files (including .m and Simulink) for the implementation of a state-space control system in Mag-Lev trains as the final project of the Digital Control Systems course. The project description and report are in Farsi.

The project is made of several parts:
1. **Given the system state equations, Equilibrium points are found.**
2. **The system is Linearized around the equilibrium point, and a state matrix is formed.**
3. **State-transition matrix is calculated.**
4. **A transfer function matrix is calculated, and a PID controller is designed to control the output of both linear and non-linear systems.**
5. **Controller is digitalized using matched zero and pole, bilinear transform and zero-order hold in three different sample rates, and the results are compared to continuous controller.**
6. **System transfer function is discretized, and a digital controller is designed for it. Then, systems characteristics like phase margin, gain margin, and bandwidth are reported.**
7. **Deadbeat controller is designed for the digital system.**
8. **System state space matrix is digitalized to form a Discrete state space matrix. Controllability and observability criteria are checked.**
9. **A deadbeat controller is designed for the discretized state space system, first assuming access to all state variables, second using a full-rank observer**
10. **All systems are tested in the presence of noise.**
