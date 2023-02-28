# Joint Coverage Regions (JCRs)
Code and figures for the paper
## Joint Coverage Regions: Simultaneous Confidence and Prediction Sets
The Joint Coverage Region (JCR) is a novel statistical concept that unifies confidence intervals and prediction regions 
in frequentist statistics. Specifically, JCRs are designed to cover a pair formed by an unknown fixed parameter and an unobserved random datapoint. 
The first corresponds to a confidence component, while the second corresponds to a prediction part.
We aim to construct such regions with finite-sample coverage guarantees.

The figure below illustrates a JCR
for a toy model where $X_1,X_2 \sim N(\theta,1)$ independently, but we only observe $X_1$, and want to cover the pair $(\theta,X_2)$.
For contrast, we also plot a confidence interval for $\theta$ and a prediction region for $X_2$.
The purple point labeled "Truth" shows the true realization in this trial.
It is shown that the JCR corresponds to any region in $(\theta,X_2)$-space; while a confidence interval for $\theta$ can be viewed as a 
horizontal strip and a prediction interval for $X_2$ can be viewed as a vertical strip.
<img src="https://user-images.githubusercontent.com/124510232/221736527-38638737-8aba-48a8-8d1c-014a8371feca.png" >
See our paper for details.
