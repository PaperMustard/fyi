
> **AP Exam Weight**: 20-30% | Multiple Choice: 8-12 questions | Free Response: Major focus in several questions

## 📚 Table of Contents
1. [Area & Volume](#area)
2. [Average Value](#average)
3. [Cross Sections](#cross)
4. [Arc Length](#length)
5. [Integration Applications](#applications)

## 1. Area & Volume 📊 {#area}

### Understanding Area Applications
Area between curves represents accumulated difference. Think of it as:
- Net difference between functions
- Accumulated space
- Bounded regions
- Definite integral application

### Finding Area
#### Between Two Curves
$A = \int_a^b |f(x) - g(x)|dx$

#### Process
1. **Identify Functions**
   - Determine upper/lower curves
   - Find intersection points
   - Check domain restrictions
   - Consider orientation

2. **Set Up Integral**
   - Choose appropriate bounds
   - Order functions correctly
   - Consider absolute value
   - Check for multiple regions

3. **Evaluate**
   - Use integration techniques
   - Verify result
   - Check reasonableness
   - Consider symmetry

#### Example Walkthrough
Find area between y = x² and y = x from x = 0 to x = 1
1. **Graph curves**:
   - y = x is linear
   - y = x² is parabola
   - x intersects at 0, 1
2. **Compare functions**:
   - x > x² on (0,1)
   - x is upper curve
3. **Set up integral**:
   - $A = \int_0^1 (x - x^2)dx$
4. **Evaluate**:
   - $= [\frac{x^2}{2} - \frac{x^3}{3}]_0^1$
   - $= (\frac{1}{2} - \frac{1}{3})$
   - $= \frac{1}{6}$

### Volume Calculations
#### Understanding Methods
Think of volumes as:
- Accumulated cross-sections
- Rotated regions
- Sliced solids
- Three-dimensional accumulation

#### Disk Method
$V = \pi\int_a^b [f(x)]^2dx$

##### When to Use
- Rotating around x-axis
- Simple function squared
- Circular cross sections
- Solid with no hole

#### Washer Method
$V = \pi\int_a^b [R(x)^2 - r(x)^2]dx$

##### When to Use
- Rotating around axis
- Region between curves
- Hollow objects
- Nested cylinders

#### Shell Method
$V = 2\pi\int_a^b xf(x)dx$

##### When to Use
- Rotating around y-axis
- Complex functions
- Multiple regions
- Often simpler integration

#### Method Selection Guide
1. **Choose Disk/Washer When**:
   - Rotating around horizontal axis
   - Simple function squared
   - Clear outer/inner functions
   - Straightforward bounds

2. **Choose Shell When**:
   - Rotating around vertical axis
   - Complex functions
   - Multiple regions
   - Easier integration

#### Example Walkthrough
Find volume when y = x² is rotated about y-axis from y = 0 to y = 4
1. **Analyze problem**:
   - Rotating around y-axis
   - Need x in terms of y
   - Shell method best
2. **Set up**:
   - x = ±√y
   - Use shell method
3. **Integrate**:
   - $V = 2\pi\int_0^4 \sqrt{y} \cdot y dy$
   - $= 2\pi[\frac{2y^{5/2}}{5}]_0^4$

### Common Mistakes
1. **Setup Errors**:
   - Wrong method choice
   - Incorrect radius
   - Wrong axis of rotation
   - Bound confusion

2. **Calculation Errors**:
   - Forgetting π
   - Square vs. squared function
   - Wrong substitution
   - Integration mistakes

## 2. Average Value {#average}

### Understanding Average Value
The average value of a function over an interval. Think of it as:
- Average height of a curve
- Equally distributed value
- Definite integral application

### Formula
$\bar{f} = \frac{1}{b-a}\int_a^b f(x)dx$

#### Process
1. **Set Up Integral**
   - Determine bounds
   - Check units

2. **Evaluate**
   - Use integration techniques
   - Divide by interval length
   - Verify units
   - Check reasonableness

#### Example Walkthrough
Find average value of f(x) = x² on [0,2]
1. **Set up integral**:
   - $\bar{f} = \frac{1}{2-0}\int_0^2 x^2 dx$
2. **Evaluate**:
   - $= \frac{1}{2}\int_0^2 x^2 dx$
   - $= \frac{1}{2}[\frac{x^3}{3}]_0^2$
   - $= \frac{1}{2}[\frac{8}{3} - 0]$
   - $= \frac{4}{3}$

## 3. Cross Sections {#cross}

### Understanding Cross Sections
The area of a cross-section of a solid. Think of it as:
- Slice of a solid
- Definite integral application

### Formula
$A = \int_a^b f(x)dx$

#### Process
1. **Identify Function**
   - Function describing cross-section
   - Check domain restrictions
   - Consider orientation

2. **Set Up Integral**
   - Choose appropriate bounds
   - Check units

3. **Evaluate**
   - Use integration techniques
   - Verify result
   - Check reasonableness

#### Example Walkthrough
Find area of cross-section of solid with f(x) = x²
1. **Set up integral**:
   - $A = \int_0^2 x^2 dx$
2. **Evaluate**:
   - $= [\frac{x^3}{3}]_0^2$
   - $= \frac{8}{3}$

## 4. Arc Length 📐 {#length}

### Understanding Arc Length
The true distance along a curve. Think of it as:
- Path length
- Curve measurement
- Accumulated distance
- True curve size

### Formula
$L = \int_a^b \sqrt{1 + [f'(x)]^2}dx$

#### Process
1. **Find Derivative**
   - Calculate f'(x)
   - Square the derivative
   - Add 1
   - Take square root

2. **Set Up Integral**
   - Determine bounds
   - Simplify if possible
   - Consider substitution
   - Check complexity

3. **Evaluate**
   - Choose technique
   - Watch for special cases
   - Verify units
   - Check reasonableness

#### Example Walkthrough
Find length of y = x² from x = 0 to x = 1
1. **Find f'(x)**:
   - f'(x) = 2x
2. **Set up integral**:
   - $L = \int_0^1 \sqrt{1 + 4x^2}dx$
3. **Evaluate**:
   - Use substitution
   - u = 2x
   - Result involves ln

## 5. Integration Applications {#applications}

### Understanding Integration Applications
Integration has various applications in calculus. Think of it as:
- Solving problems
- Finding areas
- Calculating volumes
- Modeling real-world scenarios

### Common Applications
1. **Area Between Curves**
   - $A = \int_a^b |f(x) - g(x)|dx$
2. **Volume of Revolution**
   - $V = \pi\int_a^b [f(x)]^2dx$
3. **Average Value**
   - $\bar{f} = \frac{1}{b-a}\int_a^b f(x)dx$
4. **Cross Sections**
   - $A = \int_a^b f(x)dx$

### Example Walkthrough
Find area between y = x² and y = x from x = 0 to x = 1
1. **Graph curves**:
   - y = x is linear
   - y = x² is parabola
   - x intersects at 0, 1
2. **Compare functions**:
   - x > x² on (0,1)
   - x is upper curve
3. **Set up integral**:
   - $A = \int_0^1 (x - x^2)dx$
4. **Evaluate**:
   - $= [\frac{x^2}{2} - \frac{x^3}{3}]_0^1$
   - $= (\frac{1}{2} - \frac{1}{3})$
   - $= \frac{1}{6}$

## 📝 AP-Style Examples

### Example 1: Area Between Curves
Find area between $y = x^2$ and $y = \sqrt{x}$ from x = 0 to x = 1

**Solution**:
1. **Compare functions**:
   - $\sqrt{x} > x^2$ on (0,1)
   - $\sqrt{x}$ is upper curve
2. **Set up integral**:
   - $A = \int_0^1 (\sqrt{x} - x^2)dx$
3. **Evaluate**:
   - $= [\frac{2x^{3/2}}{3} - \frac{x^3}{3}]_0^1$
   - $= \frac{2}{3} - \frac{1}{3} = \frac{1}{3}$

### Example 2: Volume of Revolution
Find volume when $y = \sin x$ is rotated about x-axis from x = 0 to x = π

**Solution**:
1. **Choose method**:
   - Rotating around x-axis
   - Use disk method
2. **Set up integral**:
   - $V = π\int_0^π [\sin x]^2dx$
3. **Evaluate**:
   - $= π\int_0^π \frac{1 - \cos(2x)}{2}dx$
   - $= π[\frac{x}{2} - \frac{\sin(2x)}{4}]_0^π$
   - $= \frac{π^2}{2}$

### Example 3: Average Value
Find average value of $f(x) = \cos x$ on $[0,\frac{π}{2}]$

**Solution**:
1. **Apply formula**:
   - $\bar{f} = \frac{2}{π}\int_0^{π/2} \cos x dx$
2. **Evaluate**:
   - $= \frac{2}{π}[\sin x]_0^{π/2}$
   - $= \frac{2}{π}$

## 💡 Success Strategies

### 1. Setting Up Integrals
- Draw and label diagrams
- Identify correct bounds
- Choose appropriate method
- Verify integrand

### 2. Common Mistakes
- Wrong integration method
- Incorrect bounds
- Missing absolute value
- Function order confusion

### 3. Calculator Tips
- Graph to verify regions
- Check intersections
- Confirm reasonableness
- Use numerical integration

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show all work**:
   - Draw and label diagrams
   - Write correct integrals
   - Show evaluation steps
   - State final answer

2. **Common Questions**:
   - Area between curves
   - Volume of revolution
   - Average value
   - Cross sections

### Multiple Choice Strategy
1. **Analyze the Problem**:
   - Read carefully
   - Draw quick sketch
   - Consider all methods
   - Look for patterns

2. **Check Answer**:
   - Reasonable magnitude
   - Correct sign
   - Appropriate units
   - Matches graph

## 📊 Quick Reference

### Area Formulas
1. Between curves: $\int_a^b |f(x) - g(x)|dx$
2. With respect to y: $\int_c^d |h(y) - k(y)|dy$

### Volume Formulas
1. Disk Method: $π\int_a^b [f(x)]^2dx$
2. Washer Method: $π\int_a^b [R(x)^2 - r(x)^2]dx$
3. Shell Method: $2π\int_a^b xf(x)dx$

### Other Applications
1. Average Value: $\frac{1}{b-a}\int_a^b f(x)dx$
2. Arc Length: $\int_a^b \sqrt{1 + [f'(x)]^2}dx$

---

*💡 Pro Tip: Always sketch the region first - it helps identify the correct integration method and bounds!* 