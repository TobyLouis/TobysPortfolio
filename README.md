# Welcome to my Portfolio!
Hello! My name is Toby Trotta, an early-career professional seeking a data scientist or data analyst role. Residing in the greater Pittsburgh region, I earned a Bachelor of Science in Mathematics with a concentration in Actuarial Science from Edinboro University of Pennsylvania (EUP) (now Pennsylvania Western University), where I developed a strong interest in statistics and programming.

My academic foundation began with learning the core principles of data science, statistical programming, machine learning, and parallel computing using RStudio, leading to a lasting proficiency in—and appreciation for—the R programming language. During my graduate studies at Indiana University of Pennsylvania (IUP), I expanded my technical toolkit by working primarily in Python, developing both probabilistic and deterministic operations research models, as well as conducting data science analyses using libraries such as Pandas, SciPy, scikit-learn, and statsmodels within Jupyter Notebook and Google Colab environments.

I invite you to explore my growing portfolio, beginning with selected work from my thesis, *A General Class of Additive Parametric Models for Recurrent Event Data*. This project presents the theoretical development and empirical testing of an intervention-based effective age model, completed under the guidance of Dr. Russell Stocker IV.

# 🎓 :page_facing_up: A General Class of Additive Parametric Models for Recurrent Event Data

My master's thesis was advised by Dr. Russell Stocker, IV, Associate Professor of Mathematics at Indiana University of Pennsylvania's Department of Mathematical and Computer Sciences. The full text can be found on [ProQuest](https://www.proquest.com/openview/408ecd24e6e05b01b624ef0013797b3b/1?pq-origsite=gscholar&cbl=18750&diss=y).

*The graphics in this section were created using a combination of RStudio packages: `ggplot`, `tikzDevice`, and `latex2exp`.*

*Abstract:* We propose a general class of additive parametric models to analyze recurrent event data that uses the effective age process given in Peña and Hollander [1]. We assume a negligible intervention effect is applied to each unit after an observed event which may be classified as perfect, minimal, or partial. Estimators are derived and their asymptotic properties are established under regularity conditions that are formulated using doubly-indexed processes. We investigate the finite sample properties via a simulation study in RStudio. The simulation study shows minimal and decreasing bias in the maximum likelihood estimators, and that the standard errors can be approximated using the inverse observed information matrix. The model and asymptotic properties are used to examine the indolent non-Hodgkin’s lymphoma data set from Gonzalez, Peña, and Slate. [2]

***Effective Age Process***: The effective age process under Peña and Hollander [2], which is an observable process \{ $\mathcal{E}_{i}(s) | 0 \leq s < \infty$ \} that describes the operating age of the unit, must adhere to the following conditions:

| Effective Age Process |
| :--- |
| Must be nonnegative |
| The value at time 0 is $c$ for any $c \in \mathbb{R}^+$ |
| Must be monotone and almost surely differentiable with positive derivative $E_{i}'(s)$ on the interval $(S_{ij-1}, S_{ij}]$ |

<img width="1137" height="768" alt="effectiveAgeProcess" src="https://github.com/user-attachments/assets/2430159c-fd5b-4f1b-ae9f-08c38d4f58cf" />

We let the random variable *S* represent the time when a unit experiences an event of interest. We propose the model below as a function consisting of a baseline parametric hazard function, $\lambda_0(\mathcal{E}_i(s) | \theta)$, and an additive link function $\beta^T \mathbf{X}_i$. Assigning $\beta = (\beta_1, \beta_2, ..., \beta_p)^T$ to be a vector of regression parameters associated with the time-*independent* covariate vector $X_i = (X_1, X_2, ..., X_p)^T$, the following model is created:

$$\lambda_i(s|\boldsymbol{\theta, \boldsymbol{\beta}}) = \lambda_0(\mathcal{E}_i(s)|\boldsymbol{\theta}) + \beta^TX_i$$

### :hospital: Applications of the Model: non-Hodgkins Lymphoma Data

***Brief Background:*** Non-Hogdkins Lymphoma (NHL) is a class of lymphatic cancer diagnoses that can be partitioned into two groups: indolent and aggressive. Indolent NHL is slower-progressing, generally having longer survival processes. It is understood that patients with NHL tend to experience several relapses over time. [3]

**References:**
[1] E. Peña and M. Hollander, *Mathematical Reliability: An Expository Perspective*,
Springer, 2004, ch. 6: Models for Recurrent Events in Reliability and Survival
Analysis, pp. 105–123.

[2] J. Gonzalez, E. Peña, and E. Slate, *Modelling intervention effects after cancer
relapses*, Stat Med., 24 (2005), pp. 3959–3975.

[3] N Delinger, N. Epperla, and B. William, *Management of relapsed/refractory martinal zone lymphoma: focus on ibrutinib*, Cancer Management and Research 10 (2018), pp. 615-624.

# :computer: :chart_with_upwards_trend: RStudio Workshop

As a Research Assistant with IUP's Applied Research Lab (ARL), I was given the opportunity to host an RStudio Programming Workshop during IUP's Research Appreciation Week. During this two-day workshop, I instructed a class of approximately 10 participants. I encourage those who are interested in learning RStudio to view both the blank RMarkdown worksheets for practice and the respective "Key" files for answers at your own pace. :blush:
