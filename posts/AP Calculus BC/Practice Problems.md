
> **Note**: These problems mirror actual AP exam questions in style and difficulty.

## 📚 Table of Contents
1. [Limits & Continuity](#limits)
2. [Derivatives](#derivatives)
3. [Integration](#integration)
4. [Series](#series)
5. [Parametric/Polar](#parametric)
6. [Differential Equations](#diffeq)

## Limits & Continuity 📊 {#limits}

### Problem 1
Evaluate $\lim_{x \to 0} \frac{\sin(3x)}{x}$

**Solution**:
1. $= 3\lim_{x \to 0} \frac{\sin(3x)}{3x}$
2. $= 3 \cdot 1 = 3$

### Problem 2
Find values of k where f(x) is continuous:
$f(x) = \begin{cases} 
x^2 + k & x < 2 \\
kx + 1 & x \geq 2
\end{cases}$

## Derivatives 📈 {#derivatives}

### Problem 3
Find $\frac{d}{dx}[\ln(\sin x)]$

**Solution**:
1. Chain Rule: $\frac{1}{\sin x} \cdot \cos x$
2. Simplify: $\cot x$

### Problem 4
If $f'(x) = x^2e^x$ and f(0) = 1, find f(x).

## Integration 🔄 {#integration}

### Problem 5
Evaluate $\int_0^1 xe^{x^2}dx$

**Solution**:
1. Let u = x²
2. du = 2x dx
3. $\frac{1}{2}\int_0^1 e^u du$
4. $\frac{1}{2}(e - 1)$

### Problem 6
Find the area between y = sin x and y = cos x from 0 to π/4.

## Series 📊 {#series}

### Problem 7
Determine if $\sum_{n=1}^{\infty} \frac{2^n}{n!}$ converges.

**Solution**:
1. Ratio test: $\lim_{n \to \infty} |\frac{2^{n+1}}{(n+1)!} \cdot \frac{n!}{2^n}|$
2. $= \lim_{n \to \infty} \frac{2}{n+1} = 0$
3. Converges

### Problem 8
Find the Taylor series for ln(1+x) centered at a = 0.

## Parametric/Polar 🎯 {#parametric}

### Problem 9
Find $\frac{dy}{dx}$ for:
x = t² - 1
y = t³ + t

**Solution**:
1. $\frac{dx}{dt} = 2t$
2. $\frac{dy}{dt} = 3t^2 + 1$
3. $\frac{dy}{dx} = \frac{3t^2 + 1}{2t}$

### Problem 10
Find the area inside r = 2sin θ.

## Differential Equations ⚡ {#diffeq}

### Problem 11
Solve $\frac{dy}{dx} = 2xy$, y(0) = 1

**Solution**:
1. Separate: $\frac{dy}{y} = 2x dx$
2. Integrate: ln|y| = x² + C
3. y = Ce^{x²}
4. Use y(0) = 1: C = 1
5. y = e^{x²}

### Problem 12
Use Euler's method with Δx = 0.5 to approximate y(1) for:
$\frac{dy}{dx} = x + y$, y(0) = 1

## Free Response Style 📝

### Question 1 (9 points)
Given $f(x) = \int_0^x t\sin(t^2)dt$:

a) Find f'(x) (2 points)

b) Find f''(x) (2 points)

c) Find any critical points of f (3 points)

d) Justify whether each critical point is max/min (2 points)

### Question 2 (9 points)
A particle moves with velocity v(t) = t²e^{-t}:

a) Find acceleration (2 points)

b) Find all critical points of velocity (3 points)

c) Determine when speed is maximum (2 points)

d) Sketch velocity graph (2 points)

## Multiple Choice Style 🔍

### Question 1
$\lim_{x \to \infty} \frac{x^3 + 2x}{x^3 - x}$ =
A) 0
B) 1
C) -1
D) ∞

### Question 2
If $f''(x) = 6x + 2$, f'(0) = 1, and f(0) = 3, then f(2) =
A) 10
B) 11
C) 12
D) 13

## Success Strategies 💡

### For Free Response
1. Show all work
2. Use proper notation
3. Justify conclusions
4. Check units

### For Multiple Choice
1. Use process of elimination
2. Check answers
3. Consider graphical approach
4. Estimate when possible

## Common Mistakes ⚠️

1. Sign errors
2. Chain rule errors
3. Integration constant
4. Domain restrictions
5. Units consistency

## Calculator Tips 🖩

1. Check derivatives
2. Verify integrals
3. Graph functions
4. Table features

---

*💡 Pro Tip: Time yourself when solving these problems to build exam pace awareness!* 