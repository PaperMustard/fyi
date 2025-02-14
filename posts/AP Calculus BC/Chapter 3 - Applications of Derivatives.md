
> **AP Exam Weight**: 25-35% | Multiple Choice: 10-14 questions | Free Response: Major focus in several questions

## 📚 Table of Contents
1. [Mean Value Theorem](#mvt)
2. [Extrema & Optimization](#extrema)
3. [Related Rates](#rates)
4. [Curve Analysis](#curves)
5. [L'Hôpital's Rule](#lhopital)

## 1. Mean Value Theorem 📊 {#mvt}

### Understanding MVT
The Mean Value Theorem connects average and instantaneous rates of change. Think of it as:
- A car's average speed vs. instantaneous speed
- The exact moment you're going the average speed
- A mathematical guarantee about derivatives
- A tool for proving other theorems

### Statement
If f is continuous on [a,b] and differentiable on (a,b), then there exists c in (a,b) where:
$f'(c) = \frac{f(b)-f(a)}{b-a}$

#### Intuitive Understanding
- Left side: instantaneous rate at some point
- Right side: average rate over interval
- Must match at least once
- Like hitting your average speed during a trip

#### Verification Process
1. Check continuity on [a,b]
2. Check differentiability on (a,b)
3. Calculate average rate
4. Find where derivative equals average rate

#### Example Walkthrough
Show MVT applies to f(x) = x² on [1,4]
1. **Check conditions**:
   - Continuous: polynomials are continuous
   - Differentiable: f'(x) = 2x exists everywhere
2. **Calculate average rate**:
   - $\frac{f(4)-f(1)}{4-1} = \frac{16-1}{3} = 5$
3. **Find c**:
   - f'(c) = 2c = 5
   - c = 2.5
4. **Verify**:
   - c is in (1,4)
   - f'(2.5) = 5 matches average rate

### Rolle's Theorem
A special case of MVT where f(a) = f(b)

#### Key Insights
- Guarantees a horizontal tangent
- Like finding a peak or valley
- Used in proof of MVT
- Important for existence proofs

#### Applications
1. **Proving Zero Existence**
   - Finding roots of derivatives
   - Showing turning points exist
   - Locating horizontal tangents
   - Maximum/minimum locations

2. **Real-World Examples**
   - Return to starting height
   - Periodic motion
   - Temperature cycles
   - Financial breakeven points

### Common Applications

#### 1. Average vs. Instantaneous Rate
- Speed at a moment vs. average speed
- Growth rates in biology
- Reaction rates in chemistry
- Economic rates of change

#### 2. Existence Proofs
- Showing solutions exist
- Finding intervals containing solutions
- Proving inequalities
- Demonstrating properties

#### 3. Estimation
- Error bounds
- Approximation guarantees
- Interval calculations
- Numerical analysis

### Common Mistakes
1. **Condition Checking**
   - Forgetting to verify continuity
   - Missing discontinuities
   - Not checking differentiability
   - Ignoring endpoint behavior

2. **Interpretation**
   - Confusing average and instantaneous rates
   - Misidentifying c value
   - Wrong interval notation
   - Incomplete conclusions

3. **Application**
   - Wrong formula use
   - Incorrect interval selection
   - Missing critical assumptions
   - Incomplete verification

### Practice Strategies
1. **Understanding the Theorem**
   - Draw diagrams
   - Use real-world analogies
   - Connect to other concepts
   - Verify conditions carefully

2. **Problem Solving**
   - List given information
   - Check conditions systematically
   - Show clear work
   - Verify conclusions

3. **Common Scenarios**
   - Motion problems
   - Rate comparisons
   - Existence proofs
   - Inequality verifications

## 2. Extrema & Optimization 🎯 {#extrema}

### Understanding Extrema
Finding maximum and minimum values is crucial for optimization. Think of it as:
- Finding the highest/lowest points
- Locating best/worst scenarios
- Optimizing real-world situations
- Analyzing function behavior

### First Derivative Test
#### Understanding the Test
- f'(x) > 0: Function increasing
- f'(x) < 0: Function decreasing
- f'(x) = 0 or DNE: Critical point

#### Process
1. Find critical points
2. Create number line
3. Test intervals
4. Identify extrema

#### Example Walkthrough
Find extrema of f(x) = x³ - 3x
1. **Find f'(x)**:
   - f'(x) = 3x² - 3
   - = 3(x² - 1)
   - = 3(x+1)(x-1)
2. **Critical points**:
   - x = -1 and x = 1
3. **Test intervals**:
   - x < -1: negative
   - -1 < x < 1: positive
   - x > 1: negative
4. **Conclude**:
   - Local max at x = 1
   - Local min at x = -1

### Second Derivative Test
#### Understanding the Test
At critical point x = c:
- f''(c) > 0: Local minimum
- f''(c) < 0: Local maximum
- f''(c) = 0: Inconclusive

#### When to Use
- Faster than first derivative test
- Only works at critical points
- Requires second derivative
- Must be differentiable twice

### Optimization Process
#### Step-by-Step Approach
1. **Define Variables**
   - Identify what varies
   - Choose appropriate variables
   - Label diagram
   - Note relationships

2. **Write Objective Function**
   - Express quantity to optimize
   - Use given constraints
   - Simplify if possible
   - Check units

3. **Find Domain Restrictions**
   - Physical constraints
   - Geometric limitations
   - Practical bounds
   - Mathematical restrictions

4. **Locate Critical Points**
   - Take derivative
   - Set equal to zero
   - Solve equation
   - Check endpoints

5. **Test Points**
   - Use second derivative test
   - Compare values
   - Check endpoints
   - Verify answer makes sense

#### Common Applications
1. **Geometric**
   - Maximize area/volume
   - Minimize perimeter
   - Optimize dimensions
   - Find best shapes

2. **Business**
   - Maximize profit
   - Minimize cost
   - Optimize production
   - Best pricing strategies

3. **Physics**
   - Minimize time
   - Maximize distance
   - Optimize angles
   - Energy efficiency

## 3. Related Rates 🔄 {#rates}

### Understanding Related Rates
Problems where multiple quantities change with respect to time. Think of it as:
- Connected rates of change
- Chain rule with time
- Implicit differentiation
- Real-world applications

### Problem-Solving Process
#### 1. Draw and Label Diagram
- Show all variables
- Mark known values
- Indicate what's changing
- Show relationships

#### 2. Write Equation
- Connect variables
- Use geometric formulas
- Consider relationships
- Keep time dependence

#### 3. Differentiate
- Use chain rule
- Remember implicit differentiation
- Keep track of units
- Watch for constant terms

#### 4. Solve
- Substitute known values
- Solve for unknown rate
- Check units
- Verify reasonableness

### Common Scenarios
#### 1. Geometric Shapes
- Growing circles
- Changing triangles
- Expanding volumes
- Moving points

#### 2. Real-World Applications
- Water filling tanks
- Shadow problems
- Distance/velocity
- Cost relationships

## 4. Curve Analysis 📈 {#curves}

### Understanding Curve Analysis
A systematic way to understand function behavior. Think of it as:
- Creating a function's complete profile
- Mapping out all key features
- Understanding overall behavior
- Predicting function patterns

### First Derivative Information
#### Understanding f'(x)
- Sign tells increasing/decreasing
- Zeros give critical points
- DNE points are critical
- Connects to motion/rates

#### Key Features
1. **Increasing/Decreasing**
   - f'(x) > 0: Increasing
   - f'(x) < 0: Decreasing
   - Create sign chart
   - Mark transitions

2. **Critical Points**
   - Where f'(x) = 0
   - Where f'(x) DNE
   - Potential extrema
   - Important features

3. **Local Extrema**
   - Use first derivative test
   - Compare neighboring intervals
   - Consider domain edges
   - Verify with second derivative

4. **Tangent Lines**
   - Slope = f'(x)
   - Point-slope form
   - Normal lines
   - Approximations

### Second Derivative Information
#### Understanding f''(x)
- Sign tells concavity
- Zeros give inflection points
- Confirms extrema type
- Rate of change of slope

#### Key Features
1. **Concavity**
   - f''(x) > 0: Concave up
   - f''(x) < 0: Concave down
   - Like shape of smile/frown
   - Changes at inflection points

2. **Inflection Points**
   - Where f''(x) = 0 or DNE
   - Concavity changes
   - Important for shape
   - Often symmetric

3. **Maximum/Minimum Verification**
   - Second derivative test
   - Confirms extrema type
   - More efficient than first derivative
   - Not always conclusive

4. **Linear Approximation**
   - Tangent line approximation
   - Error bounds
   - Local behavior
   - Differentials

### Curve Sketching Process
#### Step-by-Step Approach
1. **Find Domain**
   - Check denominators
   - Check radicals
   - Consider context
   - Note restrictions

2. **Find Intercepts**
   - x-intercepts: f(x) = 0
   - y-intercept: f(0)
   - Important points
   - Cross-check with domain

3. **Find Asymptotes**
   - Horizontal: $\lim_{x \to \pm\infty} f(x)$
   - Vertical: Where denominator = 0
   - Slant: Divide by highest power
   - Guide overall shape

4. **Analyze First Derivative**
   - Find f'(x)
   - Solve f'(x) = 0
   - Create sign chart
   - Mark critical points

5. **Analyze Second Derivative**
   - Find f''(x)
   - Solve f''(x) = 0
   - Determine concavity
   - Mark inflection points

6. **Sketch the Curve**
   - Plot key points
   - Follow sign charts
   - Respect asymptotes
   - Connect smoothly

#### Common Mistakes
1. **Process Errors**
   - Skipping steps
   - Missing key points
   - Wrong asymptotes
   - Inconsistent signs

2. **Graphing Errors**
   - Wrong concavity
   - Missing features
   - Incorrect crossings
   - Scale issues

## 5. L'Hôpital's Rule 🔄 {#lhopital}

### Understanding L'Hôpital's Rule
A powerful tool for evaluating indeterminate limits. Think of it as:
- Converting "bad" limits to "good" ones
- Using derivatives to simplify
- Finding true limiting behavior
- Resolving uncertainty

### Indeterminate Forms
#### Types and Recognition
1. **$\frac{0}{0}$ Form**
   - Both numerator and denominator → 0
   - Like $\lim_{x \to 0} \frac{\sin x}{x}$
   - Most common type
   - Often from cancellation

2. **$\frac{\infty}{\infty}$ Form**
   - Both parts grow without bound
   - Like $\lim_{x \to \infty} \frac{x^2}{x}$
   - Check growth rates
   - Consider simplification first

3. **Other Forms**
   - $0 \cdot \infty$: Rewrite as fraction
   - $\infty - \infty$: Common denominator
   - $0^0$, $1^\infty$, $\infty^0$: Use ln

### Application Process
#### Step-by-Step Approach
1. **Verify Indeterminate Form**
   - Check limit of each part
   - Confirm indeterminate
   - Classify form
   - Consider alternatives

2. **Apply Rule**
   - Take derivatives of top and bottom
   - Keep limit statement
   - Simplify if possible
   - Check if still indeterminate

3. **Evaluate Result**
   - Compute final limit
   - Verify answer makes sense
   - Check domain issues
   - Consider context

#### Example Walkthrough
Find $\lim_{x \to 0} \frac{e^x - 1}{x}$
1. **Check form**:
   - Top → 0
   - Bottom → 0
   - $\frac{0}{0}$ form
2. **Apply L'Hôpital's**:
   - $\lim_{x \to 0} \frac{e^x}{1} = 1$
3. **Verify**:
   - Result is finite
   - Makes sense geometrically
   - Matches calculator

### Common Mistakes
1. **Application Errors**
   - Using when not indeterminate
   - Wrong derivatives
   - Missing steps
   - Domain issues

2. **Process Errors**
   - Not checking form
   - Applying too soon
   - Missing simpler methods
   - Algebraic mistakes

### Practice Strategies
1. **Form Recognition**
   - Make table of forms
   - Practice identification
   - Know alternatives
   - Check thoroughly

2. **Technique Selection**
   - Try algebra first
   - Consider substitution
   - Look for patterns
   - Use L'Hôpital's last

3. **Verification**
   - Use calculator
   - Check reasonableness
   - Consider graph
   - Confirm work

## 📝 AP-Style Examples

### Example 1: Optimization
A box with square base and open top must have volume 1000 cubic inches. Find dimensions that minimize surface area.

**Solution**:
1. Let x = side length of base
2. Let h = height
3. Volume: $x^2h = 1000$
4. Surface area: $S = x^2 + 4xh$
5. Solve: $h = \frac{1000}{x^2}$
6. $S = x^2 + \frac{4000}{x}$
7. $S' = 2x - \frac{4000}{x^2}$
8. Solve $S' = 0$: $x = 10$
9. Therefore: x = 10, h = 10

### Example 2: Related Rates
A conical water tank with radius 6 ft and height 10 ft is being filled at 3 cubic feet per minute. How fast is the height increasing when the water is 4 ft deep?

**Solution**:
1. Volume formula: $V = \frac{1}{3}\pi r^2h$
2. Similar triangles: $\frac{r}{h} = \frac{6}{10}$
3. Differentiate: $\frac{dV}{dt} = \pi r^2\frac{dh}{dt}$
4. Solve for $\frac{dh}{dt}$

## 💡 Success Strategies

### 1. Optimization Problems
- Draw diagram
- Define variables
- Write constraint equation
- Consider domain
- Check endpoints

### 2. Related Rates
- Draw picture
- Label variables
- Write equation
- Differentiate
- Substitute values

### 3. Common Mistakes
- Wrong units
- Missing critical points
- Incomplete testing
- Domain errors

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show work clearly**
   - Label steps
   - Include units
   - Justify conclusions

2. **Common Questions**
   - Optimization
   - Related rates
   - Curve sketching
   - Rate comparisons

### Multiple Choice Strategy
1. **Consider**
   - Multiple approaches
   - Graphical insights
   - Sign analysis

2. **Check**
   - Units
   - Reasonableness
   - Domain restrictions

---

*💡 Pro Tip: Applications of derivatives form the core of many real-world problems. Practice interpreting word problems carefully!* 