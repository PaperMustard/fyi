
> **AP Exam Weight**: 25-35% | Multiple Choice: 10-14 questions | Free Response: Major focus in several questions

## 📚 Table of Contents
1. [Antiderivatives](#antiderivatives)
2. [Definite Integrals](#definite)
3. [Integration Techniques](#techniques)
4. [Applications](#applications)
5. [Fundamental Theorem](#ftc)

## 1. Antiderivatives 📊 {#antiderivatives}

### Understanding Antiderivatives
The reverse process of differentiation. Think of it as:
- Finding the original function from its derivative
- Recovering distance from velocity
- Working backwards through changes
- Finding a family of related functions

### Basic Rules
#### Power Rule Integration
$\int x^n dx = \frac{x^{n+1}}{n+1} + C$ (n ≠ -1)

#### Process
1. Add 1 to exponent
2. Divide by new exponent
3. Add constant of integration
4. Check by differentiating

#### Example Walkthrough
Find $\int 3x^2 dx$
1. **Identify parts**:
   - Coefficient: 3
   - Base: x
   - Exponent: 2
2. **Apply rule**:
   - Add 1 to exponent: x³
   - Divide by new exponent: $\frac{x^3}{3}$
   - Multiply by coefficient: $x^3$
3. **Add C**:
   - Final answer: $x^3 + C$
4. **Verify**:
   - Differentiate: $\frac{d}{dx}(x^3 + C) = 3x^2$

### Common Antiderivatives
#### Exponential Functions
- $\int e^x dx = e^x + C$
- $\int a^x dx = \frac{a^x}{\ln a} + C$

#### Trigonometric Functions
- $\int \sin x dx = -\cos x + C$
- $\int \cos x dx = \sin x + C$
- $\int \sec^2 x dx = \tan x + C$
- $\int \csc^2 x dx = -\cot x + C$

#### Special Cases
- $\int \frac{1}{x} dx = \ln|x| + C$
- $\int \frac{1}{\sqrt{1-x^2}} dx = \arcsin x + C$
- $\int \frac{1}{1+x^2} dx = \arctan x + C$

## 2. Definite Integrals 🎯 {#definite}

### Understanding Definite Integrals
The definite integral represents total accumulation. Think of it as:
- Area under a curve
- Total distance traveled
- Accumulated change
- Net accumulation over interval

### Definition
$\int_a^b f(x)dx = \lim_{n \to \infty} \sum_{i=1}^n f(x_i^*)\Delta x$

#### Intuitive Understanding
- Sum of many tiny rectangles
- Better approximation as n increases
- Like slicing area into thin strips
- Limit of Riemann sums

#### Process for Riemann Sums
1. Divide interval into n subintervals
2. Choose sample points
3. Form sum of rectangles
4. Take limit as n → ∞

#### Example Walkthrough
Approximate $\int_0^2 x^2 dx$ with n = 4
1. **Set up**:
   - Δx = (2-0)/4 = 0.5
   - Points: 0, 0.5, 1, 1.5, 2
2. **Calculate heights**:
   - f(0) = 0
   - f(0.5) = 0.25
   - f(1) = 1
   - f(1.5) = 2.25
   - f(2) = 4
3. **Form sum**:
   - Σf(x)Δx = (0 + 0.25 + 1 + 2.25)·0.5
4. **Compare to actual**:
   - Approximation ≈ 2.67
   - Actual = 8/3 ≈ 2.67

### Properties
#### Basic Properties
1. **Reversal of Limits**:
   - $\int_a^b f(x)dx = -\int_b^a f(x)dx$
   - Like walking backwards
   - Changes sign
   - Same magnitude

2. **Additivity**:
   - $\int_a^b [f(x) \pm g(x)]dx = \int_a^b f(x)dx \pm \int_a^b g(x)dx$
   - Integrals distribute
   - Like adding areas
   - Preserves operations

3. **Constant Multiple**:
   - $\int_a^b cf(x)dx = c\int_a^b f(x)dx$
   - Constants come out
   - Scaling property
   - Like area scaling

#### Advanced Properties
1. **Split Interval**:
   - $\int_a^b f(x)dx = \int_a^c f(x)dx + \int_c^b f(x)dx$
   - Any point c between a and b
   - Additive property
   - Useful for complex problems

2. **Comparison**:
   - If f(x) ≥ g(x), then $\int_a^b f(x)dx ≥ \int_a^b g(x)dx$
   - Area comparison
   - Inequality preservation
   - Important for estimation

### Common Applications
1. **Area**:
   - Between curve and x-axis
   - Between two curves
   - Absolute value for total area

2. **Distance**:
   - From velocity
   - Total vs. net
   - Direction matters

3. **Average Value**:
   - $f_{avg} = \frac{1}{b-a}\int_a^b f(x)dx$
   - Mean value theorem
   - Representative value
   - Like center of mass

## 3. Integration Techniques 🔄 {#techniques}

### U-Substitution
#### Understanding the Method
Think of it as:
- Chain rule in reverse
- Simplifying complex integrals
- Pattern recognition
- Strategic substitution

#### Process
1. **Identify Parts**:
   - Look for composite function
   - Find derivative pattern
   - Choose u carefully
   - Consider du

2. **Set Up**:
   - Write u = inner function
   - Find du/dx
   - Solve for dx
   - Rewrite integral

3. **Integrate**:
   - Work in terms of u
   - Use basic antiderivatives
   - Keep track of constants
   - Remember +C

4. **Back Substitute**:
   - Replace u with original
   - Check answer
   - Verify domain
   - Simplify if needed

#### Example Walkthrough
Evaluate $\int x\cos(x^2)dx$
1. **Choose u**:
   - Let u = x²
   - du = 2x dx
   - x dx = du/2
2. **Rewrite**:
   - $\int \cos(u)\frac{du}{2}$
3. **Integrate**:
   - $\frac{1}{2}\sin(u) + C$
4. **Substitute back**:
   - $\frac{1}{2}\sin(x^2) + C$

### Integration by Parts
#### Formula Understanding
$\int u dv = uv - \int v du$

Think of it as:
- Product rule backwards
- Strategic choice of parts
- Trading complexity
- Systematic approach

#### LIATE Order
Choose u from left:
- **L**ogarithmic
- **I**nverse trig
- **A**lgebraic
- **T**rigonometric
- **E**xponential

#### Process
1. **Choose Parts**:
   - Select u using LIATE
   - Find dv
   - Calculate v
   - Set up formula

2. **New Integral**:
   - Often simpler
   - Sometimes same form
   - May need iteration
   - Watch for patterns

## 4. Applications 📊 {#applications}

### Understanding Applications
Integration solves real-world accumulation problems. Think of it as:
- Finding total quantities from rates
- Calculating areas and volumes
- Determining accumulated change
- Measuring physical quantities

### Area Calculations
#### Between Curves
$A = \int_a^b [f(x) - g(x)]dx$

#### Process
1. **Find Intersection Points**:
   - Solve f(x) = g(x)
   - These are bounds
   - Check crossings
   - Verify domain

2. **Set Up Integral**:
   - Top minus bottom
   - Check orientation
   - Consider absolute value
   - Verify bounds

3. **Evaluate**:
   - Use appropriate technique
   - Check units
   - Verify reasonableness
   - Consider symmetry

#### Example Walkthrough
Find area between y = x² and y = x from x = 0 to x = 1
1. **Identify curves**:
   - Upper: f(x) = x
   - Lower: g(x) = x²
2. **Set up integral**:
   - $A = \int_0^1 (x - x^2)dx$
3. **Evaluate**:
   - $= [\frac{x^2}{2} - \frac{x^3}{3}]_0^1$
   - $= (\frac{1}{2} - \frac{1}{3}) - (0 - 0)$
   - $= \frac{1}{6}$ square units

### Volume Calculations
#### Understanding Methods
1. **Disk Method**:
   - $V = \pi\int_a^b [f(x)]^2dx$
   - Rotating around x-axis
   - Circular cross sections
   - Like stacking circles

2. **Washer Method**:
   - $V = \pi\int_a^b [R(x)^2 - r(x)^2]dx$
   - Nested cylinders
   - Hollow shapes
   - Difference of disks

3. **Shell Method**:
   - $V = 2\pi\int_a^b xf(x)dx$
   - Cylindrical shells
   - Often easier
   - Alternative approach

#### Method Selection
1. **Choose Disk/Washer When**:
   - Rotating around horizontal line
   - Simple function squared
   - Clear outer/inner functions
   - Straightforward bounds

2. **Choose Shell When**:
   - Rotating around vertical line
   - Complex functions
   - Multiple regions
   - Easier integration

#### Common Mistakes
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

### Other Applications
#### Work and Pressure
- $W = \int_a^b F(x)dx$
- Force times distance
- Variable force
- Accumulation of effort

#### Average Value
- $f_{avg} = \frac{1}{b-a}\int_a^b f(x)dx$
- Mean value theorem
- Representative value
- Typical behavior

## 5. Fundamental Theorem of Calculus 📐 {#ftc}

### Understanding FTC
The bridge between derivatives and integrals. Think of it as:
- Undoing differentiation
- Connecting rates to totals
- Simplifying calculations
- Unifying calculus concepts

### Part 1 (FTC1)
#### Statement
If F'(x) = f(x), then:
$\frac{d}{dx}\int_a^x f(t)dt = f(x)$

#### Interpretation
- Derivative undoes integration
- Rate of accumulation
- Instantaneous change
- Local behavior

#### Applications
1. **Finding Derivatives**:
   - Of integral functions
   - Variable upper limit
   - Chain rule needed
   - Check conditions

2. **Theoretical**:
   - Proves relationships
   - Justifies shortcuts
   - Connects concepts
   - Foundation for calculus

### Part 2 (FTC2)
#### Statement
$\int_a^b f(x)dx = F(b) - F(a)$

#### Understanding
- Evaluate at endpoints
- Net change
- Total accumulation
- Difference of states

#### Process
1. **Find Antiderivative**:
   - Look for patterns
   - Use basic rules
   - Consider techniques
   - Verify derivative

2. **Evaluate**:
   - Plug in bounds
   - Subtract results
   - Check signs
   - Verify units

#### Example Walkthrough
Evaluate $\int_0^2 x^3dx$
1. **Find F(x)**:
   - $F(x) = \frac{x^4}{4}$
2. **Evaluate bounds**:
   - F(2) = 16/4 = 4
   - F(0) = 0
3. **Subtract**:
   - 4 - 0 = 4

### Common Mistakes
1. **Conceptual**:
   - Confusing parts 1 and 2
   - Wrong variable use
   - Missing conditions
   - Integration errors

2. **Computational**:
   - Wrong antiderivative
   - Bound substitution
   - Sign errors
   - Constant confusion

### Practice Strategies
1. **Understanding**:
   - Draw diagrams
   - Use analogies
   - Connect concepts
   - Verify results

2. **Problem Solving**:
   - Identify theorem needed
   - Check conditions
   - Show clear work
   - Verify answer

## 📝 AP-Style Examples

### Example 1: FTC Application
Find $\frac{d}{dx}\int_2^x t^3dt$

**Solution**:
1. Use FTC1: Result is x³
2. No need to integrate
3. Upper limit becomes variable
4. Lower limit doesn't affect derivative

### Example 2: Area Calculation
Find area between y = x² and y = √x from x = 0 to x = 1

**Solution**:
1. **Compare functions**:
   - √x > x² on (0,1)
2. **Set up integral**:
   - $\int_0^1 (\sqrt{x} - x^2)dx$
3. **Integrate**:
   - $[\frac{2x^{3/2}}{3} - \frac{x^3}{3}]_0^1$
4. **Evaluate**:
   - $\frac{2}{3} - \frac{1}{3} = \frac{1}{3}$

## 💡 Success Strategies

### 1. Integration Method Selection
- Try simplest method first
- Look for patterns
- Consider alternatives
- Check answer reasonableness

### 2. Common Mistakes
- Wrong technique choice
- Missing +C
- Bound errors
- Sign mistakes

### 3. Calculator Tips
- Check with numerical integration
- Graph to verify area
- Use for complex calculations
- Verify endpoints

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show work**:
   - Method selection
   - Step-by-step process
   - Final evaluation

2. **Common Questions**:
   - Area/Volume
   - FTC applications
   - Average value
   - Accumulation

### Multiple Choice Strategy
1. **Consider**:
   - Integration techniques
   - Properties of integrals
   - FTC applications

2. **Check**:
   - Units
   - Sign
   - Reasonableness

---

*💡 Pro Tip: Integration is the inverse of differentiation. Always check your answer by differentiating!* 