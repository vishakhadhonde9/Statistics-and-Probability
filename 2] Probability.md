# Probability

Probability measures uncertainty.

It quantifies the likelihood of an event occurring.

Formula:

P(E) = Favorable Outcomes / Total Outcomes

## Probability Properties

### Rule 1

0 ≤ P(E) ≤ 1

### Rule 2

Impossible Event

P(E) = 0

### Rule 3

Certain Event

P(E) = 1

# Random Variable

A random variable is a numerical representation of outcomes.

Examples:

Coin Toss

Head = 1

Tail = 0

Dice Roll

1, 2, 3, 4, 5, 6



# Probability Mass Function (PMF)

PMF is used for discrete random variables.

It gives probability of exact values.

Example: Dice Roll

| X | P(X) |
|---|------|
| 1 | 1/6 |
| 2 | 1/6 |
| 3 | 1/6 |
| 4 | 1/6 |
| 5 | 1/6 |
| 6 | 1/6 |

Characteristics:

- Used for countable outcomes.
- Sum of probabilities equals 1.



 6. Probability Density Function (PDF)

PDF is used for continuous random variables.

Examples:

- Height
- Weight
- Temperature

Characteristics:

- Probability at a single point is zero.
- Area under curve equals 1.

Example:

Normal Distribution

      /\
    /    \
  /        \
/            \

Probability is measured by area under the curve.


 7. Data Distributions

A distribution describes how data values are spread.


# Normal Distribution

Most important distribution in Machine Learning.

Characteristics:

- Bell-shaped
- Symmetric
- Mean = Median = Mode

Examples:

- Human height
- IQ scores
- Measurement errors

## Empirical Rule

68% within 1 Standard Deviation

95% within 2 Standard Deviations

99.7% within 3 Standard Deviations

This is called the 68-95-99.7 Rule.


# Uniform Distribution

All outcomes equally likely.

Example:

Fair Dice

Every outcome:

P(X) = 1/6


# Skewed Distribution

Skewness measures asymmetry.

## Positive Skew

Long tail on right.

Mean > Median

Example:

Income Distribution

Few extremely rich people pull the mean upward.


## Negative Skew

Long tail on left.

Mean < Median

Example:

Very easy exam where most students score high.


# Binomial Distribution

Used when:

- Fixed number of trials
- Two outcomes

Examples:

- Head/Tail
- Pass/Fail
- Success/Failure

Formula:

P(X = k) = nCk × p^k × (1-p)^(n-k)

Applications:

- Email spam detection
- Customer conversion prediction


# Poisson Distribution

Used to model rare events.

Examples:

- Calls arriving per minute
- Website visits per hour
- Accidents per day

Characteristics:

- Counts occurrences in a fixed interval.
- Events occur independently.


8. Percentiles

Percentiles divide data into 100 equal parts.

Interpretation:

90th Percentile means:

90% observations lie below this value.

## Quartiles

### Q1

25th Percentile

### Q2

50th Percentile (Median)

### Q3

75th Percentile

## Importance

Used in:

- Exam rankings
- Salary analysis
- Outlier detection

---

# 9. Moments of Distribution

Moments describe shape and characteristics of a distribution.

## First Moment: Mean

Measures location or center.

Mean = E[X]

---

## Second Moment: Variance

Measures spread.

Variance = Var(X)

---

## Third Moment: Skewness

Measures asymmetry.

Positive Skewness:

Right Tail

Negative Skewness:

Left Tail

---

## Fourth Moment: Kurtosis

Measures heaviness of tails.

High Kurtosis:

- More extreme values
- More outliers

Low Kurtosis:

- Fewer outliers

---

# Why Statistics is Important in Machine Learning

Statistics helps us:

- Understand data
- Detect outliers
- Select features
- Normalize data
- Evaluate models
- Measure uncertainty
- Build probabilistic models

Machine Learning algorithms heavily depend on statistical concepts.

| ML Concept | Statistical Concept |
|------------|---------------------|
| Linear Regression | Mean, Variance |
| Logistic Regression | Probability |
| Naive Bayes | Conditional Probability |
| K-Means | Mean |
| PCA | Variance |
| Gaussian Naive Bayes | Normal Distribution |
| Hypothesis Testing | Probability Theory |

A strong understanding of Statistics and Probability is often more important than learning ML algorithms themselves because almost every ML algorithm is built on these mathematical foundations.
