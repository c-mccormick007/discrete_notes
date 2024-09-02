# [[Discrete Computing]]
**Date:** 2024-08-26
#notes #discreet
## Key Terms:


![[Tautology]]
 ![[Contradiction]]
 ![[Logically Equivalent]]
## Truth tables for [[Tautology]] & [[Contradiction]]: 

[[Tautology]]:

| $p$ | $¬p$ | $p∨¬p$ |
| --- | ---- | ------ |
| T   | F    | T      |
| F   | T    | T      |
[[Contradiction]]:

| $p$ | $¬p$ | $p∨¬p$ |
| --- | ---- | ------ |
| T   | F    | F      |
| F   | T    | F      |

## Showing logical equivalence using [[Truth Table]]s:

If $s$ and $r$ are two compound propositions, the notation $s ≡ r$ is used to indicate they are [[Logically Equivalent]]. 

| $p$ | $¬p$  | $p→¬p$ |
| --- | ----- | ------ |
| T   | ==F== | ==F==  |
| F   | ==T== | ==T==  |
1. $p→¬p$ can be shown to be equivalent to $¬p$ by filling in a column for $¬p$.
2. Then a column for $p→¬p$ is filled in, and the two columns are verified to be the same.

Table 1.4.3:
### $¬p∨¬q ≡ ¬(p∧q)$

| $p$ | q   | $¬p$ | $¬q$ | $p∧q$ | $¬(p∧q)$ | $¬p∨¬q$ |
| --- | --- | ---- | ---- | ----- | -------- | ------- |
| T   | T   | F    | F    | T     | F        | F       |
| T   | F   | F    | T    | F     | T        | T       |
| F   | T   | T    | F    | F     | T        | T       |
| F   | F   | T    | T    | F     | T        | T       |

## [[Discrete Computing/Chapter 1.1-1.7 - Logic A/Key Terms/De Morgan's Laws]]:

The first De Morgan Law is: 
## $¬(p∨q) ≡ (¬p∧¬q)$

When the negation operation is distributed inside the parentheses, the [[Disjunction]] operation changes to a [[Conjunction]] operation.

Consider an English example with the following propositions for $p$ and $q$

- $p$: The patient has migraines

- $q$: The patient has high blood pressure

The use of the English word "or" throughout the example is assumed to be [[Disjunction]] (i.e., the inclusive or). [[Discrete Computing/Chapter 1.1-1.7 - Logic A/Key Terms/De Morgan's Laws]] says that the following two English statements are [[Logically Equivalent]]:

The second version swaps the role of [[Disjunction]] and [[Conjunction]]:
## $¬(p∧q) ≡ (¬p∨¬q)$


# Exercises Todo: 
- [ ] 1.4.1
- [ ] 1.4.2
- [ ] 1.4.3
- [ ] 1.4.4
- [ ] 1.4.5
- [ ] 1.4.6