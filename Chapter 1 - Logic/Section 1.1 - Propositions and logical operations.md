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

## 1.1.1: Determine Whether Each Sentence is a [[Proposition]]

### (a) Have a nice day.

- **Proposition:** No
- **Reason:** This is a command, not a statement that can be true or false.

### (b) The soup is cold.

- **Proposition:** Yes
- **Negation:** The soup is not cold.

### (c) The patient has diabetes.

- **Proposition:** Yes
- **Negation:** The patient does not have diabetes.

### (d) The light is on.

- **Proposition:** Yes
- **Negation:** The light is not on.

### (e) It's raining today.

- **Proposition:** Yes
- **Negation:** It is not raining today.

### (f) Do you like my new shoes?

- **Proposition:** No
- **Reason:** This is a question, not a statement that can be true or false.

### (g) The sky is purple.

- **Proposition:** Yes
- **Negation:** The sky is not purple.

### (h) 2 + 3 = 6

- **Proposition:** Yes
- Negation: 2 plus 3 does not equal six. 

### (i) Every prime number is even.

- **Proposition:** Yes
- **Negation:** Not every prime number is even (or There exists a prime number that is not even).

### (j) There is a number that is larger than 17.

- **Proposition:** Yes
- **Negation:** There is no number that is larger than 17.


## 1.1.2: Expressing English sentences using logical notation.

Express each English statement using logical operations ∧, ∨, ¬ and the propositional variables *t*, *n*, *m* and defined below. The use of the word "or" means [[inclusive or]].

*t*: The patient took the medication. 
*n*: The patient had nausea.
*m*: The patient had migraines. 

### (a) The patient had nausea and migraines.

- *n* ∧ *m* 
### (b) The patient took the medication, but still had migraines.

- *t* ∧ *m*
### (c) The patient had nausea or migraines.

- *n* ∨ *m* 
### (d) The patient did not have migraines.

- ¬*m*
### (e) Despite the fact that the patient took the medication, the patient had nausea.

- *t* ∧ *n*
### (f) There is no way that the patient took the medication.

- ¬*t*


## 1.1.3: Applying [[logical operation|logical operations]]

Assume the propositions *p*, *q*, *r*, and *s* have the following truth values:

- *p* is false

- *q* is true

- *r* is false

- *s* is true

What are the truth values for the following compound propositions?
### (a) ¬*p*

- True
### (b) *p* ∨ *r*

- False
### (c) *q* ∧ *s* 

- True
### (d) *q* ∨ *s* 

- True
### (e) *q* ⊕ *s* 

-  False
### (f) *q* ⊕ *r* 

- True


## 1.1.4: Truth Values for statements with [[inclusive or]] [[exclusive or]]. 

Indicate whether each statement is true or false, assuming that the "or" in the sentence means the inclusive or. Then indicate whether the statement is true or false if the "or" means the exclusive or.

### (a) February has 31 days or the number 5 is an integer.

- This is true for both inclusive and exclusive or.
### (b) The number π is an integer or the sun revolves around the earth.

- This is false for both. 
### (c) 20 nickels are worth one dollar or whales are mammals.

- This is true for inclusive or, but it is false for exclusive or.
### (d) There are eight days in a week or there are seven days in a week. 

- This is true for both inclusive and exclusive or. 
### (e) January has exactly 31 days or April has exactly 30 days. 

- This is true for inclusive or, but not exclusive. 