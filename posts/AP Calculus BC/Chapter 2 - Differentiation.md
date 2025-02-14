
> **AP Exam Weight**: 25-35% | Multiple Choice: 10-14 questions | Free Response: Major focus in several questions

## 📚 Table of Contents
1. [Definition](#definition)
2. [Basic Rules](#rules)
3. [Advanced Rules](#advanced)
4. [Applications](#applications)
5. [Optimization](#optimization)

## 1. Definition of Derivative 📊 {#definition}

### Understanding the Derivative
The derivative measures how quickly a function is changing at any point. Think of it as:
- The instantaneous speedometer in your car
- The slope of a mountain at a specific point
- The rate of population growth at a moment
- The sensitivity of temperature change

### Limit Definition
$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

#### Intuitive Understanding
- The derivative is a special limit
- We're finding the slope of increasingly closer secant lines
- As h gets tiny (approaches 0), secant line becomes tangent line
- Think of zooming in until curve looks like a straight line

#### Process for Finding Limit Definition
1. Start with difference quotient
2. Substitute and simplify
3. Take limit as h approaches 0
4. Simplify result

#### Example Walkthrough
Find f'(x) for f(x) = x²
1. Write quotient: $\lim_{h \to 0} \frac{(x+h)^2 - x^2}{h}$
2. Expand: $\lim_{h \to 0} \frac{x^2 + 2xh + h^2 - x^2}{h}$
3. Simplify: $\lim_{h \to 0} \frac{2xh + h^2}{h} = \lim_{h \to 0} (2x + h)$
4. Result: f'(x) = 2x

### Alternative Form
$f'(a) = \lim_{x \to a} \frac{f(x) - f(a)}{x-a}$

#### When to Use
- Helpful for finding derivatives at specific points
- Useful when function is defined piecewise
- Better for some theoretical proofs
- Equivalent to h-definition

### Interpretations

#### 1. Geometric Interpretation
- Slope of tangent line at point (x, f(x))
- Rate of steepness of curve
- Direction of motion along curve
- Visual representation of rate of change

#### 2. Physical Interpretation
- Instantaneous velocity from position function
- Rate of reaction in chemistry
- Rate of growth in biology
- Rate of change in any quantity

#### 3. Practical Applications
- Market rate of change in economics
- Acceleration in physics
- Population growth rates
- Temperature change rates

### Notation
Different notations emphasize different aspects of derivatives:

#### Leibniz Notation: $\frac{d}{dx}[f(x)]$ or $\frac{dy}{dx}$
- Emphasizes ratio of changes
- Helpful for related rates
- Clear variable dependency
- Standard for differential equations

#### Prime Notation: f'(x)
- Compact and clean
- Good for multiple derivatives (f'', f''')
- Common in theoretical work
- Easy to write quickly

#### Newton's Notation: $\dot{y}$
- Used mainly in physics
- Represents time derivatives
- Multiple dots for higher derivatives
- Compact for motion problems

### Common Misconceptions
1. **The Derivative Is Not**:
   - Average rate of change
   - Slope between two points
   - Change in y over change in x
   - A secant line slope

2. **Common Errors**:
   - Forgetting limit process
   - Confusing average and instantaneous rates
   - Misinterpreting negative derivatives
   - Not checking for differentiability

3. **Points of Confusion**:
   - Corner points
   - Vertical tangent lines
   - Points of discontinuity
   - Infinite derivatives

### Practice Strategies
1. **Understanding the Definition**:
   - Draw secant lines approaching tangent
   - Calculate difference quotients
   - Take limits step by step
   - Verify with graphs

2. **Mastering Interpretations**:
   - Connect to real-world scenarios
   - Practice slope visualization
   - Link to rate problems
   - Use multiple representations

3. **Notation Fluency**:
   - Practice converting between notations
   - Use appropriate notation for context
   - Understand meaning of each symbol
   - Connect to physical meanings

## 2. Basic Rules 📐 {#rules}

### Understanding Basic Derivatives
The foundation of calculus rests on these fundamental rules. Think of them as:
- The basic vocabulary of calculus
- Building blocks for more complex derivatives
- Essential patterns to recognize
- Core rules that never change

### Power Rule
$\frac{d}{dx}[x^n] = nx^{n-1}$

#### How It Works
1. Take the exponent
2. Multiply it by the base
3. Reduce exponent by 1
4. Apply to each term separately

#### Examples
1. $\frac{d}{dx}[x^3] = 3x^2$
2. $\frac{d}{dx}[x^{1/2}] = \frac{1}{2}x^{-1/2}$
3. $\frac{d}{dx}[x^{-2}] = -2x^{-3}$

#### Common Mistakes
- Forgetting to multiply by power
- Adding instead of subtracting exponent
- Mishandling negative exponents
- Confusion with chain rule cases

### Constant Rule
$\frac{d}{dx}[c] = 0$

#### Understanding Why
- Constants don't change
- Their rate of change is zero
- Graph is horizontal line
- No matter what x does, c stays same

### Sum/Difference Rule
$\frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)$

#### Key Concepts
- Derivatives distribute over addition/subtraction
- Each term differentiated separately
- Signs stay the same
- Order doesn't matter

#### Example Walkthrough
Find $\frac{d}{dx}[3x^4 - 2x^2 + 5x - 7]$
1. Split into terms: $(3x^4) + (-2x^2) + (5x) + (-7)$
2. Apply power rule to each:
   - $3 \cdot 4x^3 = 12x^3$
   - $-2 \cdot 2x^1 = -4x$
   - $5 \cdot 1x^0 = 5$
   - $0$ (constant)
3. Combine: $12x^3 - 4x + 5$

### Constant Multiple Rule
$\frac{d}{dx}[cf(x)] = cf'(x)$

#### Applications
- Pull out coefficients
- Keep constants in place
- Multiply after differentiating
- Useful for simplifying

## 3. Advanced Rules 🔄 {#advanced}

### Product Rule
$\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$

#### Understanding the Rule
- Think "first times derivative of second plus second times derivative of first"
- Like FOIL but for derivatives
- Each function takes turns being differentiated
- Other function stays the same

#### Common Applications
1. **Polynomial Products**
   - $(x^2)(x^3)$
   - $(x+1)(x^2-3)$
2. **Trig-Polynomial Combinations**
   - $x\sin(x)$
   - $x^2\cos(x)$
3. **Exponential-Polynomial**
   - $xe^x$
   - $x^2\ln(x)$

#### Example Walkthrough
Find $\frac{d}{dx}[x^2\sin(x)]$
1. Identify f(x) = x² and g(x) = sin(x)
2. Find f'(x) = 2x and g'(x) = cos(x)
3. Apply rule: $(2x)(\sin(x)) + (x^2)(\cos(x))$
4. Result: $2x\sin(x) + x^2\cos(x)$

### Quotient Rule
$\frac{d}{dx}[\frac{f(x)}{g(x)}] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$

#### Memory Device
"Low d-High minus High d-Low over square of below"

#### Key Points
1. Denominator is always squared
2. Numerator follows specific pattern
3. Order matters in subtraction
4. Check for domain restrictions

### Chain Rule
$\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$

#### Visual Understanding
- Think of peeling layers of an onion
- Work from outside in
- Multiply results together
- Keep track of inside function

#### Common Patterns
1. **Power Functions**
   - $(x^2 + 1)^3$
   - $\sqrt{x^2 + 1}$
2. **Exponentials**
   - $e^{x^2}$
   - $2^{sin(x)}$
3. **Trigonometric**
   - $\sin(x^2)$
   - $\tan(e^x)$

## 4. Applications 🎯 {#applications}

### Related Rates
Understanding how different changing quantities relate to each other.

#### Problem-Solving Process
1. **Draw a Diagram**
   - Label variables
   - Show relationships
   - Mark known values
   - Indicate what's changing

2. **Write an Equation**
   - Connect variables
   - Use geometric formulas
   - Consider relationships
   - Keep variables as functions of time

3. **Differentiate**
   - Use chain rule
   - Remember implicit differentiation
   - Keep track of units
   - Watch for constant terms

4. **Solve**
   - Substitute known values
   - Solve for unknown rate
   - Check units
   - Verify answer makes sense

#### Common Scenarios
1. **Geometric**
   - Growing circles
   - Sliding ladders
   - Changing triangles
   - Expanding volumes

2. **Real-World**
   - Water filling tanks
   - Shadow lengths
   - Distance problems
   - Cost relationships

### Linear Approximation
$f(x) \approx f(a) + f'(a)(x-a)$

#### Understanding the Concept
- Tangent line approximation
- Best near x = a
- First-order approximation
- Local linear behavior

#### Applications
1. **Estimation**
   - Quick calculations
   - Error bounds
   - Near-point values
   - Complex functions

2. **Error Analysis**
   - Maximum error
   - Interval of accuracy
   - Improvement methods
   - Tolerance levels

## 5. Optimization 📈 {#optimization}

### Understanding Optimization
Finding maximum or minimum values in real-world situations.

### Finding Extrema
#### Process
1. **Identify Variables**
   - What changes
   - What's constrained
   - What to optimize
   - Relationship between variables

2. **Write Equation**
   - Express goal in terms of one variable
   - Use constraints
   - Simplify if possible
   - Check units

3. **Find Critical Points**
   - Set derivative = 0
   - Find undefined points
   - Check endpoints
   - List all candidates

4. **Test Points**
   - First derivative test
   - Second derivative test
   - Endpoint comparison
   - Verify answer makes sense

### Testing Methods

#### First Derivative Test
- f'(x) changes - to + : Local minimum
- f'(x) changes + to - : Local maximum
- Check behavior around critical points
- Consider domain restrictions

#### Second Derivative Test
- f''(x) > 0 : Local minimum
- f''(x) < 0 : Local maximum
- f''(x) = 0 : Inconclusive
- More efficient but not always applicable

### Common Applications
1. **Geometric**
   - Maximum area
   - Minimum perimeter
   - Optimal volume
   - Best dimensions

2. **Business**
   - Maximum profit
   - Minimum cost
   - Optimal production
   - Best pricing

3. **Physics**
   - Minimal time
   - Maximum distance
   - Optimal angle
   - Energy efficiency

## 📝 AP-Style Examples

### Example 1: Chain Rule
Find $\frac{d}{dx}[\sin(e^{2x})]$

**Solution**:
1. Outer function: sin
2. Inner function: $e^{2x}$
3. $f'(x) = \cos(e^{2x}) \cdot e^{2x} \cdot 2$
4. $f'(x) = 2e^{2x}\cos(e^{2x})$

### Example 2: Related Rates
A spherical balloon expands at 2 cm³/s. How fast is the radius increasing when r = 5 cm?

**Solution**:
1. Volume formula: V = 4/3πr³
2. Differentiate: dV/dt = 4πr²·dr/dt
3. Substitute: 2 = 4π(5)²·dr/dt
4. Solve for dr/dt

## 💡 Success Strategies

### 1. Choosing the Right Rule
- Multiple terms → Sum/Difference Rule
- Multiplication → Product Rule
- Division → Quotient Rule
- Composition → Chain Rule

### 2. Common Mistakes
- Forgetting chain rule
- Product vs. power rule confusion
- Sign errors in quotient rule
- Missing terms in product rule

### 3. Calculator Tips
- Check with numerical derivative
- Graph to verify reasonableness
- Use for complex calculations
- Verify critical points

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show all work**
   - Rule identification
   - Step-by-step process
   - Final simplification

2. **Common Questions**
   - Related rates
   - Optimization
   - Chain rule applications
   - Motion problems

### Multiple Choice Strategy
1. **Consider**
   - Basic vs. advanced rules
   - Multiple approaches
   - Common derivatives

2. **Check**
   - Units
   - Sign
   - Domain restrictions

---

*💡 Pro Tip: Mastering differentiation rules is crucial - they're the foundation for most calculus applications!* 