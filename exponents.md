# Exponents

Exponents are a shortcut for repeated multiplication:

$\qquad a^n = \underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ times}}$

# Exponent Rules
These are the rules for converting formulas with exponents.

| Rule | Formula |
| - | - |
| Product | $$a^m \times a^n = a^{m+n}$$  |
| Quotient  | $$a^m \div a^n = a^{m-n}$$ |
| Power of a Power  | $$(a^m)^n = a^{m \times n}$$ |
| Power of a Product  | $$(ab)^m = a^m b^m$$ |
| Power of a Quotient  | $$\left(\frac{a}{b}\right)^m = \frac{a^m}{b^m}$$ |
| Negative Exponent  | $$a^{-n} = \frac{1}{a^n}$$ |
| Fractional Exponent  | $$a^{m/n} = \sqrt[n]{a^m}$$ |

# Exponent Rule Proofs

Mathematical proofs for exponent rules rely directly on the definition of an exponent as repeated multiplication:

$\qquad a^n = \underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ times}}$

By expanding these expressions into their multiplied forms, the underlying rules become clear.

## The Product Rule
This is a proof for the Product Rule.

$\qquad a^m \cdot a^n = a^{m+n}$

1. Definition Expansion

$\qquad a^m = \underbrace{a \cdot a \cdot \dots \cdot a}_{m \text{ times}}$

$\qquad a^n = \underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ times}}$

2. Combined Multiplication

$\qquad a^m \cdot a^n = \left( \underbrace{a \cdot a \cdot \dots \cdot a}_{m \text{ times}} \right) \cdot \left( \underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ times}} \right)$

3. Count the Total

> There are a total of $(m + n)$ factors of $a$ being multiplied together.

4. Conclusion

$\qquad a^m \cdot a^n = a^{m+n}$

## The Quotient Rule
This is a proof of the Quotient Rule.

$\qquad \frac{a^m}{a^n} = a^{m-n}$ (where $a \neq 0$)

1. Definition Expansion

$\qquad \frac{a^m}{a^n} = \frac{\overbrace{a \cdot a \cdot \dots \cdot a}^{m \text{ times}}}{\underbrace{a \cdot a \cdot \dots \cdot a}_{n \text{ times}}}$

2. Cancellation

> Every factor of $a$ in the denominator cancels out a corresponding factor of $a$ in the numerator ($\frac{a}{a} = 1$).

4. Count the Remaining

> After canceling $n$ factors from both the top and bottom, you are left with exactly $(m - n)$ factors of $a$ in the numerator.

5. Conclusion

$\qquad \frac{a^m}{a^n} = a^{m-n}$

## The Zero Exponent Rule
This is a proof for the Zero Exponent Rule.

$\qquad a^0 = 1$ (where $a \neq 0$)

1. Setup

> Start with a simple division where the numerator and denominator are identical: $\frac{a^n}{a^n}$.

2. Method 1 (Arithmetic)
  
> Any non-zero number divided by itself equals 1.

$\qquad \frac{a^n}{a^n} = 1$

3. Method 2 (Quotient Rule)
  
> Apply the quotient rule by subtracting the exponents.

$\qquad \frac{a^n}{a^n} = a^{n-n} = a^0$

4. Conclusion

> Since both methods solve the exact same expression, their results must equal each other.

$\qquad a^0 = 1$

## The Negative Exponent Rule
This is a proof for the Negative Exponent Rule.

$\qquad a^{-n} = \frac{1}{a^n}$

1. Setup

> Write out the expression $a^{-n}$ as a product using the zero exponent rule ($a^0 = 1$).

$\qquad a^{-n} = a^{0 - n}$

2. Reverse Quotient Rule

> Rewrite this subtraction in the exponent as a division problem.

$\qquad a^{0 - n} = \frac{a^0}{a^n}$

3. Substitute $a^0$

> Substitute $1$ in place of $a^0$.

$\qquad \frac{a^0}{a^n} = \frac{1}{a^n}$

4. Conclusion

$\qquad a^{-n} = \frac{1}{a^n}$

## The Power of a Power Rule
This is a proof for the Power of a Power Rule.

$\qquad (a^m)^n = a^{m \cdot n}$

1. Definition Expansion

> Treat $a^m$ as the base being multiplied by itself $n$ times.

$\qquad (a^m)^n = \underbrace{a^m \cdot a^m \cdot \dots \cdot a^m}_{n \text{ times}}$

2. Apply Product Rule

> Use the product rule to add all the exponents together.

$\qquad a^{\overbrace{m + m + \dots + m}^{n \text{ times}}}$

3. Simplify Addition

> Adding the number $m$ a total of $n$ times is the exact definition of multiplication ($m \cdot n$).

4. Conclusion

$\qquad (a^m)^n = a^{m \cdot n}$

### Logarithms

*Logarithms* are the reverse of exponents.
If we say a number $n$ has the value of a base $b$ to the power $m$:

$\qquad n = b^m$

The logarithm of $n$, base $b$, is $m$:

$\qquad log_{b}\ n = m$

Logarithms are another convenient way to represent large numbers. For $n$ = $1,000,000$:

$\qquad log_{10}\ n = log_{10}\ 1,000,000 = log_{10}\ 10^6 = 6$


### Roots
The *square root* of a number $n$ is the number which if multplied by itself will be $n$.  

$\qquad \sqrt{n} \cdot \sqrt{n} = (\sqrt{n})^2 = n$    

The cube root is the third root of $n$.   

$\qquad \sqrt[3]{n} \cdot \sqrt[3]{n} \cdot \sqrt[3]{n} = (\sqrt[3]{n})^3 = n$    

The fourth root is $\sqrt[4]{n}$, and so on.
We say this follows the *fractional exponent* rule.  

$\qquad \sqrt[n]{a}\>=\sqrt[n]{a^1}\>=\>a^{\frac{1}{n}}$


