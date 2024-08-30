# [[Discrete Computing]]
**Date:** 2024-08-23
#notes #discreet

## Key Terms:

 ![[Conditional Operation]]
 ![[Conditional Proposition]]
 ![[Conditional Statement]]
 ![[Biconditional Operation]]
 
## [[Truth Table]] for the [[Conditional Operation]]:

| $p$ | $q$ | $p→q$ |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | F     |
| F   | T   | T     |
| F   | F   | T     |

A [[Conditional Proposition]] can be thought of like a contract between two parties. 
- "If you mow Mr. Smith's lawn, then he will pay you."

The only way for the contract to be broken is for you to mow his lawn and for Smith to not pay you. Speaking in logic, the only scenario in which the contract is broken is when $p$ is true and $q$ is false.

if **you mow Mr. Smith's Lawn**, then **he will pay you.**
$p$ = "you mow Mr. Smith's Lawn,"
$q$ = "he will pay you."

|              | $q$ is true | $q$ is false |
| ------------ | ----------- | ------------ |
| $p$ is true  | $p→q = T$   | $p→q = F$    |
| $p$ is false | $p→q = T$   | $p→q = T$    |

Here are some English expressions of the [[conditional operation]]

| if $p$, then $q$.         | If you mow Mr. Smith's lawn, then he will pay you.           |
| ------------------------- | ------------------------------------------------------------ |
| if $p$, $q$.              | If you mow Mr. Smith's lawn, he will pay you.                |
| $q$ if $p$.               | Mr. Smith will pay you if you mow his lawn.                  |
| $p$ implies $q$           | Mowing Mr. Smith's lawn implies that he will pay you.        |
| $q$ whenever $p$.         | Mr. Smith will pay you whenever you mow his lawn.            |
| $p$ only if $q$           | You will mow Mr. Smith's lawn only if he pays you.           |
| $p$ is sufficient for $q$ | Mowing Mr. Smith's lawn is sufficient for him to pay you.    |
| $q$ is necessary for $p$  | Mr. Smith's paying you is necessary for you to mow his lawn. |



## Converse, contrapositive, and inverse:

Three conditional statements related to [[Proposition]] $p→q$ are so common they have special names. 

![[Converse]]
![[Contrapositive]]
![[Inverse]]

## [[Truth Table]] for the [[Biconditional Operation]]:

| $p$ | $q$ | $p↔q$ |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | F     |
| F   | T   | F     |
| F   | F   | T     |
English expressions:
- "$p$ is necessary and sufficient for $q$"
- "if $p$ then $q$, and conversely."

The term **iff** is an abbreviation of the expression "if and only if," like "$p$ iff $q$"

## Evaluating [[Compound proposition]] with a [[Biconditional Operation]]: 

If parenthesis are not present, the order of operations is as follows: 
1. **¬** - Not
2. **∧** - And
3. **∨** - Or
After this you can apply ↔ and →.

$p$: T     $q$: T     $r$: F

$p ∨ ¬(q ↔ r)$
$T ∨ ¬(T ↔ F)$
$T ∨ ¬(F)$
$T ∨ T$
$T$


# Exercises Todo: 
- [x] Exercise 1.3.1
- [x] Exercise 1.3.2
- [ ] Exercise 1.3.3
- [ ] Exercise 1.3.4
- [ ] Exercise 1.3.5
- [ ] Exercise 1.3.6
- [ ] Exercise 1.3.7
- [ ] Exercise 1.3.8
- [ ] Exercise 1.3.9
- [ ] Exercise 1.3.10
- [ ] Exercise 1.3.11