Here are the most essential factorial properties, algebraic manipulation patterns, and specific exponential series tools you will need for **JEE Mains**, specifically tailored for solving infinite series problems in *Sequence & Series*.

---

## 1. Core Fundamental Properties

These are the basic definitions and structural identities used to rewrite terms in a summation.

### Basic Definition & Recursive Relation

For any integer $n \ge 1$:


$$n! = n \times (n - 1)!$$

> **Key Takeaway:** You can pull out any number of leading terms to simplify fractions.
> 
> $$\frac{n!}{(n - k)!} = n(n - 1)(n - 2)\cdots(n - k + 1)$$
> 
> 

### Double Factorial Notation

Used frequently when dealing with products of only odd or only even numbers:

* **Even terms product:** $2 \cdot 4 \cdot 6 \cdots (2n) = 2^n \cdot n!$
* **Odd terms product:** $1 \cdot 3 \cdot 5 \cdots (2n - 1) = \frac{(2n)!}{2^n \cdot n!}$

---

## 2. Algebraic Telescoping Patterns

In JEE Mains, series involving factorials in the denominator are often solved by breaking the general term $T_r$ into a difference of two consecutive terms: $T_r = V_r - V_{r+1}$.

### Pattern A: Multiplying $n$ by $n!$

$$n \cdot n! = (n + 1 - 1)n! = (n + 1)! - n!$$

If you need to sum $S = \sum_{r=1}^{n} r \cdot r!$:


$$S = (2! - 1!) + (3! - 2!) + \cdots + ((n+1)! - n!) = (n + 1)! - 1$$

---

### Pattern B: Linear Term over Factorial

When the numerator is linear in $r$, split the numerator to cancel out terms in the denominator.

$$\frac{r}{(r + 1)!} = \frac{(r + 1) - 1}{(r + 1)!} = \frac{1}{r!} - \frac{1}{(r + 1)!}$$

Summing this gives a telescoping series:


$$\sum_{r=1}^{n} \frac{r}{(r + 1)!} = 1 - \frac{1}{(n + 1)!}$$

---

### Pattern C: Quadratic/Polynomial Term over Factorial

If the numerator contains $r^2$ or higher powers, express the polynomial in terms of fall-through factors $r(r-1), r, 1$:

$$r^2 = r(r - 1) + r$$

Applying this to a general term:


$$\frac{r^2}{r!} = \frac{r(r - 1) + r}{r!} = \frac{1}{(r - 2)!} + \frac{1}{(r - 1)!} \quad ( \text{for } r \ge 2 )$$

---

## 3. The Exponential Series ($e^x$) Identities

The standard Taylor expansion for the exponential function is the foundation of complex-looking factorial series in JEE Mains.

### Standard Expansion

$$e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!} = 1 + \frac{x}{1!} + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots$$

Setting $x = 1$ and $x = -1$ gives two fundamental constant series:


$$e = 1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \dots$$

$$\frac{1}{e} = 1 - \frac{1}{1!} + \frac{1}{2!} - \frac{1}{3!} + \dots$$

---

### Key Even & Odd Combinations

By adding and subtracting the series for $e$ and $e^{-1}$, you obtain expressions for purely even or purely odd denominators:

$$\frac{e + e^{-1}}{2} = 1 + \frac{1}{2!} + \frac{1}{4!} + \frac{1}{6!} + \dots$$

$$\frac{e - e^{-1}}{2} = \frac{1}{1!} + \frac{1}{3!} + \frac{1}{5!} + \dots$$

---

## 4. Standard Summation Formulas using Exponential Series

These four standard sums frequently appear directly in JEE Mains problems:

| Series Summation | Value | Trick to Remember |
| --- | --- | --- |
| $\displaystyle \sum_{n=1}^{\infty} \frac{n}{n!}$ | $e$ | $\frac{n}{n!} = \frac{1}{(n-1)!}$ |
| $\displaystyle \sum_{n=1}^{\infty} \frac{n^2}{n!}$ | $2e$ | Split $n^2 = n(n-1) + n$ |
| $\displaystyle \sum_{n=1}^{\infty} \frac{n^3}{n!}$ | $5e$ | Split $n^3 = n(n-1)(n-2) + 3n(n-1) + n$ |
| $\displaystyle \sum_{n=1}^{\infty} \frac{n^4}{n!}$ | $15e$ | Convert numerator into factorial-falling polynomials |

---

## 5. Master Steps for Solving Infinite Factorial Series

When presented with a sum like $S = \sum_{n=1}^{\infty} \frac{P(n)}{n!}$ where $P(n)$ is a polynomial in $n$:

1. **Find the General Term ($T_n$):** Write down $T_n = \frac{P(n)}{n!}$.
2. **Decompose the Numerator:** Express $P(n)$ in terms of $n(n-1)(n-2)\dots$ factors matching the denominator.
3. **Cancel Factors:** Reduce $\frac{n(n-1)\dots}{n!}$ to $\frac{1}{(n-k)!}$.
4. **Substitute $e$ Series:** Group terms into standard forms like $\sum \frac{1}{k!} = e$.