# Chapter 3: Probability



## 3.1) Basic terminology:

A. **Experiment/Trial**: A process that produces a set of outcomes that are uncertain, e.g., flipping a coin.

B. **Sample Space**: The set of all possible outcomes of an experiment, e.g., {heads, tails} for flipping a coin.

C. **Event**: A subset of the sample space. It represents a set of outcomes that we are interested in, e.g., rolling a die and getting an even number is {2, 4, 6}.

D. **Exhaustive Case**: A situation where all possible outcomes in a sample space are included in one or more events, e.g., in rolling a die, the exhaustive cases are rolling a number between 1 to 6.

E. **Mutually Exclusive Events**: A situation where the occurrence of one event precludes the occurrence of the other, e.g., in rolling a die, the events of getting an odd number and getting an even number are mutually exclusive.

F. **Dependent Events**: A situation where the probability of an event is influenced by the occurrence or non-occurrence of another event, e.g., when drawing two cards from a deck without replacement, the probability of drawing a second card of a certain suit depends on the suit of the first card drawn.

G. **Independent Events**: A situation where the probability of an event is not influenced by the occurrence or non-occurrence of another event, e.g., when flipping a coin twice, the outcome of the first flip does not influence the outcome of the second flip.

## 3.2) Probability


$$P(A) = \frac{n(A)}{n(S)}$$

where $A$ is an event, $n(A)$ is the number of outcomes favorable to event $A$, and $n(S)$ is the total number of possible outcomes in the sample space $S$.

All other related formula of probability are the same as the formula for Sets.

## 2.3) Conditional Probability

$P(A|B)$ is the conditional probability of event $A$ given event $B$ has occurred, $P(A \cap B)$ is the probability of the intersection of events $A$ and $B$, and $P(B)$ is the probability of event $B$. 
It is also denoted by $P(\frac{A}{B})$ .
$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

where $A$ and $B$ are events, and $P(B) \neq 0$.


## 2.4) Bayes Theorem

$$P(A|B) = \frac{P(B|A)P(A)}{P(B)}$$

where $A$ and $B$ are events, and $P(B)\neq 0$.

$P(A|B)$ is the conditional probability of event $A$ given event $B$ has occurred, $P(B|A)$ is the conditional probability of event $B$ given event $A$ has occurred, and $P(A)$ and $P(B)$ are the marginal probabilities of events $A$ and $B$, respectively.


