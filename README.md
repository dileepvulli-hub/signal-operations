
## MATLAB to Python Conversion – Description
This program demonstrates the **conversion of basic signal generation programs from MATLAB to Python**. MATLAB is widely used for signal processing, but Python provides an open-source alternative using libraries such as **NumPy, Matplotlib, and Math**.

In this program, several **basic signals used in Signals and Systems** are generated using Python. The time axis is created using loops instead of MATLAB functions like `linspace` or `arange`. The signals are then plotted using the **Matplotlib library**, which performs a role similar to MATLAB plotting functions.

The following signals are implemented:

1. **Unit Step Signal**

   * The signal value is **0 for t < 0** and **1 for t ≥ 0**.
   * Implemented using conditional statements in Python.

2. **Unit Impulse Signal**

   * The signal is **1 at t = 0** and **0 for all other time values**.
   * This simulates the discrete impulse function.

3. **Unit Ramp Signal**

   * The signal increases linearly for **t ≥ 0** and remains **0 for t < 0**.

4. **Exponential Signal**

   * Generated using the **math.exp()** function to represent an exponential growth signal.

5. **Sinusoidal Signal**

   * Created using **math.sin()** to represent a sine wave over a time interval.

6. **Addition of Signals**

   * Two signals **sin(t)** and **cos(t)** are generated and added together to produce a new signal.

7. **Multiplication of Signals**

   * The signals **sin(t)** and **cos(t)** are multiplied to demonstrate signal operations.

Python's **Matplotlib plotting functions such as `plot()`, `stem()`, and `subplot()`** are used to visualize the signals similarly to MATLAB's `plot`, `stem`, and `subplot` functions.
