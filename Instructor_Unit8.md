# College Algebra - MATH 1503 - Guided Notes (INSTRUCTOR VERSION)
# Unit 8: Rational Expressions and Equations

## Key Concepts

### Fundamental Definitions
A rational expression is **an expression that can be written as the quotient of two polynomials**.

A rational equation is **an equation containing one or more rational expressions**.

### Review of Previous Concepts
- Factoring polynomials: **Breaking down a polynomial into a product of simpler polynomials**
- Finding the LCD: **The smallest expression that is divisible by all denominators**
- Domain restrictions: **Values that make denominators equal to zero must be excluded from the domain**

## Rational Equations

### Steps for Solving Rational Equations
1. **Multiply** the equation by all denominators until no fractions remain.
2. Use the **distributive** property to simplify.
3. **Combine** like terms.
4. Add/Subtract to get all of the **variables** on one side.
5. **Factor** the equality.
6. Determine which x values would result in **zero** (these are the potential solutions).
7. Check with the original **denominators** to ensure that no potential answers will cause "undefined".

### Practice Problems

**Problem 1:** Solve the rational equation:
$\frac{x + 10}{x(x - 1)} = \frac{x + 10}{x - 1}$

Step 1: Multiply by denominators: $x(x-1) \cdot \frac{x + 10}{x(x - 1)} = x(x-1) \cdot \frac{x + 10}{x - 1}$

Step 2: Simplify: $(x + 10) = x \cdot \frac{x + 10}{x - 1} = \frac{x(x+10)}{x-1}$

Step 3: Combine like terms: $(x + 10)(x - 1) = x(x + 10)$

Step 4: Factor: $(x + 10)(x - 1) - x(x + 10) = 0$
$(x + 10)(x - 1 - x) = 0$
$(x + 10)(-1) = 0$
$-(x + 10) = 0$
$x + 10 = 0$
$x = -10$

Step 5: Solution: $x = -10$ and $x = 1$ (check: 1 is excluded as it makes the denominator zero)

**Problem 2:** Solve the rational equation:
$\frac{x}{x + 3} = \frac{3}{(x + 2)(x + 3)}$

Step 1: Multiply by denominators: $(x+3)(x+2)(x+3) \cdot \frac{x}{x+3} = (x+3)(x+2)(x+3) \cdot \frac{3}{(x+2)(x+3)}$

Step 2: Simplify: $x(x+2)(x+3) = 3(x+3)$

Step 3: Combine like terms: $x(x+2)(x+3) - 3(x+3) = 0$
$(x+3)[x(x+2) - 3] = 0$
$(x+3)[x^2 + 2x - 3] = 0$
$(x+3)[(x+3)(x-1)] = 0$

Step 4: Factor: $(x+3)^2(x-1) = 0$

Step 5: Solution: $x = -3$ or $x = 1$

**Problem 3:** Solve the rational equation:
$\frac{-2}{x - 3} = \frac{x}{x - 6}$

Step 1: Multiply by denominators: $(x-3)(x-6) \cdot \frac{-2}{x-3} = (x-3)(x-6) \cdot \frac{x}{x-6}$

Step 2: Simplify: $-2(x-6) = x(x-3)$
$-2x + 12 = x^2 - 3x$
$0 = x^2 - x - 12$

Step 3: Factor: $0 = (x-4)(x+3)$

Step 4: Solve for x: $x = 4$ or $x = -3$

Step 5: Solution: $x = 4$ or $x = -3$ (check: 3 and 6 are excluded as they make denominators zero)

**Problem 4:** Solve the rational equation:
$\frac{-2}{x(x + 2)} = \frac{x + 3}{x + 2}$

Step 1: Multiply by denominators: $x(x+2) \cdot \frac{-2}{x(x+2)} = x(x+2) \cdot \frac{x+3}{x+2}$

