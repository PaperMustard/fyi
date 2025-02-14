
> **AP Exam Weight**: 15-25% | Multiple Choice: 6-10 questions | Free Response: Usually 1 full question

## 📚 Table of Contents
1. [Sequence Basics](#sequences)
2. [Series Tests](#tests)
3. [Power Series](#power)
4. [Taylor Series](#taylor)
5. [Error Bounds](#error)

## 1. Sequence Basics 📊 {#sequences}

### Understanding Sequences
A sequence is a list of numbers in order. Think of it as:
- Pattern of values following a rule
- Function with domain of natural numbers
- Stepping stones to series
- Ordered list of terms

### Basic Concepts
#### Notation
- {aₙ} represents a sequence
- aₙ is the nth term
- Explicit vs. recursive form
- Index notation

#### Example Walkthrough
Find the first 4 terms of aₙ = n²/(n+1)
1. **n = 1**:
   - a₁ = 1²/(1+1) = 1/2
2. **n = 2**:
   - a₂ = 2²/(2+1) = 4/3
3. **n = 3**:
   - a₃ = 9/4
4. **n = 4**:
   - a₄ = 16/5

### Convergence of Sequences
#### Process for Finding Limits
1. **Identify Pattern**:
   - Look for trend
   - Consider behavior as n grows
   - Watch for special forms
   - Consider asymptotes

2. **Calculate Limit**:
   - Use limit techniques
   - Consider infinity rules
   - Watch for indeterminate forms
   - Verify conclusion

#### Example Walkthrough
Find $\lim_{n \to \infty} \frac{n+1}{n}$
1. **Analyze form**:
   - Divide numerator and denominator by n
2. **Simplify**:
   - $\lim_{n \to \infty} (1 + \frac{1}{n})$
3. **Evaluate**:
   - As n → ∞, 1/n → 0
   - Limit = 1

### Common Mistakes
1. **Notation Errors**:
   - Confusing n and k
   - Missing subscripts
   - Wrong index bounds
   - Incorrect brackets/parentheses

2. **Conceptual Errors**:
   - Confusing sequence vs. series
   - Wrong starting index
   - Missing terms
   - Pattern recognition

## 2. Series Tests 🔍 {#tests}

### Understanding Series
A series is the sum of sequence terms. Think of it as:
- Adding up infinite terms
- Accumulation of sequence values
- Limit of partial sums
- Infinite summation

### Test Selection Guide
| Test | When to Use |
|------|-------------|
| n-th Term | First check |
| Geometric | Constant ratio |
| p-Series | $\frac{1}{n^p}$ form |
| Integral | Decreasing, positive |
| Comparison | Compare to known |
| Ratio | Fraction of terms |
| Root | nth root |
| Alternating | (-1)ⁿ series |

### Detailed Tests
#### 1. n-th Term Test
- If $\lim_{n \to \infty} a_n \neq 0$, series diverges
- Necessary but not sufficient
- Quick first check
- Can't prove convergence

#### 2. Geometric Series
$\sum_{n=0}^{\infty} ar^n$
- Converges if |r| < 1
- Sum = a/(1-r)
- Common first series
- Important in applications

#### 3. p-Series Test
$\sum_{n=1}^{\infty} \frac{1}{n^p}$
- Converges if p > 1
- Diverges if p ≤ 1
- Compare to 1/n
- Key benchmark series

#### 4. Integral Test
For f(x) continuous, decreasing, positive:
- Compare $\sum a_n$ to $\int_1^{\infty} f(x)dx$
- Both converge or both diverge
- Used for rational functions
- Good for power functions

#### 5. Comparison Tests
##### Direct Comparison
- If 0 ≤ aₙ ≤ bₙ
- bₙ converges → aₙ converges
- aₙ diverges → bₙ diverges
- Compare to known series

##### Limit Comparison
- Use $\lim_{n \to \infty} \frac{a_n}{b_n} = c > 0$
- Both converge or both diverge
- More flexible than direct
- Good for complex terms

#### 6. Ratio Test
$\lim_{n \to \infty} |\frac{a_{n+1}}{a_n}|$
- < 1: Converges
- > 1: Diverges
- = 1: Inconclusive
- Good for factorials, powers

#### 7. Root Test
$\lim_{n \to \infty} \sqrt[n]{|a_n|}$
- < 1: Converges
- > 1: Diverges
- = 1: Inconclusive
- Good for nth powers

### Example Walkthroughs
#### Ratio Test Example
Determine if $\sum_{n=1}^{\infty} \frac{2^n}{n!}$ converges
1. **Set up ratio**:
   - $|\frac{a_{n+1}}{a_n}| = |\frac{2^{n+1}}{(n+1)!} \cdot \frac{n!}{2^n}|$
2. **Simplify**:
   - $= \frac{2}{n+1}$
3. **Take limit**:
   - $\lim_{n \to \infty} \frac{2}{n+1} = 0$
4. **Conclude**:
   - Since limit < 1, series converges

#### Comparison Test Example
Compare $\sum_{n=1}^{\infty} \frac{1}{n^2 + 1}$ with $\sum_{n=1}^{\infty} \frac{1}{n^2}$
1. **Compare terms**:
   - $\frac{1}{n^2 + 1} < \frac{1}{n^2}$
2. **Check known series**:
   - $\sum \frac{1}{n^2}$ converges (p-series, p=2)
3. **Conclude**:
   - Original series converges by comparison

## 3. Power Series 📊 {#power}

### Understanding Power Series
Think of power series as:
- Infinite polynomials
- Function representations
- Convergent series
- Analytical tools

### Basic Form
$\sum_{n=0}^{\infty} c_n(x-a)^n$

#### Components
1. **Center (a)**:
   - Point of expansion
   - Reference point
   - Often 0 (Maclaurin)
   - Affects interval

2. **Coefficients (cₙ)**:
   - Determine behavior
   - Control convergence
   - Found from function
   - Pattern important

### Radius of Convergence
#### Finding R
1. **Using Ratio Test**:
   - $R = \frac{1}{\lim_{n \to \infty} \sqrt[n]{|c_n|}}$
2. **Using Root Test**:
   - $R = \frac{1}{\lim_{n \to \infty} |\frac{c_{n+1}}{c_n}|}$

#### Interval of Convergence
1. **Find R**
2. **Check endpoints**
3. **Write interval**
4. **Consider domain**

### Operations
#### Differentiation
- Term by term
- Within radius
- Power rule
- Coefficient changes

#### Integration
- Term by term
- Within radius
- Power rule
- New coefficient

## 4. Taylor Series 📈 {#taylor}

### Understanding Taylor Series
Think of Taylor series as:
- Function approximations
- Power series representations
- Local behavior models
- Infinite polynomials

### Formula
$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$

### Common Series
1. **Exponential**:
   $e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$
   - All x
   - Quick convergence
   - Important base

2. **Sine**:
   $\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n+1}}{(2n+1)!}$
   - All x
   - Odd function
   - Alternating

3. **Cosine**:
   $\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}$
   - All x
   - Even function
   - Alternating

4. **Geometric**:
   $\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n, |x| < 1$
   - Limited interval
   - Basic series
   - Common pattern

### Finding Taylor Series
#### Process
1. **Find Derivatives**:
   - Calculate f'(a), f''(a), etc.
   - Look for pattern
   - Consider symmetry
   - Watch signs

2. **Write Terms**:
   - Use Taylor formula
   - Simplify fractions
   - Combine like terms
   - Check pattern

3. **Determine Interval**:
   - Find radius
   - Check endpoints
   - Consider domain
   - Verify convergence

## 5. Error Bounds ⚠️ {#error}

### Understanding Error
Think of error bounds as:
- Approximation accuracy
- Guaranteed limits
- Precision measure
- Truncation effects

### Taylor's Remainder Theorem
$R_n(x) = \frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}$

### Lagrange Error Bound
$|R_n(x)| \leq \frac{M}{(n+1)!}|x-a|^{n+1}$

#### Process
1. **Find M**:
   - Maximum of |f⁽ⁿ⁺¹⁾(x)|
   - On given interval
   - Consider derivatives
   - Use calculus

2. **Calculate Bound**:
   - Substitute values
   - Evaluate factorial
   - Compute power
   - Compare to actual

### Example Walkthrough
Find error bound for sin x using n = 3 at x = 0.1
1. **Identify M**:
   - |f⁽⁴⁾(x)| = |sin x| ≤ 1
2. **Use formula**:
   - $|R_3(0.1)| ≤ \frac{1}{4!}|0.1|^4$
3. **Evaluate**:
   - $\leq \frac{0.0001}{24}$
   - Very small error

## 📝 AP-Style Examples

### Example 1: Series Convergence
Determine if $\sum_{n=1}^{\infty} \frac{3^n}{n!}$ converges.

**Solution**:
1. **Choose test**:
   - Ratio test best for factorial
2. **Apply test**:
   - $\lim_{n \to \infty} |\frac{3^{n+1}}{(n+1)!} \cdot \frac{n!}{3^n}|$
   - $= \lim_{n \to \infty} \frac{3}{n+1} = 0$
3. **Conclude**:
   - Since limit < 1, series converges

### Example 2: Taylor Series
Find the first 3 terms of Taylor series for ln(1+x) at a = 0.

**Solution**:
1. **Find derivatives**:
   - f'(x) = 1/(1+x)
   - f''(x) = -1/(1+x)²
   - f'''(x) = 2/(1+x)³
2. **Evaluate at a = 0**:
   - f'(0) = 1
   - f''(0) = -1
   - f'''(0) = 2
3. **Write series**:
   - $x - \frac{x^2}{2} + \frac{x^3}{3} + ...$

## 💡 Success Strategies

### 1. Test Selection
- Try n-th term test first
- Look for familiar patterns
- Consider complexity
- Use test selection guide

### 2. Common Mistakes
- Wrong test choice
- Incorrect intervals
- Sign errors
- Pattern recognition

### 3. Calculator Tips
- Graph partial sums
- Check convergence
- Verify calculations
- Use numerical tests

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show work**:
   - Justify test choice
   - Show all steps
   - State conclusions
   - Check endpoints

2. **Common Questions**:
   - Convergence tests
   - Taylor series
   - Error bounds
   - Interval of convergence

### Multiple Choice Strategy
1. **Consider**:
   - Multiple approaches
   - Known series
   - Common patterns
   - Quick checks

2. **Check**:
   - Reasonableness
   - Convergence
   - Endpoints
   - Domain

---

*💡 Pro Tip: Memorize common Taylor series and their intervals of convergence - they're frequently tested!* 