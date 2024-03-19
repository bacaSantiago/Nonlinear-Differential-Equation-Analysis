# Nonlinear Differential Equation Analysis  

This Python program offers a comprehensive exploration of a homogeneous nonlinear differential equation, providing insights into its dynamics, stability, and sensitivity to initial conditions. By analyzing fixed points, trajectory evolution, and potential landscapes, users gain a deep understanding of the system's behavior under different parameters. Additionally, the program investigates the impact of small perturbations on trajectory outcomes, highlighting regions where precision in initial values is crucial.

The equation is defined as:

$$\frac{dx}{dt} = x(b - x^2); x(0) = x_{0}$$  

Now let's delve into the specific functionalities provided by the program:

1. **Fixed Points and Stability:**
   - The program calculates fixed points and evaluates stability, crucial for understanding the dynamics of the system.

2. **Trajectory Evolution and Basins:**
   - It visualizes trajectory evolution over time, highlighting basins of attraction for different initial conditions.

3. **Potential Function Analysis:**
   - The program calculates and graphs the potential function, providing insights into the energy landscape of the system.

4. **Parameter Variation Analysis:**
   - Users can explore how varying the parameter \( b \) affects the system's behavior by generating graphs of trajectory evolution and potential functions for different \( b \) values.

5. **Initial Condition Sensitivity Analysis:**
   - It investigates the sensitivity of the system to initial conditions by analyzing the quotient \( \frac{Δ(t=5)}{Δ(t=0)} \) for perturbed initial conditions, highlighting regions where precision in initial values is crucial.

## Dependencies

- [NumPy](https://numpy.org/doc/stable/)  
- [Matplotlib](https://matplotlib.org/stable/contents.html)  
- [matplotlib.animation](https://matplotlib.org/stable/api/animation_api.html)  
- [IPython.display](https://ipython.readthedocs.io/en/stable/api/generated/IPython.display.html)  
- [Pillow](https://pillow.readthedocs.io/en/stable/)  

## Resources

The program utilizes images for visualization and analysis:

- **Branch Diagram:** An image representing a branch diagram relevant to the analysis.
- **Trajectory Evolution Graphs:** Images displaying the trajectory evolution for different initial conditions and values of \( b \).
- **Potential Function Graphs:** Images illustrating the potential function for different values of \( b \).

Through a combination of mathematical analysis and visualizations, this program offers a holistic exploration of nonlinear differential equations, shedding light on their intricate dynamics and underlying principles.