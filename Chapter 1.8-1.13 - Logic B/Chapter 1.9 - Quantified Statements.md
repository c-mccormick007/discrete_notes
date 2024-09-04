# [[Discrete Computing]]
**Date:** 2024-09-01
#notes #discreet

## Key Terms:

![[Quantified Statements]]
![[Free Variable]]
![[Bound Variable]]
![[Translation of Quantified Statements]]

## [[Quantified Statements]]

### Predicates:
- **$P(x)$**: $x$ is prime
- **$O(x)$**: $x$ is odd

### Propositions:
- **$\exists x(P(x) \land \neg O(x))$**: There exists a positive number that is prime and not odd.
  - True for $x = 2$ since $2$ is prime and not odd.
- **$\forall x(P(x) \rightarrow O(x))$**: For every positive integer $x$, if $x$ is prime, then $x$ is odd.
  - False for $x = 2$ since $2$ is prime but not odd.

### Quantified Statements:
- **Quantified statements** involve logical statements with universal ($\forall$) or existential ($\exists$) quantifiers applied before logical operations ($\land$, $\lor$, $\rightarrow$, $\leftrightarrow$).
  - Example: **$\forall x(P(x) \land Q(x))$** is equivalent to **$(\forall xP(x)) \land (\forall xQ(x))$**.

## [[Free Variable]] and [[Bound Variable]]

- **Free Variable**: A variable that is not bound by a quantifier and can take any value in the domain.
- **Bound Variable**: A variable that is bound to a quantifier, giving the statement a definite truth value.

### Example:
- **$\forall x(P(x) \land Q(x))$**: $x$ in $P(x)$ is bound, but $x$ in $Q(x)$ is not, making the statement not a proposition.
- **$\forall x(P(x) \land \forall x Q(x))$**: Both occurrences of $x$ are bound, making the statement a proposition.

## [[Translation of Quantified Statements]]

### Translating English to Logic:
- **$P(x)$**: $x$ came to the party
- **$S(x)$**: $x$ was sick

### Example:
- "Everyone was not sick" translates to **$\forall x \neg S(x)$**.
- "Someone was sick and came to the party" translates to **$\exists x(S(x) \land P(x))$**.

### Example Table 1.9.1:
| Name      | $S(x)$ | $P(x)$ |
| --------- | ---- | ---- |
| Joe       | F    | T    |
| Theodore  | T    | F    |
| Gertrude  | T    | T    |
| Samuel    | F    | F    |

### Translating quantified statements from English to Logic:
- **$R(x)$**: Person $x$ read the proposal.
- **$V(x)$**: Person $x$ voted in favor of the proposal.

1. **Everyone who read the proposal voted in favor of it**: **$\forall x(R(x) \rightarrow V(x))$**
2. **Someone who did not read the proposal voted in favor of it**: **$\exists x(\neg R(x) \land V(x))$**
3. **Someone did not read the proposal, and someone voted in favor of it**: **$\exists x\neg R(x) \land \exists xV(x)$**

---

### Exercises Todo:
- [ ] 1.9.1
- [ ] 1.9.2
- [ ] 1.9.3
- [ ] 1.9.4
- [ ] 1.9.5
- [ ] 1.9.6
- [ ] 1.9.7
- [ ] 1.9.8
- [ ] 1.9.9
- [ ] 1.9.10
