
> **AP Exam Weight**: 15-25% | Multiple Choice: 6-10 questions | Free Response: Usually 1 full question

## 📚 Table of Contents
1. [Slope Fields](#fields)
2. [Separable Equations](#separable)
3. [Logistic Growth](#logistic)
4. [Euler's Method](#euler)
5. [Applications](#applications)

## Basic Concepts 📈 {#basics}

### Key Terms
- Order: Highest derivative
- Linear vs. Nonlinear
- Initial value problem (IVP)
- General solution

### Common Forms
1. Separable: $\frac{dy}{dx} = f(x)g(y)$
2. Linear: $\frac{dy}{dx} + P(x)y = Q(x)$
3. Logistic: $\frac{dy}{dt} = ky(1-\frac{y}{M})$

## Solution Methods 🔧 {#methods}

### Separation of Variables
1. Separate y and x terms
2. Integrate both sides
3. Solve for y
4. Apply initial conditions

### Integration
$y = \int f(x)dx + C$

### Euler's Method
$y_{n+1} = y_n + f(x_n,y_n)\Delta x$

## Applications 🎯 {#applications}

### Growth/Decay
$\frac{dy}{dt} = ky$
- Solution: $y = Ce^{kt}$

### Logistic Growth
$\frac{dy}{dt} = ky(1-\frac{y}{M})$
- Solution: $y = \frac{M}{1 + Ce^{-kt}}$

### Newton's Law of Cooling
$\frac{dT}{dt} = k(T-T_s)$
- Solution: $T = T_s + (T_0-T_s)e^{kt}$

## 1. Slope Fields 📊 {#fields}

### Understanding Slope Fields
A visual representation of differential equations. Think of it as:
- Direction field for solutions
- Map of solution curves
- Tangent line indicators
- Solution path guide

### Creating Slope Fields
#### Process
1. **Identify dy/dx**:
   - Write equation in standard form
   - Isolate derivative
   - Understand variables
   - Note special cases

2. **Plot Slopes**:
   - Choose grid points
   - Calculate slope at each point
   - Draw short line segments
   - Maintain consistent length

3. **Analyze Pattern**:
   - Look for symmetry
   - Find equilibrium solutions
   - Note key behaviors
   - Identify solution types

### Example Walkthrough - Slope Fields
For $\frac{dy}{dx} = x - y$
1. **Create grid**:
   - Choose points (-2,-2) to (2,2)
   - Mark intersections
   - Consider scale
   - Note key points

2. **Calculate slopes**:
   - At (0,0): slope = 0
   - At (1,0): slope = 1
   - At (0,1): slope = -1
   - Pattern emerges

3. **Draw segments**:
   - Use consistent length
   - Show direction
   - Connect smoothly
   - Verify pattern

## 2. Separable Equations 📈 {#separable}

### Understanding Separable Equations
Equations where variables can be separated. Think of it as:
- Grouping like terms
- Dividing variables
- Independent integration
- Reverse chain rule

### Solution Process
#### Steps for Solving
1. **Identify Form**:
   - Check if $\frac{dy}{dx} = f(x)g(y)$
   - Variables must separate
   - No mixed terms
   - Clear denominators

2. **Separate Variables**:
   - Move y terms to one side
   - Move x terms to other side
   - Write in differential form
   - Check domain

3. **Integrate Both Sides**:
   - Use standard integrals
   - Watch for substitutions
   - Include constants
   - Check signs

4. **Solve for y**:
   - Isolate y variable
   - Use algebra
   - Consider domain
   - Verify solution

#### Example Walkthrough
Solve $\frac{dy}{dx} = xy$
1. **Separate**:
   - $\frac{dy}{y} = xdx$
2. **Integrate**:
   - $\ln|y| = \frac{x^2}{2} + C$
3. **Solve**:
   - $y = ±e^{x^2/2 + C}$
   - $y = Ce^{x^2/2}$

## 3. Logistic Growth 📊 {#logistic}

### Understanding Logistic Growth
Models bounded growth. Think of it as:
- Limited population growth
- S-shaped curve
- Carrying capacity model
- Restricted exponential growth

### Standard Form
$\frac{dy}{dt} = ky(1-\frac{y}{M})$

#### Components
1. **Growth Rate (k)**:
   - Initial growth speed
   - Positive constant
   - Affects steepness
   - Time scaling

2. **Carrying Capacity (M)**:
   - Maximum value
   - Horizontal asymptote
   - Limiting factor
   - Final equilibrium

### Solution Process
1. **Set Up Equation**:
   - Identify k and M
   - Write in standard form
   - Check initial conditions
   - Note constraints

2. **Separate Variables**:
   - Partial fractions
   - Split terms
   - Integrate both sides
   - Solve for y

3. **Final Form**:
   - $y = \frac{M}{1 + Ce^{-kt}}$
   - C from initial condition
   - Verify solution
   - Check behavior

#### Example Walkthrough
Population with k = 0.5, M = 1000, P₀ = 100
1. **Write equation**:
   - $\frac{dP}{dt} = 0.5P(1-\frac{P}{1000})$
2. **Use formula**:
   - $P = \frac{1000}{1 + Ce^{-0.5t}}$
3. **Find C**:
   - Use P(0) = 100
   - Solve for C = 9

## 4. Euler's Method 🔄 {#euler}

### Understanding Euler's Method
Numerical approximation technique. Think of it as:
- Step-by-step approximation
- Tangent line walking
- Numerical integration
- Local linear approximation

### Formula
$y_{n+1} = y_n + f(x_n,y_n)\Delta x$

### Implementation Process
1. **Set Up**:
   - Choose Δx
   - List initial values
   - Create table
   - Plan steps

2. **Calculate Steps**:
   - Find slope
   - Use formula
   - Record values
   - Continue pattern

3. **Analyze Error**:
   - Smaller Δx = better
   - Accumulating error
   - Compare to actual
   - Consider improvements

#### Example Walkthrough
Use Euler's method for $\frac{dy}{dx} = x + y$, y(0) = 1, Δx = 0.2
1. **Create table**:
   - x₀ = 0, y₀ = 1
2. **First step**:
   - f(0,1) = 0 + 1 = 1
   - y₁ = 1 + 1(0.2) = 1.2
3. **Continue**:
   - x₁ = 0.2, y₁ = 1.2
   - f(0.2,1.2) = 1.4
   - y₂ = 1.2 + 1.4(0.2)

## 5. Applications 🎯 {#applications}

### Types of Applications
1. **Population Growth**:
   - Exponential
   - Logistic
   - Predator-prey
   - Competition

2. **Decay Problems**:
   - Radioactive decay
   - Temperature
   - Half-life
   - Cooling

3. **Financial Models**:
   - Compound interest
   - Investment growth
   - Payment schedules
   - Market models

### Example Walkthrough
Newton's Law of Cooling: T(0) = 100°, room 70°
1. **Write equation**:
   - $\frac{dT}{dt} = k(T-70)$
2. **Solve**:
   - $T = 70 + Ce^{kt}$
3. **Use initial condition**:
   - 100 = 70 + C
   - C = 30

## 📝 AP-Style Examples

### Example 1: Slope Fields
Given $\frac{dy}{dx} = x^2 - y$, sketch slope field and solution curve through (0,1)

**Solution**:
1. **Create slope field**:
   - Calculate slopes at key points
   - Draw segments carefully
   - Note equilibrium curve y = x²
   - Show solution direction

2. **Solution curve**:
   - Start at (0,1)
   - Follow slope pattern
   - Note curve approaches y = x²
   - Show decreasing initially

### Example 2: Euler's Method
Use two steps of Euler's method to approximate y(0.4) for $\frac{dy}{dx} = x + y$, y(0) = 1, Δx = 0.2

**Solution**:
1. **First step**:
   - y₁ = 1 + (0 + 1)(0.2)
   - y₁ = 1.2 at x = 0.2

2. **Second step**:
   - y₂ = 1.2 + (0.2 + 1.2)(0.2)
   - y₂ = 1.48 at x = 0.4

### Example 3: Logistic Growth
A population follows $\frac{dP}{dt} = 0.1P(1-\frac{P}{500})$ with P(0) = 50. Find P(10).

**Solution**:
1. **Identify**:
   - k = 0.1
   - M = 500
   - P₀ = 50

2. **Use formula**:
   - $P = \frac{500}{1 + 9e^{-0.1t}}$
   - Substitute t = 10
   - P(10) ≈ 187.8

## 💡 Success Strategies

### 1. Equation Classification
- Check for separable form first
- Look for linear patterns
- Identify growth/decay type
- Consider special cases

### 2. Solution Process
- Draw slope field first
- Use Euler's for approximation
- Solve analytically when possible
- Verify with initial conditions

### 3. Common Mistakes
1. **Slope Fields**:
   - Wrong slope direction
   - Inconsistent segment length
   - Missing key points
   - Incorrect equilibrium lines

2. **Euler's Method**:
   - Wrong step size
   - Calculation errors
   - Not showing work
   - Skipping intermediate values

3. **Analytical Solutions**:
   - Incorrect separation
   - Missing absolute value
   - Wrong integration
   - Forgetting +C

## 🔍 AP Exam Focus

### Free Response Tips
1. **Slope Fields**:
   - Show clear segments
   - Consistent length
   - Correct direction
   - Solution curves match field

2. **Euler's Method**:
   - Organize in table
   - Show all calculations
   - Round appropriately
   - Include units

3. **Analytical Solutions**:
   - Show separation clearly
   - Include all steps
   - Verify initial conditions
   - Check final answer

### Multiple Choice Strategy
1. **Quick Checks**:
   - Direction field pattern
   - Solution behavior
   - Initial condition match
   - Long-term behavior

2. **Common Traps**:
   - Sign errors
   - Missing factors
   - Wrong method choice
   - Incomplete solutions

## 📊 Quick Reference

### Equation Types
1. Separable: $\frac{dy}{dx} = f(x)g(y)$
2. Linear: $\frac{dy}{dx} + P(x)y = Q(x)$
3. Logistic: $\frac{dy}{dt} = ky(1-\frac{y}{M})$

### Key Methods
1. **Separation**:
   - $\int \frac{dy}{g(y)} = \int f(x)dx$
   - Solve for y
   - Use initial conditions

2. **Euler's**:
   - $y_{n+1} = y_n + f(x_n,y_n)\Delta x$
   - Table format
   - Multiple steps

3. **Slope Fields**:
   - Grid points
   - Short segments
   - Consistent length
   - Show pattern

### Important Solutions
1. **Exponential Growth/Decay**:
   - $y = Ce^{kt}$
   - Unrestricted growth
   - Proportional change

2. **Logistic Growth**:
   - $y = \frac{M}{1 + Ce^{-kt}}$
   - Limited growth
   - S-shaped curve

3. **Linear**:
   - Use integrating factor
   - $μ(x) = e^{\int P(x)dx}$
   - Multiply through

---

*💡 Pro Tip: When in doubt, start with a slope field - it gives you the big picture of solution behavior!* 