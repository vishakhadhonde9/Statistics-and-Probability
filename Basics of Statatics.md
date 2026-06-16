# Statistics and Probability 
- Statistics and Probability form the mathematical foundation of Machine Learning.
- Before building models, we need to understand how data behaves, how uncertainty is measured, and how patterns are discovered from data.

# 1. Types of Data
- Data is a collection of observations, measurements, or facts used for analysis.
- Understanding the type of data is important because different statistical methods are applied to different data types.

## A. Categorical Data (Qualitative Data)
- Categorical data represents labels, names, or categories rather than numerical values.

### 1. Nominal Data
- Nominal data consists of categories with no natural order.
- Examples:

- Gender: Male, Female
- Blood Group: A, B, AB, O
- Country: India, USA, Japan

Characteristics:

- Categories cannot be ranked.
- Mathematical operations cannot be performed.
- Used mainly for classification tasks.

Example:

Red, Blue, Green

There is no meaningful order among these colors.


### 2. Ordinal Data

Ordinal data consists of categories that have a meaningful order.

Examples:

Low < Medium < High

Poor < Average < Good < Excellent

Characteristics:

- Ranking exists.
- Difference between categories is not measurable.

Example:

If Student A has rank 1 and Student B has rank 2, we know A performed better, but we do not know by how much.


## B. Numerical Data (Quantitative Data)

Numerical data contains measurable quantities.

### 1. Discrete Data

Discrete data can only take specific countable values.

Examples:

- Number of students in a class
- Number of cars in a parking lot
- Number of emails received

Characteristics:

- Countable
- Usually integers
- Obtained through counting

Example:

0, 1, 2, 3, 4 ...

---

### 2. Continuous Data

Continuous data can take any value within a range.

Examples:

- Height
- Weight
- Temperature
- Time

Characteristics:

- Infinite possible values
- Obtained through measurement

Example:

170.5 cm

170.55 cm

170.555 cm


# 2. Measures of Central Tendency

Central tendency describes the center or typical value of a dataset.

The three major measures are:

1. Mean
2. Median
3. Mode



# Mean

The mean is the arithmetic average of all observations.

Formula:

Mean = (Σxi) / n

Where:

- xi = observation
- n = total observations

Example:

Dataset:

10, 20, 30, 40, 50

Calculation:

Mean = (10 + 20 + 30 + 40 + 50) / 5

Mean = 150 / 5

Mean = 30

## Importance of Mean

The mean uses every observation in the dataset.

Advantages:

- Easy to calculate
- Uses all values

Disadvantages:

- Sensitive to outliers

Example:

10, 20, 30, 40, 500

Mean becomes:

600 / 5 = 120

The value 500 heavily influences the mean.


# Median

The median is the middle value of a sorted dataset.

Steps:

1. Sort the data.
2. Find the middle observation.

Example:

10, 20, 30, 40, 50

Median = 30

## Median for Even Number of Observations

Dataset:

10, 20, 30, 40

Middle values:

20 and 30

Median = (20 + 30) / 2

Median = 25

## Importance of Median

Advantages:

- Not affected by outliers.
- Better for skewed data.

Example:

10, 20, 30, 40, 500

Median = 30

Even though 500 is very large, the median remains stable.


# Mode

Mode is the most frequently occurring value.

Example:

10, 20, 20, 30, 40

Mode = 20

## Types of Mode

### Unimodal

One mode

1, 2, 2, 3, 4

Mode = 2

### Bimodal

Two modes

1, 2, 2, 3, 3, 4

Modes = 2 and 3

### Multimodal

More than two modes

1, 1, 2, 2, 3, 3

Modes = 1, 2, 3



# 3. Measures of Dispersion

Central tendency tells where data is centered.

Dispersion tells how spread out data is.

Common measures:

1. Range
2. Variance
3. Standard Deviation


# Range

Range measures the difference between largest and smallest value.

Formula:

Range = Maximum - Minimum

Example:

10, 20, 30, 40, 50

Range = 50 - 10

Range = 40


# Variance

Variance measures the average squared deviation from the mean.

It indicates how far observations are spread around the mean.

Population Variance Formula:

σ² = Σ(xi - μ)² / N

Where:

- xi = observation
- μ = mean
- N = population size

## Why Squaring?

Without squaring:

-10 + 10 = 0

Positive and negative deviations cancel each other.

Squaring makes every deviation positive.


# Standard Deviation

Standard deviation is the square root of variance.

Formula:

σ = √σ²

Interpretation:

- Small standard deviation → Data is concentrated near mean.
- Large standard deviation → Data is widely spread.

## Importance in Machine Learning

Many algorithms use standard deviation:

- Z-score normalization
- Gaussian Naive Bayes
- PCA
- Statistical testing



