
> **Note**: This comprehensive formula sheet covers all major topics in AP Calculus BC.

## 📚 Table of Contents
1. [Limits & Continuity](#limits)
2. [Derivatives](#derivatives)
3. [Integration](#integration)
4. [Series](#series)
5. [Parametric/Polar](#parametric)
6. [Differential Equations](#diffeq)

## Limits & Continuity 📊 {#limits}

### Special Limits
- $\lim_{x \to 0} \frac{\sin x}{x} = 1$
- $\lim_{x \to 0} \frac{1-\cos x}{x} = 0$
- $\lim_{x \to \infty} (1 + \frac{1}{x})^x = e$

## Derivatives 📈 {#derivatives}

### Basic Rules
- Power Rule: $\frac{d}{dx}[x^n] = nx^{n-1}$
- Product Rule: $\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$
- Quotient Rule: $\frac{d}{dx}[\frac{f(x)}{g(x)}] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$
- Chain Rule: $\frac{d}{dx}[f(g(x))] = f'(g(x))g'(x)$

### Common Derivatives
| Function | Derivative |
|----------|------------|
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |
| $\tan x$ | $\sec^2 x$ |
| $e^x$ | $e^x$ |
| $\ln x$ | $\frac{1}{x}$ |
| $a^x$ | $a^x \ln a$ |

## Integration 🔄 {#integration}

### Basic Integrals
- $\int x^n dx = \frac{x^{n+1}}{n+1} + C$, $n \neq -1$
- $\int \frac{1}{x} dx = \ln|x| + C$
- $\int e^x dx = e^x + C$
- $\int \sin x dx = -\cos x + C$
- $\int \cos x dx = \sin x + C$

### Integration Techniques
1. **U-Substitution**
   - $\int f(g(x))g'(x)dx = \int f(u)du$

2. **Integration by Parts**
   - $\int u\,dv = uv - \int v\,du$

3. **Partial Fractions**
   - Decompose rational functions

## Series 📊 {#series}

### Convergence Tests
1. **Ratio Test**
   - $\lim_{n \to \infty}|\frac{a_{n+1}}{a_n}|$
   - < 1: Converges
   - > 1: Diverges
   - = 1: Inconclusive

2. **Root Test**
   - $\lim_{n \to \infty}\sqrt[n]{|a_n|}$

3. **p-Series**
   - $\sum \frac{1}{n^p}$ converges if p > 1

### Taylor Series
$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$

### Common Series
1. $e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$
2. $\sin x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n+1}}{(2n+1)!}$
3. $\cos x = \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}$
4. $\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n$, |x| < 1

## Parametric/Polar 🎯 {#parametric}

### Parametric Derivatives
$\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}}$

### Polar Formulas
- x = r cos θ
- y = r sin θ
- $r^2 = x^2 + y^2$
- Area: $A = \frac{1}{2}\int_α^β r^2 dθ$
- Arc Length: $L = \int_α^β \sqrt{r^2 + (\frac{dr}{dθ})^2}dθ$

## Differential Equations ⚡ {#diffeq}

### First Order
1. **Separable**
   - $\frac{dy}{dx} = f(x)g(y)$
   - Separate and integrate

2. **Linear**
   - $\frac{dy}{dx} + P(x)y = Q(x)$
   - Use integrating factor

### Common Forms
1. **Growth/Decay**
   - $\frac{dy}{dt} = ky$
   - Solution: $y = Ce^{kt}$

2. **Logistic**
   - $\frac{dy}{dt} = ky(1-\frac{y}{M})$
   - Solution: $y = \frac{M}{1 + Ce^{-kt}}$

### Euler's Method
$y_{n+1} = y_n + f(x_n,y_n)\Delta x$

## 📊 Important Constants

### Trigonometric Values
| Angle | sin | cos | tan |
|-------|-----|-----|-----|
| 0° | 0 | 1 | 0 |
| 30° | 1/2 | √3/2 | 1/√3 |
| 45° | 1/√2 | 1/√2 | 1 |
| 60° | √3/2 | 1/2 | √3 |
| 90° | 1 | 0 | undef |

### Other Constants
- e ≈ 2.71828
- π ≈ 3.14159
- ln(e) = 1
- e^(ln x) = x

---

*💡 Pro Tip: This formula sheet is provided for reference - understanding how to use these formulas is more important than memorizing them!* 