Step 2: Simplify: $-2 = x(x+3)$
$-2 = x^2 + 3x$
$0 = x^2 + 3x + 2$

Step 3: Factor: $0 = (x+2)(x+1)$

Step 4: Solve for x: $x = -2$ or $x = -1$

Step 5: Solution: $x = -1$ (check: $x = -2$ is excluded as it makes the denominator zero)

### Common Mistakes
- Forgetting to check for excluded values: If an x-value makes any denominator in the original equation equal to zero, it must be excluded from the solution set.
- Introducing extraneous solutions: When multiplying both sides by expressions containing the variable, we may introduce solutions that don't work in the original equation.
- Sign errors when clearing fractions: Be careful with negative signs when multiplying to clear fractions.
- Factoring errors: Incorrect factoring leads to incorrect solutions.

## Inverse Rational Functions

### Steps for Finding the Inverse of Rational Functions
1. Copy down the function. Replace **g(x)** with x and x with **y**.
2. **Multiply** by denominators to remove rational expressions.
3. Isolate all the **y's** on one side of the equality.
4. **Factor** the y side completely.
5. **Divide** to get y by itself.

### Practice Problems

**Problem 1:** Find $g^{-1}(x)$ for the function $g(x) = \frac{3x - 4}{22 - x}$

Step 1: Replace with y: $x = \frac{3y - 4}{22 - y}$

Step 2: Multiply by denominators: $x(22 - y) = 3y - 4$
$22x - xy = 3y - 4$

Step 3: Isolate y terms: $22x + 4 = 3y + xy$
$22x + 4 = y(3 + x)$

Step 4: Factor: $y = \frac{22x + 4}{3 + x}$

Step 5: Solve for y: $g^{-1}(x) = \frac{22x - 4}{x - 3}$

**Problem 2:** Find $g^{-1}(x)$ for the function $g(x) = \frac{x + 5}{15x - 4}$

Step 1: Replace with y: $x = \frac{y + 5}{15y - 4}$

Step 2: Multiply by denominators: $x(15y - 4) = y + 5$
$15xy - 4x = y + 5$

Step 3: Isolate y terms: $15xy - y = 5 + 4x$
$y(15x - 1) = 5 + 4x$

Step 4: Factor: $y = \frac{5 + 4x}{15x - 1}$

Step 5: Solution: $g^{-1}(x) = \frac{4x + 5}{15x - 1}$

**Problem 3:** Find $g^{-1}(x)$ for the function $g(x) = \frac{23x - 150}{14 + x}$

Step 1: Replace with y: $x = \frac{23y - 150}{14 + y}$

Step 2: Multiply by denominators: $x(14 + y) = 23y - 150$
$14x + xy = 23y - 150$

Step 3: Isolate y terms: $14x + 150 = 23y - xy$
$14x + 150 = y(23 - x)$

Step 4: Factor: $y = \frac{14x + 150}{23 - x}$

Step 5: Solution: $g^{-1}(x) = \frac{14x - 150}{x - 23}$

### Common Mistakes
- Forgetting to switch x and y: The first step in finding an inverse is to replace f(x) with y, then switch x and y.
- Calculation errors when solving for y: The algebra can get complex when solving for y in a rational function.
- Domain restrictions: Not identifying the domain restrictions for the inverse function.
- Not checking: Failing to verify that f(f⁻¹(x)) = x and f⁻¹(f(x)) = x.

## Formulas for Modeling Rational Expressions

