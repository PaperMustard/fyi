
> **AP Exam Weight**: 10-12% | Multiple Choice: 4-6 questions | Free Response: Part of several questions

## 📚 Table of Contents
1. [Understanding Limits](#limits)
2. [Limit Laws](#laws)
3. [Continuity](#continuity)
4. [Special Limits](#special)
5. [Techniques](#techniques)

## 📝 Chapter Overview
This chapter covers the foundational concepts of calculus - limits and continuity. Understanding these concepts is crucial as they form the basis for derivatives and integrals.

## 🎯 Learning Objectives
After completing this chapter, you should be able to:
- Evaluate limits using various methods
- Analyze one-sided limits
- Identify and classify discontinuities
- Apply the Intermediate Value Theorem
- Use the Squeeze Theorem

## 📚 Key Concepts

## 1. Understanding Limits 📊 {#limits}

### What is a Limit?
A limit describes what a function approaches as x gets closer and closer to a specific value. Think of it as:
- Walking towards a doorway but never quite reaching it
- Zooming in on a graph closer and closer
- Getting arbitrarily close to a value
- The "tendency" of a function

### Limit Definition
$\lim_{x \to a} f(x) = L$ means the values of f(x) get arbitrarily close to L as x gets arbitrarily close to a

#### Intuitive Understanding
- Values approach L from both sides
- Function need not be defined at point a
- Actual value at a doesn't matter
- Only care about "nearby" behavior

#### Process for Finding Limits
1. Try direct substitution
2. Make a table of values
3. Graph the function
4. Use algebraic techniques if needed

#### Example Walkthrough
Find $\lim_{x \to 2} \frac{x^2-4}{x-2}$
1. Direct substitution gives $\frac{0}{0}$ (indeterminate)
2. Factor: $\frac{(x+2)(x-2)}{x-2}$
3. Cancel: $x+2$
4. Evaluate at x = 2: $2+2 = 4$

### One-Sided Limits
#### Left-Hand Limit
- Approaching from values less than a
- Notation: $\lim_{x \to a^-} f(x)$
- Example: For |x| as x→0 from left = 0⁻

#### Right-Hand Limit
- Approaching from values greater than a
- Notation: $\lim_{x \to a^+} f(x)$
- Example: For |x| as x→0 from right = 0⁺

#### Key Points
- Two-sided limit exists only if both sides are equal
- Common in piecewise functions
- Important for continuity analysis

### Infinite Limits
#### Types
1. **Vertical Asymptotes**
   - Function grows without bound
   - Example: $\lim_{x \to 0} \frac{1}{x^2}$
   - Look for division by zero

2. **Horizontal Asymptotes**
   - Function approaches finite value
   - Example: $\lim_{x \to \infty} \frac{1}{x}$
   - Important for end behavior

#### Analysis Process
1. Make a table of values
2. Look at behavior from both sides
3. Consider domain restrictions
4. Graph for visualization

## 2. Limit Laws 📐 {#laws}

### Basic Laws
The foundation for evaluating complex limits. Think of these as:
- Rules for breaking down complicated limits
- Tools for simplifying calculations
- Building blocks for proofs
- Essential patterns to recognize

#### Sum/Difference Law
$\lim_{x \to a} [f(x) \pm g(x)] = \lim_{x \to a} f(x) \pm \lim_{x \to a} g(x)$

#### Product Law
$\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$

#### Quotient Law
$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$, if denominator ≠ 0

### Common Applications
1. **Polynomial Functions**
   - Direct substitution usually works
   - Factor when needed
   - Cancel common factors

2. **Rational Functions**
   - Check for zero denominator
   - Factor if necessary
   - Look for asymptotes

3. **Radical Expressions**
   - Rationalize when needed
   - Consider domain restrictions
   - Watch for extraneous solutions

## 3. Continuity 🔄 {#continuity}

### Understanding Continuity
A function is continuous if you can draw it without lifting your pencil. Three conditions:

#### Conditions for Continuity
1. f(a) exists (function defined)
2. $\lim_{x \to a} f(x)$ exists (limit exists)
3. $\lim_{x \to a} f(x) = f(a)$ (limit equals value)

### Types of Discontinuities
#### 1. Removable (Point/Hole)
- Single point missing
- Limit exists but ≠ function value
- Can be "fixed" by redefining point
- Example: $\frac{x^2-1}{x-1}$ at x = 1

#### 2. Jump
- Left and right limits exist but differ
- Cannot be "fixed"
- Common in piecewise functions
- Example: Step functions

#### 3. Infinite
- Limit doesn't exist (infinite)
- Vertical asymptote
- Example: $\frac{1}{x}$ at x = 0

#### 4. Essential
- Most severe type
- No limit exists
- Example: sin(1/x) at x = 0

### Intermediate Value Theorem (IVT)
#### Statement
If f is continuous on [a,b] and k is between f(a) and f(b), then there exists c in [a,b] where f(c) = k

#### Applications
1. **Finding Roots**
   - Prove existence of solutions
   - Approximate root location
   - Verify calculator results

2. **Practical Uses**
   - Temperature variations
   - Motion problems
   - Economic models

## 4. Special Limits 📈 {#special}

### Trigonometric Limits
1. $\lim_{x \to 0} \frac{\sin x}{x} = 1$
2. $\lim_{x \to 0} \frac{1-\cos x}{x^2} = \frac{1}{2}$
3. $\lim_{x \to 0} \frac{\tan x}{x} = 1$

### Important Limits
1. $\lim_{x \to \infty} (1 + \frac{1}{x})^x = e$
2. $\lim_{x \to 0} \frac{e^x-1}{x} = 1$

### Squeeze Theorem
#### Statement
If g(x) ≤ f(x) ≤ h(x) and $\lim_{x \to a} g(x) = \lim_{x \to a} h(x) = L$, then $\lim_{x \to a} f(x) = L$

#### Applications
1. **Trigonometric Limits**
   - $\lim_{x \to 0} x\sin(\frac{1}{x})$
   - Bounded functions
   - Oscillating functions

2. **Process**
   - Find bounding functions
   - Verify inequalities
   - Show bounds converge
   - Conclude about middle function

## 5. Techniques 🎯 {#techniques}

### Direct Substitution
- Try first
- Works for continuous functions
- Simplest approach
- Watch for undefined values

### Algebraic Manipulation
#### Factoring
1. Look for common factors
2. Standard factoring patterns
3. Cancel when possible
4. Check domain

#### Rationalization
1. Multiply by conjugate
2. Clear radicals
3. Simplify result
4. Verify no domain changes

### L'Hôpital's Rule
#### When to Use
- 0/0 form
- ∞/∞ form
- Must be indeterminate

#### Process
1. Check if indeterminate
2. Take derivative of numerator
3. Take derivative of denominator
4. Evaluate limit

## 📝 Practice Problems

### Basic Limits
1. Evaluate lim(x→2) (x²-4)/(x-2)
2. Find lim(x→0) sin(x)/x
3. Calculate lim(x→∞) (2x+1)/(x-3)

### One-Sided Limits
1. Find both one-sided limits of |x| at x=0
2. Evaluate lim(x→1⁺) 1/(x-1)
3. Analyze lim(x→0) x/|x|

### Continuity
1. Find all discontinuities of f(x) = (x²-9)/(x-3)
2. Analyze continuity of piecewise function
3. Make a function continuous by finding parameter values

### IVT Applications
1. Prove x⁵-x-1=0 has a solution
2. Show existence of a specific value
3. Apply to real-world scenario

### Squeeze Theorem
1. Prove lim(x→0) xsin(1/x) = 0
2. Show lim(x→0) x²cos(1/x) = 0
3. Apply to bounded function

## 🔍 Common Mistakes to Avoid
1. Forgetting to check both sides for limits
2. Assuming limit equals function value
3. Misidentifying discontinuity types
4. Not verifying IVT conditions
5. Incorrect squeeze theorem bounds

## 📚 Additional Resources
1. Khan Academy: Limits and Continuity
2. AP Classroom Videos
3. Practice FRQ questions
4. Online graphing calculators

## ✅ Chapter Checklist
- [ ] Understand limit definition
- [ ] Master limit calculation techniques
- [ ] Classify discontinuities
- [ ] Apply IVT correctly
- [ ] Use Squeeze Theorem effectively
- [ ] Complete practice problems
- [ ] Review common mistakes

## 📝 AP-Style Examples

### Example 1: Limit Evaluation
Find $\lim_{x \to 2} \frac{x^2-4}{x-2}$

**Solution**:
1. Factor: $\frac{(x+2)(x-2)}{x-2}$
2. Cancel: $x+2$
3. Evaluate: $\lim_{x \to 2} (x+2) = 4$

### Example 2: Continuity
Is f(x) = $\begin{cases} 
x^2 & x < 1 \\
2x-1 & x \geq 1
\end{cases}$ continuous at x = 1?

**Check**:
1. f(1) exists = 1
2. $\lim_{x \to 1^-} f(x) = 1$
3. $\lim_{x \to 1^+} f(x) = 1$
Therefore, continuous at x = 1

## 💡 Success Strategies

### 1. Limit Evaluation Steps
1. Try direct substitution
2. Look for special limits
3. Try algebraic techniques
4. Consider one-sided limits

### 2. Common Mistakes
- Forgetting to check both sides
- Division by zero
- Incorrect factoring
- Missing discontinuities

### 3. Calculator Tips
- Graph to check reasonableness
- Use table feature
- Zoom for better view
- Check window settings

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show work clearly**
   - Algebraic steps
   - Reasoning
   - Conclusions

2. **Include**:
   - Limit notation
   - Equal signs
   - Units if applicable

### Multiple Choice Strategy
1. **Consider**:
   - Graphical interpretation
   - Algebraic approach
   - Special cases

2. **Check**:
   - Reasonableness
   - Sign changes
   - Asymptotes

---

*💡 Pro Tip: Understanding limits is fundamental to calculus. Master these concepts as they appear throughout the course!* 