# Joint Coverage Regions (JCRs)
Code and figures for the paper
## Joint Coverage Regions: Simultaneous Confidence and Prediction Sets

by E. Dobriban and Z. Lin, [https://arxiv.org/abs/2303.00203](https://arxiv.org/abs/2303.00203).

Joint Coverage Regions (JCRs) are a novel statistical concept that unifies confidence intervals/sets and prediction regions 
in standard frequentist statistics. Specifically, JCRs are designed to cover a *pair* formed by an unknown fixed parameter and an unobserved random datapoint. 
The first corresponds to a confidence component, while the second corresponds to a prediction part.
We aim to construct JCRs that have valid coverage; in finite samples or asymptotically.


In particular, JCRs unify the classical notions of confidence intervals (such as standard Z and t-intervals), and
modern distribution-free methods for predictive inference (specifically conformal prediction)


The figure below illustrates a JCR
for a simplified model where $X_1,X_2 \sim \mathcal{N}(\theta,1)$ independently, but we only observe $X_1$, and want to cover the pair $(\theta,X_2)$.
For contrast, we also plot a confidence interval for $\theta$, which appears here as a vertical band, because it does not provide
any information about $X_2$.
Similarly, we also plot a prediction region for $X_2$; which appears as a horizontal band.
The purple point labeled "Truth" shows the true realization in this trial.
A JCR corresponds to any region in $(\theta,X_2)$-space that covers the truth with at the desired level.
<img src="https://user-images.githubusercontent.com/124510232/221736527-38638737-8aba-48a8-8d1c-014a8371feca.png" >
See our paper for details.
