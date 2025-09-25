Orbital Mechanics Simulations in Python
This repository contains several Python scripts that simulate orbital motion using different numerical methods and physical models. These simulations are designed to explore the behavior of celestial bodies under gravitational forces, and compare the accuracy and stability of various integration techniques.

 Contents

1. **Circular Orbit with Euler-Cromer Method**
- Simulates Earth's circular orbit around the Sun.
- Uses the **Euler-Cromer method**, which is a stable variant of Euler’s method for energy-conserving systems.
- Assumes inverse-square gravitational force: \( F \propto \frac{1}{r^2} \)

2. **Elliptical Orbit with Reduced Initial Velocity**
- Demonstrates how reducing the initial tangential velocity leads to an elliptical orbit.
- Still uses Euler-Cromer integration.
- Highlights the sensitivity of orbital shape to initial conditions.

3. **Orbital Behavior for Different Gravitational Exponents**
- Tests how changing the exponent \( n \) in the gravitational force law \( F \propto \frac{1}{r^n} \) affects orbital stability.
- Compares three cases: \( n = 1.5 \), \( n = 2.0 \), and \( n = 3.0 \)
- Shows that only \( n = 2 \) produces closed elliptical orbits (Bertrand’s theorem).

4. **Orbit Comparison: Euler-Cromer vs Runge-Kutta 2 vs Runge-Kutta 4**
- Compares three numerical integration methods:
  - Euler-Cromer (2nd order)
  - Runge-Kutta 2nd order (RK2)
  - Runge-Kutta 4th order (RK4)
- All methods simulate the same initial conditions.
- Visual comparison shows how higher-order methods improve accuracy and orbital stability.


اگه بخوای می‌تونم این توضیح رو به صورت `README.md` با فرمت Markdown برات آماده کنم یا به هر بخش از کدها لینک و توضیح جداگانه بدم. دوست داری پروژه رو به صورت ساختارمند تو گیت‌هاب بچینیم؟
