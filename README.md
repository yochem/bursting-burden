# Bursting the Burden Bubble

**An assessement of Sharma et al.'s Counterfactual-Based Fairness Metric.**

By Yochem van Rosmalen, Florian van der Steen, Sebastiaan Jans, and Daan van
der Weijden.

Submitted to BNAIC/BeNeLearn 2022 conference
[[link](https://bnaic2022.uantwerpen.be/)].

### Abstract

Machine learning has seen an increase in negative publicity in recent years,
due to biased, unfair, and uninterpretable models. There is a rising interest
in making machine learning models more fair for unprivileged communities, such
as women or people of color. Metrics are needed to evaluate the fairness of a
model. A novel metric for evaluating fairness between groups is Burden, which
uses counterfactuals to approximate the average distance of negatively
classified individuals in a group to the decision boundary of the model. The
goal of this study is to compare Burden to statistical parity, a well-known
fairness metric, and discover Burden's advantages and disadvantages. We do this
by calculating the Burden and statistical parity of a sensitive attribute in
three datasets: two synthetic datasets are created to display differences
between the two metrics, and one real-world dataset is used. We show that
Burden can be more nuanced than statistical parity, but also that the metrics
can disagree on which group is treated unfairly. We therefore conclude that
Burden is a valuable metric to add to the existing group of fairness metrics,
but should not be used on its own.

Read the full paper at [bursting-burden.pdf](paper/bursting-burden.pdf)!
