# [[Discrete Computing]]
**Date:** 2024-09-01
#notes #discreet

## Key Terms:

![[Predicate]]
![[Domain]]
![[Arbitrary Element]]
![[Quantifier]]
![[Universal Quantifier]]
## [[Predicate|Predicates]] & Mathematical Statements

Mathematical statements with variables aren't propositions until the variable is defined. For [[example]]:

- "$x$ is an odd number":
  - True if $x = 5$
  - False if $x = 4$

Such statements are called **predicates**, expressed as functions like $P(x)$. If $P(x)$ is "x is an odd number," then $P(5)$ is a true proposition ("5 is an odd number").

### Predicates with Multiple Variables:
- $Q(x, y) : x^2 = y$ (e.g., $Q(5, 25)$ is true)
- $R(x, y, z) : x + y = z$ (e.g., $R(2, 3, 6)$ is false)

### [[domain|Domain]]:
The **[[domain]]** of a variable is the set of all possible values. For [[example]], the [[domain]] for "$x$ is an odd number" is all integers.

### Non-Mathematical Predicates:
Predicates aren't limited to math. For [[example]], "The city has a population over $1,000,000$":

- True if the city is New York
- False if the city is Toledo

Even if $P(x)$ is true for all $x$, it's still a predicate if it contains a variable (e.g., $P(x) = x + 1 > 1$).

## [[Universal Quantifier]]

A predicate becomes a proposition with a well-defined truth value if variables are assigned specific values from their domains. Another way to turn a predicate into a proposition is by using a **quantifier**.

- **[[Universal Quantifier]] ($\forall$)**: Asserts that $P(x)$ is true for every value of $x$ in its domain.
  - [[example]]: $\forall x P(x)$ means $P(x)$ is true for all $x$ in the domain.
  - If the domain is finite, $\forall x P(x)$ is true if it holds for every element.

Establishing $\forall x A(x)$ is true requires showing that each element in the domain satisfies the predicate.

Some universally quantified statements are proven by showing the predicate holds for an arbitrary element from the domain.

- [[example]]: The domain is all positive integers, and $\forall x \left(\frac{1}{x+1} < 1\right)$ is true because it holds for any positive integer $x$.

## Proof of $\forall x \left(\frac{1}{x+1} < 1\right)$ for Arbitrary Positive Integers $x$

This proof demonstrates that the inequality $\forall x \left(\frac{1}{x+1} < 1\right)$ holds true for all positive integers $x$:

1. Start with the fact that $0 < x$ for all positive integers $x$.
2. Add 1 to both sides to get $1 < x + 1$.
3. Divide both sides by $x + 1$ to obtain $\frac{1}{x+1} < 1$.

Thus, the inequality $\forall x \left(\frac{1}{x+1} < 1\right)$ is true for all positive integers $x$.

## [[Counterexample]] in Universally Quantified Statements

A **[[Counterexample]]** is an element in the domain that makes a universally quantified statement false. Just one [[Counterexample]] is enough to disprove such a statement.

- **[[example]]**: For the statement $\forall x(x^2 > x)$, with $x$ being a positive integer, $x = 1$ serves as a [[Counterexample]] because $1^2 = 1$ does not satisfy $x^2 > x$.

If the domain is empty, $\forall x P(x)$ is considered true because there are no elements for which $P(x)$ is false.
## [[Existential Quantifier]]

An **[[Existential Quantifier]]** ($\exists$) asserts that a predicate $P(x)$ is true for at least one value of $x$ in its domain. The statement $\exists xP(x)$ is a proposition because it is either true or false.

- **[[example]]**: If the domain is a finite set, $\exists xP(x)$ is true if at least one element in the domain satisfies the predicate.

To prove that $\exists xA(x)$ is true, finding one [[example]] where the predicate is true is sufficient. This [[example]] is known as an **[[example]]**. However, to show that $\exists xA(x)$ is false, it must be proven that no element in the domain satisfies the predicate.

- **[[example]]**: For the statement $\exists x(x + 1 < x)$ in the domain of all positive integers, the statement is false because no positive integer satisfies this inequality.

If the domain is empty, $\exists xP(x)$ is false because there are no elements to satisfy $P(x)$.

## Proof That $\exists x (x + 1 < x)$ Is False

This proof demonstrates that the inequality $\exists x (x + 1 < x)$ is false:

1. Start with the inequality $x + 1 < x$.
2. Subtract $x$ from both sides to get $1 < 0$.

Since $1 < 0$ is false, the inequality $x + 1 < x$ is false for every $x$. Therefore, $\exists x (x + 1 < x)$ is false.

## Proving and Disproving Statements

### 1. Proving $\exists xP(x)$ is true:
- **Approach**: Give an [[example]] of a specific element $n$ in the domain for which $P(n)$ is true.
- **Explanation**: The statement $\exists xP(x)$ means that $P(n)$ is true for at least one element $n$ in the domain.

### 2. Proving $\exists xP(x)$ is false:
- **Approach**: Show that for every element $n$ in the domain, $P(n)$ is false.
- **Explanation**: The fact that $\exists xP(x)$ is false means there is no element $n$ in the domain that makes $P(n)$ true. This is equivalent to showing that every element in the domain makes $P(n)$ false.

### 3. Proving $\forall xP(x)$ is true:
- **Approach**: Show that for every element $n$ in the domain, $P(n)$ is true.
- **Explanation**: The statement $\forall xP(x)$ means that $P(n)$ is true for every element $n$ in the domain.

### 4. Proving $\forall xP(x)$ is false:
- **Approach**: Provide a [[Counterexample]], a specific element $n$ in the domain for which $P(n)$ is false.
- **Explanation**: If $\forall xP(x)$ is false, it means that there is at least one element $n$ in the domain where $P(n)$ does not hold true.

# Exercises Todo: 
- [ ] 1.8.1
- [ ] 1.8.2
- [ ] 1.8.3
- [ ] 1.8.4
- [ ] 1.8.5