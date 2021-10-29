## <center> Probabilistic Graphical Model</center>



#### 1 Markov Network

##### 1.1 Definition

A Markov Network (alias Markov Random Field) is defined by:

- A set of **random variables** $X = (X_1,\dots, X_n)$

- **Undirected graph** $G$, with vertices corresponding to random variables.
- Non-negative **potential functions** $\{\phi_k\}$.
- Each (maximum) **clique** $c\in C$ of $G$ is assigned with a corresponding potential function.

The joint distribution represented by a Markov network is:
$$
P(X = x) = \frac{1}{Z} \prod_{c\in C}\phi_c(x_c)
$$

- where $Z$  normalizes the probability and is often referred to as the **partition function**.



##### 1.2 Properties

Markov networks are often expressed as log-linear models, in which the potential functions is replaced by an exponentiated weighted sum of features:
$$
P(X = x) = \frac{1}{Z} \exp \left(\sum_{j}w_j f_j(x)\right)
$$


#### 2 Markov Logical Network

(See [Link](https://homes.cs.washington.edu/%7Epedrod/papers/mlj05.pdf))

##### 2.1 First-order Knowledge Base

A first-order knowledge base is a set of formulas in first-order logic, constructed using four types of symbols: constants, variables, functions, and predicates. A first-order KB can also be viewed as a set of hard constraints: If a *possible world* violates even one formula, it has zero probability.

*Markov logical network* softens these hard constraints (formulas), and uses weights to represent how strong a constraint is.

##### 2.2 M