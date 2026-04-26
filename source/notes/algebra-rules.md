### 1. Factoring Trinomials (The "Multiply & Add" Game)
You saw the "Difference of Squares" (like $x^2 - 9$), which only has two pieces. But often, you will see expressions with *three* pieces, called a trinomial.
* **The Rule:** To factor something that looks like $x^2 + bx + c$, you need to find two numbers that **multiply** to make the last number ($c$) AND **add** up to make the middle number ($b$).
* **Example:** Factor $x^2 + 5x + 6$
    * *Question:* What multiplies to $6$ and adds to $5$?
    * *Answer:* $2$ and $3$. ($2 \times 3 = 6$, and $2 + 3 = 5$).
    * *Result:* $(x + 2)(x + 3)$
* **Why it's needed:** Just like Difference of Squares, this is used constantly in Module 2 to cancel out "zero" denominators in limits.

### 2. Greatest Common Factor (GCF)
This is the simplest form of factoring, but the easiest to forget. It means pulling out the biggest piece that every term shares.
* **The Rule:** Look at all the pieces. What is the biggest number or letter they can all be divided by? Pull it out to the front.
* **Example:** $3x^2 - 12x$
    * *Question:* What do $3x^2$ and $12x$ have in common? Both can be divided by $3$, and both have at least one $x$.
    * *Result:* Pull $3x$ to the front. You get $3x(x - 4)$.
* **Why it's needed:** Often, doing this one simple step is enough to cross out a denominator and solve a limit.

### 3. The Exponent Rules (The Big Three)
When dealing with variables raised to powers, you need to know how those powers interact.
* **Rule A: Multiplying (Add the powers)**
    * If you multiply the same base, you add the tiny numbers.
    * *Example:* $x^2 \cdot x^3 = x^5$ *(Because $xx$ times $xxx$ is $xxxxx$)*
* **Rule B: Dividing (Subtract the powers)**
    * If you divide, the top power minus the bottom power wins.
    * *Example:* $$\frac{x^5}{x^2} = x^3$$
* **Rule C: Negative Exponents (The Flip)**
    * A negative exponent is just a fraction in disguise. It means "move me to the bottom."
    * *Example:* $x^{-2}$ is exactly the same as $$\frac{1}{x^2}$$
* **Why it's needed:** When we get to Module 4 (Derivative Rules), knowing how to move exponents around is the entire key to solving the problems quickly!

### 4. Fractional Exponents (Hidden Roots)

* **The Rule:** A square root is actually just an exponent of $\frac{1}{2}$. A cube root is an exponent of $\frac{1}{3}$.
* **Example:** $\sqrt{x}$ is the exact same thing as $x^{1/2}$. 
* **Why it's needed:** In calculus, there are no "rules" for square roots. So, whenever we see a square root, we rewrite it as a fraction exponent first, and then apply normal calculus rules.

### 5. The Conjugate (The Square Root Killer)
If you get a $\frac{0}{0}$ limit, but it has a square root in it, factoring won't work. You have to use a trick called the Conjugate.
* **The Rule:** The conjugate just means "flip the sign in the middle." If you have $(\sqrt{x} - 3)$, the conjugate is $(\sqrt{x} + 3)$. When you multiply them together, the square roots magically disappear.
* **Example:** Multiply $(\sqrt{x} - 3)$ by its conjugate $(\sqrt{x} + 3)$.
    * *Steps:* Use FOIL (First, Outer, Inner, Last). 
    * First: $\sqrt{x} \cdot \sqrt{x} = x$
    * Outer: $3\sqrt{x}$
    * Inner: $-3\sqrt{x}$ (Notice how the outer and inner cancel each other out to zero!)
    * Last: $-3 \cdot 3 = -9$
    * *Result:* $x - 9$


---
