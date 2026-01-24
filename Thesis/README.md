## A General Class of Additive Parametric Models for Recurrent Event Data
*Toby L. Trotta, August 2024; Advised by: Dr. Russell S. Stocker*

This project presents the theoretical development and empirical testing of an intervention-based effective age model.

***Effective Age Process***: The effective age process under Peña and Hollander [2], which is an observable process \{ $\mathcal{E}_{i}(s) | 0 \leq s < \infty$ \} that describes the operating age of the unit, must adhere to the following conditions:

| Effective Age Process |
| :--- |
| Must be nonnegative |
| The value at time 0 is $c$ for any $c \in \mathbb{R}^+$ |
| Must be monotone and almost surely differentiable with positive derivative $E_{i}'(s)$ on the interval $(S_{ij-1}, S_{ij}]$ |

<img width="567" height="384" alt="effectiveAgeProcess" src="https://github.com/user-attachments/assets/2430159c-fd5b-4f1b-ae9f-08c38d4f58cf" />

The unit is subject to some censoring time, $\tau_i$, in which no further information can be provided to the model. Data can be left-, right-, or interval-censored. A unit is considered "left-censored" when the event of interest occurs *before* the observation was noted or collected. A unit is considered "right-censored," which is the most common, when the unit is removed from the study *prior* to the event of interest being noted (ie. due to death or relocation). Finally, a unit is considered "interval-censored" when the exact time the event of interest occurred is not known, but we know that the event occurred within some structured interval of time. For this thesis, we considered right-censored data.

We let the random variable *S* represent the time when a unit experiences an event of interest. We propose the model below as a function consisting of a baseline parametric hazard function, $\lambda_0(\mathcal{E}_i(s) | \theta)$ and an additive link function $\beta^T \mathbf{X}_i$. Assigning $\beta = (\beta_1, \beta_2, ..., \beta_p)^T$ to be a vector of regression parameters associated with the time-*independent* covariate vector $X_i = (X_1, X_2, ..., X_p)^T$, the following model is created:

$$\lambda_i(s|\boldsymbol{\theta, \boldsymbol{\beta}}) = \lambda_0(\mathcal{E}_i(s)|\boldsymbol{\theta}) + \beta^TX_i$$

### :hospital: Applications of the Model: non-Hodgkins Lymphoma Data

***Brief Background:*** Non-Hogdkins Lymphoma (NHL) is a class of lymphatic cancer diagnoses that can be partitioned into two groups: indolent and aggressive. Indolent NHL is slower-progressing, generally having longer survival processes. It is understood that patients with NHL tend to experience several relapses over time. [3]

***More to come...***

**References:**

[1] E. Peña and M. Hollander, *Mathematical Reliability: An Expository Perspective*,
Springer, 2004, ch. 6: Models for Recurrent Events in Reliability and Survival
Analysis, pp. 105–123.

[2] J. Gonzalez, E. Peña, and E. Slate, *Modelling intervention effects after cancer
relapses*, Stat Med., 24 (2005), pp. 3959–3975.

[3] N Delinger, N. Epperla, and B. William, *Management of relapsed/refractory martinal zone lymphoma: focus on ibrutinib*, Cancer Management and Research 10 (2018), pp. 615-624.