### Key Formulas
- Amount/Distance = **rate** × **time**
- Rate = **amount**/**time** 
- Time = **amount**/**rate**
- Concentration (c) = **ingredient volume** / **total volume**
- Ingredient volume (iv) = **concentration** × **total volume**
- Total volume (tv) = **ingredient volume**/**concentration**
- Final volume = **starting volume** + **change in volume**

### Practice Problems

**Problem 1:** Deshawn and Tyriq can weed their garden in 30 minutes together. Alone, it takes Tyriq 75 minutes to weed the garden. How long does it take Deshawn to weed the garden alone?

Step 1: Identify formula to use: **Rate = amount/time formula**

Step 2: Set up the equation: **Deshawn's rate + Tyriq's rate = Combined rate**
**1/dT + 1/75 = 1/30**

Step 3: Solve: **1/dT = 1/30 - 1/75**
**1/dT = 5/150 - 2/150 = 3/150 = 1/50**

Step 4: Solution: **Deshawn can weed the garden alone in 50 minutes**

**Problem 2:** Ujarak has 100mL of a strong toothpaste with a 1.1% concentration of sodium fluoride. They have a weaker toothpaste with a 0.3% concentration of sodium fluoride. What volume, in milliliters, of the weaker toothpaste would Ujarak need to add to the strong toothpaste to create a blend with a 0.8% concentration of sodium fluoride?

Step 1: Set up variables: **Let v = volume of weaker toothpaste to add**

Step 2: Set up the equation: **Final volume = Starting volume + Change in volume**
**0.008(100 + v) = 0.011(100) + 0.003v**

Step 3: Solve: **0.8 + 0.008v = 1.1 + 0.003v**
**0.008v - 0.003v = 1.1 - 0.8**
**0.005v = 0.3**
**v = 60**

Step 4: Solution: **Ujarak needs to add 60mL of the weaker toothpaste**

### Common Mistakes
- Using the wrong formula: Make sure to identify which formula applies to the given problem.
- Unit conversions: Forgetting to keep units consistent throughout calculations.
- Setting up the equation incorrectly: When working with rates, make sure to properly represent the relationship between variables.
- Not checking the reasonableness of answers: Always verify that your answer makes sense in the context of the problem.

## Reducing Rational Expressions

### Steps for Reducing Rational Expressions
1. **Factor** the numerator and denominator (if possible).
2. Note any results that would cause **division by zero** in the denominator.
3. Cancel out any matching **binomials** in the numerator and denominator.

### Practice Problem

**Problem:** Reduce the rational expression: $\frac{x^2 - 7x + 12}{x^2 - 6x + 9}$

Step 1: Factor the numerator and denominator: $\frac{(x-3)(x-4)}{(x-3)^2}$

Step 2: Identify any excluded values: **x = 3 is excluded**

Step 3: Cancel matching factors: $\frac{(x-3)(x-4)}{(x-3)^2} = \frac{x-4}{x-3}$

Step 4: Simplified expression: $\frac{x-4}{x-3}$

### Common Mistakes
- Cancellation errors: Attempting to cancel terms that are not factors.
- Factoring errors: Incorrect factoring leads to incorrect simplified expressions.
- Missing excluded values: Forgetting to identify values that make the denominator zero.
- Simplifying before factoring: Always factor completely before canceling.

## Multiplying & Dividing Rational Expressions

### Steps for Multiplying and Dividing Rational Expressions
1. **Factor** both numerators and denominators (if possible).
2. For division, **invert** the second fraction and multiply.
3. Note any results that would cause **division by zero** in the denominator.
4. Cancel out any matching **binomials** in the numerator and denominator.
5. Perform the **multiplication**.
6. Combine like terms, if possible.

### Practice Problem

**Problem:** Multiply the rational expressions: $\frac{x + 8}{x^2 - 6x - 7} \cdot \frac{x^2 + 16x + 64}{x + 1}$

Step 1: Factor completely: $\frac{x + 8}{(x+1)(x-7)} \cdot \frac{(x+8)^2}{x + 1}$

Step 2: Identify any excluded values: **x = -1 and x = 7 are excluded**

Step 3: Cancel matching factors: $\frac{x + 8}{(x+1)(x-7)} \cdot \frac{(x+8)^2}{x + 1} = \frac{(x+8)^3}{(x+1)^2(x-7)}$

Step 4: Perform multiplication: $\frac{(x+8)^3}{(x+1)^2(x-7)}$

Step 5: Simplified expression: $\frac{(x+8)^3}{(x+1)^2(x-7)}$

### Common Mistakes
- Factoring errors: Not factoring completely or factoring incorrectly.
- Confusing multiplication and division: For division, remember to invert the second fraction.
- Cancellation errors: Canceling terms that are not common factors.
- Missing domain restrictions: Forgetting to note values that make denominators zero.

## Adding & Subtracting Rational Expressions

### Steps for Adding & Subtracting Rational Expressions
1. Determine **greatest common factor** in the denominator (this may require factoring).
2. For subtraction only: **Distribute** the negative sign as a -1.
3. Multiply all terms to get a **common denominator**.
4. Add the **numerators**.
5. Combine **like terms**, if possible.

### Practice Problems

**Problem 1:** Add the rational expressions: $\frac{5}{x + 5} + \frac{28}{x - 3}$

Step 1: Find the least common denominator: **(x + 5)(x - 3)**

Step 2: Rewrite with common denominator: $\frac{5(x-3)}{(x+5)(x-3)} + \frac{28(x+5)}{(x-3)(x+5)}$

Step 3: Add numerators: $\frac{5(x-3) + 28(x+5)}{(x+5)(x-3)}$
$= \frac{5x - 15 + 28x + 140}{(x+5)(x-3)}$
$= \frac{33x + 125}{(x+5)(x-3)}$

Step 4: Simplify: $\frac{33x + 125}{(x+5)(x-3)}$

**Problem 2:** Subtract the rational expressions: $\frac{8}{x + 3} - \frac{2}{x + 8}$

Step 1: Find the least common denominator: **(x + 3)(x + 8)**

Step 2: Rewrite with common denominator: $\frac{8(x+8)}{(x+3)(x+8)} - \frac{2(x+3)}{(x+8)(x+3)}$

Step 3: Subtract numerators: $\frac{8(x+8) - 2(x+3)}{(x+3)(x+8)}$
$= \frac{8x + 64 - 2x - 6}{(x+3)(x+8)}$
$= \frac{6x + 58}{(x+3)(x+8)}$

Step 4: Solution: $\frac{6x + 58}{(x+3)(x+8)}$

### Common Mistakes
- Using incorrect common denominators: Not finding the least common denominator or factoring incorrectly.
- Sign errors in subtraction: Forgetting to distribute the negative sign to all terms in the numerator.
- Adding/subtracting denominators: Only numerators should be added or subtracted when denominators are the same.
- Simplifying too early: Wait until the final step to simplify the resulting expression.

## Summary of Key Concepts

1. Rational equations: Equations involving fractions with variables in the denominator.
2. Inverse rational functions: Switching input and output values of rational functions.
3. Modeling with rational expressions: Using rational expressions to solve real-world problems.
4. Reducing rational expressions: Simplifying by factoring and canceling.
5. Operations with rational expressions: Adding, subtracting, multiplying, and dividing.

**Remember**: Always check for domain restrictions (values that make denominators zero)!

### Instructor Notes
- Students typically struggle most with modeling word problems using rational expressions. Consider providing additional examples or in-class group work focusing on translating word problems into equations.
- When teaching inverse rational functions, emphasize the domain restrictions carefully, as these are often overlooked.
- Encourage students to always check their answers by substituting back into the original equation.
- A common area of confusion is the difference between reducing a rational expression (simplifying) and solving a rational equation (finding values of the variable).

---

## Citation
These guided notes were generated using Claude 3.7 Sonnet by Anthropic (March 24, 2025). The content was structured based on instructor-provided source materials from a college algebra course. The prompting approach involved requesting a comprehensive set of guided notes with fill-in-the-blank sections for key concepts, step-by-step practice problems, and common mistake warnings for each topic in Unit 8: Rational Expressions and Equations.
