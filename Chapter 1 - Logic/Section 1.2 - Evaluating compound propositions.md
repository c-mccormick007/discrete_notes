# [[Discrete Computing]]
**Date:** 2024-08-23
#notes #discreet

## Key Terms:

![[Compound proposition]]

![[Truth Table]]

## Evaluating [[Compound proposition|Compound Propositions]]:

Order of operations with Absence of Parenthesis: 
1. **¬** - Not
2. **∧** - And
3. **∨** - Or
#### Using parenthesis to specify the order of operations is a good practice.
##### **Example**: *p* **∨** *q* **∧** *r* 
- This should be read as *p* **∨** (*q* **∧** *r* )

#### [[Negation]] is always applied first. 
##### **Example**: **¬***p* **∨** *q* 
- This should be read as (**¬***p*) **∨** *q*  instead of **¬**(*p* **∨** *q*)  

#### In the event of multiple **∧** or **∨** operations, parenthesis can be omitted because the order will not affect the final truth value. 
##### **Example**: *p* **∨** *q* **∨** *r*
- No change needed. 
## Filling in the rows of a [[Truth Table]]:

A [[Truth Table]] for a [[Compound proposition]] has a row for every possible combination of truth assignments for the statement's variables. 

The amount of rows in a compound function $= 2^n$

The [[truth table]] for a compound proposition **$(p ∨ r) ∧ ¬q$** has $2^3 = 8$ rows. 
The top row starts with all T's. The rightmost column alternates between T and F. The column to the left of that alternates between 2T and 2F. The column to the left of that alternates between 4T and 4F. Every column to the left will double past that.

| $p$ | $q$ | $r$ | $(p ∨ r) ∧ ¬q$ |
| --- | --- | --- | -------------- |
| T   | T   | T   | F              |
| T   | T   | F   | F              |
| T   | F   | T   | T              |
| T   | F   | F   | T              |
| F   | T   | T   | F              |
| F   | T   | F   | F              |
| F   | F   | T   | T              |
| F   | F   | F   | F              |

# Exercises Todo: 

- [x] 1.2.1
- [x] 1.2.2
- [x] 1.2.3
- [x] 1.2.4
- [x] 1.2.5
- [x] 1.2.6
- [x] 1.2.7
- [x] 1.2.8
- [x] 1.2.9
