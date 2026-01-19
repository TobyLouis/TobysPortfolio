# Welcome to my Portfolio!
Hello! My name is Toby Trotta, an early-career professional, in search of a data scientist/analyst role. From the Pittsburgh area, I earned my Bachelor of Science in Mathematics: Actuarial Science from Edinboro University of Pennsylvania *(currently Pennsylvania Western University)*, where I grew fond of statistics and programming, and the familiarity of version-control softwares, such as GitHub. First learning the fundamentals of data science, statistical programming, machine learning, and parallel processing in RStudio, I have developed a strong bond with the R programming language. My graduate studies were primarily concerned with using Python to develop probabalistic and deterministic operations research models, and for data science (such as Pandas, sciPy, sklearn, statsmodels) using both JupyterNotebook and GoogleColab. I welcome you to view my growing portfolio, beginning with excerpts from my thesis, *A General Class of Additive Parametric Models for Recurrent Event Data*, a theoretical creation and testing of an intervention-based effective age model, advised by Dr. Russell Stocker, IV.

# A General Class of Additive Parametric Models for Recurrent Event Data

My master's thesis, advised by Dr. Russell Stocker IV, of the Indiana University of Pennsylvania's Department of Mathematical and Computer Sciences.

*Abstract:* We propose a general class of additive parametric models to analyze recurrent event
data that uses the effective age process given in Peña and Hollander. We assume a negligible
intervention effect is applied to each unit after an observed event which may be classified
as perfect, minimal, or partial. Estimators are derived and their asymptotic properties are
established under regularity conditions that are formulated using doubly-indexed processes.
We investigate the finite sample properties via a simulation study in RStudio. The simulation
study shows minimal and decreasing bias in the maximum likelihood estimators, and that
the standard errors can be approximated using the inverse observed information matrix. The
model and asymptotic properties are used to examine the indolent non-Hodgkin’s lymphoma
data set from Gonzalez, Peña, and Slate.

## Applications of the Model: non-Hodgkins Lymphoma Data

*Brief Background:* Non-Hogdkins Lymphoma (NHL) is a class of lympatic cancer diagnoses that can be partitioned into two groups: indolent and aggressive. Indolent NHL is slower-progressing, generally having longer survival processes. It is understood that patients with NHL tend to experience several relapses over time. [1]

The model:

$$\delta$$

References:
[1] N Delinger, N. Epperla, and B. William, *Management of relapsed/refractory martinal zone lymphoma: focus on ibrutinib*, Cancer Management and Research 10 (2018), pp. 615-624.
