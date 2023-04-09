# probabiliTree
A branching repository of probability concepts, from foundational principles to advanced applications.


# Sample Space
In probability theory, a sample space is the set of all possible outcomes of an experiment or random process. It is denoted by the symbol "S" and is the basis for defining probabilities of events. The sample space includes all possible outcomes, whether they are desirable or not. For example, when tossing a coin, the sample space is {heads, tails}, and when rolling a die, the sample space is {1, 2, 3, 4, 5, 6}. The sample space can be finite or infinite and can be simple or complex depending on the complexity of the experiment or process. The sample space is a fundamental concept in probability theory and is used to calculate probabilities of events, which are subsets of the sample space.

Three conditions for the event of the sample space:

* **Mutually exclusive**: This means that the outcomes in the sample space should not overlap. In other words, only one outcome can occur at a time. For example, when flipping a coin, the outcomes "heads" and "tails" are mutually exclusive because only one of them can occur.

* **Collectively exhaustive**: This means that the outcomes in the sample space should cover all possible outcomes of the experiment or process. In other words, every possible outcome should be included in the sample space. For example, when rolling a die, the outcomes {1, 2, 3, 4, 5, 6} are collectively exhaustive because they cover all possible outcomes of the experiment.

* We should determine **the right scale/granularity** to define the outcomes in the sample space for the problem at hand. In other words, the elements of the sample space should be neither too broad nor too specific. For example, if the experiment is to determine the color of a car, the sample space should include only the possible colors of the car, not the make or model of the car. Similarly, if the experiment is to determine the number of cars in a parking lot, the sample space should include only the possible integer values for the number of cars, not fractions or decimals.

***

# Probabilistic Models

In this blog post, we will introduce the basic concepts of probabilistic models, which are mathematical tools for reasoning about uncertainty and randomness. We will see how to define a probabilistic model using two main elements: a sample space and a probability law. We will also learn about the three fundamental axioms of probability theory and some properties that follow from them.

## Elements of a probabilistic model

A probabilistic model consists of two components:

- A **sample space**, denoted by $\Omega$, which is the set of all possible outcomes of an experiment or a random phenomenon. For example, if we toss a coin, the sample space is $\Omega = \{H, T\}$, where $H$ stands for heads and $T$ stands for tails. If we roll a six-sided die, the sample space is $\Omega = \{1, 2, 3, 4, 5, 6\}$.

- A **probability law**, denoted by $P$, which is a function that assigns a number between 0 and 1 to each subset of the sample space, called an **event**. The number $P(A)$ represents the likelihood or the degree of belief that the event $A$ occurs. For example, if we toss a fair coin, the probability law is $P(\{H\}) = P(\{T\}) = 0.5$, meaning that both heads and tails have equal chances of occurring. If we roll a fair die, the probability law is $P(\{i\}) = \frac{1}{6}$ for any $i \in \{1, 2, 3, 4, 5, 6\}$.

## Probability Axioms

The probability law must satisfy three basic rules, called the **probability axioms**:

- **Nonnegativity**: For any event $A$, $P(A) \geq 0$. This means that probabilities are always nonnegative numbers.

- **Additivity**: For any two disjoint events $A$ and $B$, meaning that they have no common outcomes, $P(A \cup B) = P(A) + P(B)$. This means that the probability of either event occurring is equal to the sum of their individual probabilities.

- **Normalization**: For the entire sample space $\Omega$, $P(\Omega) = 1$. This means that the probability of something happening is equal to one.

## Properties that follow from the axioms

Using these three axioms, we can derive many useful properties of probabilities. Here are some examples:

- For any event $A$, $P(A^c) = 1 - P(A)$, where $A^c$ is the complement of $A$, meaning the set of outcomes that are not in $A$. This means that the probability of an event not occurring is equal to one minus the probability of it occurring.

- For any two events $A$ and $B$, $P(A \cup B) = P(A) + P(B) - P(A \cap B)$, where $A \cap B$ is the intersection of $A$ and $B$, meaning the set of outcomes that are in both events. This means that the probability of either event occurring is equal to the sum of their individual probabilities minus the probability of both events occurring.

- For any finite or countably infinite sequence of disjoint events $A_1, A_2, A_3, ...$, meaning that they have no common outcomes, $P(\bigcup_{i=1}^{\infty} A_i) = \sum_{i=1}^{\infty} P(A_i)$. This means that the probability of at least one event occurring is equal to the sum of their individual probabilities.

These are some of the basic concepts and properties of probabilistic models. In future posts, we will explore more advanced topics such as conditional probability, Bayes' theorem, independence, random variables and distributions.
