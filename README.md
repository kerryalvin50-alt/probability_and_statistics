# probability_and_statistics
either yes or no

Repository Directory
01-probability/: Foundations of probability, set theory, conditional probability, Bayes' Theorem, and discrete/continuous random variables.

02-descriptive-stats/: Measures of central tendency (mean, median, mode), variance, standard deviation, skewness, and exploratory data analysis (EDA).

03-inferential-stats/: Hypothesis testing (
𝑧
z-tests, 
𝑡
t-tests, ANOVA), confidence intervals, 
𝑝
p-values, and Type I/II errors.

04-probability-distributions/: Key probability mass and density functions including Binomial, Poisson, Normal, Exponential, and Student's 
𝑡
t.

05-regression-and-modeling/: Simple and multiple linear regression, logistic regression, and model evaluation metrics (MSE, 
𝑅
2
R 
2
 , AUC-ROC).

📈 Core Concept Highlight: Normal Distribution
The normal (Gaussian) distribution is the cornerstone of statistical inference, heavily tied to the Central Limit Theorem, which states that the distribution of sample means approximates a normal distribution as sample size increases, regardless of the population's underlying distribution.

Opens in a new window
Source: Made with Google AI
Normal distribution curves showing sample variability. Source: Made with Google AI
📐 Essential Formulas & Theorems
1. Bayes' Theorem
Crucial for updating probabilities given new evidence, foundational to Naive Bayes classifiers and Bayesian statistics:

𝑃
(
𝐴
∣
𝐵
)
=
𝑃
(
𝐵
∣
𝐴
)
𝑃
(
𝐴
)
𝑃
(
𝐵
)
P(A∣B)= 
P(B)
P(B∣A)P(A)
​
 
2. Expected Value and Variance
For a discrete random variable 
𝑋
X:

Expected Value: 
𝐸
[
𝑋
]
=
∑
𝑥
𝑖
𝑃
(
𝑥
𝑖
)
E[X]=∑x 
i
​
 P(x 
i
​
 )

Variance: 
Var
(
𝑋
)
=
𝐸
[
(
𝑋
−
𝐸
[
𝑋
]
)
2
]
Var(X)=E[(X−E[X]) 
2
 ]

🚀 Recommended Practice Projects
A/B Testing Power Calculator: Build a Python script or notebook to calculate sample size requirements and statistical power for product experiments.

Spam Detection Filter: Implement a Naive Bayes classifier from scratch using Bayes' theorem on text token frequencies.

Housing Price Predictor: Perform exploratory data analysis (EDA) and fit multiple linear regression models on real estate datasets.
