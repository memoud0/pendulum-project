# Pendulum Motion Analysis

This project delves into pendulum motion dynamics using the Verlet method, examining its efficacy with and without the small-angle approximation. The Verlet method, a numerical integration technique, aids in predicting particle trajectories, while the small-angle approximation simplifies calculations for small angles, commonly applied in pendulum motion analysis.

The code plots θ vs time using both Euler and Verlet methods, showcasing their comparative accuracy. By simulating pendulum motion with and without the small-angle approximation, the project demonstrates how the approximation holds for lesser angles but deviates for larger ones, impacting period predictions. Verlet's method proves superior over time compared to Euler's, maintaining accuracy in describing pendulum behavior.

Discussion focuses on the suitability of Verlet's method for second-order differential equations, contrasting with the limitations of the small-angle approximation, particularly evident for larger angles. The project concludes by emphasizing Verlet's superiority in accurately describing pendulum motion dynamics and suggests potential improvements to include additional variables like air resistance for a more realistic model.
