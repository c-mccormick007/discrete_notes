# [[Discrete Computing]]
**Date:** 2024-08-23
#notes #discreet

## Key Terms:

 ![[Logic]]
 ![[Proposition]]
 ![[Propositional Variable]]
 ![[Compound proposition]]
 ![[Logical operation]]
 ![[Conjunction]]
 ![[Truth Table]]
 ![[Disjunction]]
 ![[Exclusive or]]
 ![[Inclusive Or]]
 ![[Negation]]
 
 
## [[Proposition|Propositions]]:

### Examples of Propositions
#### Statements that are either true or false.

| Proposition                                    | Truth value |
| ---------------------------------------------- | ----------- |
| There are an infinite amount of prime numbers. | True        |
| 17 is an **even** number.                      | False       |
#### English sentences that are not propositions.

| Sentence         | Comment                                                             |
| ---------------- | ------------------------------------------------------------------- |
| What time is it? | A question, not a proposition. Questions are not true or false.     |
| Are you awake?   | Even a yes/no question is neither true or false. Not a proposition. |
| Have a nice day. | A command, not a proposition. A command is neither true nor false.  |
#### Examples of propositions and their truth values.

| Sentence               | Comment                             |
| ---------------------- | ----------------------------------- |
| Two plus two is four.  | Truth value is true.                |
| Two plus two is five.  | Truth value is false.               |
| Monday will be cloudy. | Truth value is unknown.             |
| The movie was funny.   | Truth value is a matter of opinion. |

## The [[Conjunction]] Operation:

The [[Proposition]] *p* ∧ q  is read "*p* and *q*" and is called the [[Conjunction]] of *p* and *q*.

*p* ∧ *q* is only ***true*** if both *p* and *q* are ***true***. 

Lets say: 
- *p*: January has 31 days.
- *q*: February has 33 days.

[[Proposition]] *p*'s truth value is true. January has 31 days. 
[[Proposition]] *q*'s truth value is false. February does not have 33 days. 

*p* ∧ *q* = False, because one of these isn't true. 

Below is a [[Truth Table]] for the [[Conjunction]] operation: 

| *p*       | *q*       | *p* ∧ *q* |
| --------- | --------- | --------- |
| ==**T**== | ==**T**== | ==**T**== |
| ==**T**== | F         | F         |
| F         | ==**T**== | F         |
| F         | F         | F         |
#### Different ways to express a [[conjunction]] in English

*p*: The sauce looks disgusting.
*h*: The sauce tastes delicious. 

| *p* & *h*                      | Description                                                            |
| ------------------------------ | ---------------------------------------------------------------------- |
| *p* and *h*                    | The sauce looks disgusting and tastes delicious.                       |
| *p*, but *h*                   | The sauce looks disgusting, but tastes delicious.                      |
| despite the fact that *p*, *h* | Despite the fact that the sauce looks disgusting, it tastes delicious. |
| Although *p*, *h*              | Although the sauce looks disgusting, it tastes delicious.              |

## The [[Disjunction]] Operation:

The [[Proposition]] *p* ∨ *q*  is read "*p* or *q*" and is called the [[Disjunction]] of *p* and *q*.

*p* ∨ *q* is ***only*** false if both *p* and *q* are ***False***. 

Lets say: 
- *p*: January has 31 days.
- *q*: February has 33 days.

[[Proposition]] *p*'s truth value is true. January has 31 days. 
[[Proposition]] *q*'s truth value is false. February does not have 33 days. 

*p* ∨ *q*  = True, because one of these is true. 

Below is a [[Truth Table]] for the [[Disjunction]] operation: 

| *p*       | *q*       | *p* ∨ *q* |
| --------- | --------- | --------- |
| ==**T**== | ==**T**== | ==**T**== |
| ==**T**== | F         | ==**T**== |
| F         | ==**T**== | ==**T**== |
| F         | F         | F         |
The only time [[Inclusive Or]] and [[Exclusive or]] have different truth values is when *p* = *q* = T. 

## The [[Negation]] Operation:

This one is quite simple. [[Truth Table]] is below: 

| p         | -p        |
| --------- | --------- |
| ==**T**== | F         |
| F         | ==**T**== |




# Exercises Todo: 

- [x] 1.1.1
- [x] 1.1.2
- [x] 1.1.3
- [x] 1.1.4