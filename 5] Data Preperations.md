# Data Preparation -
- Data preparation is the process of converting raw, unstructured, and inconsistent data into a clean, structured, and usable format for data analysis, machine learning, and artificial intelligence models.
- Raw data collected from real-world sources is often incomplete, noisy, duplicated, inconsistent, or in different formats.
- Machine learning algorithms cannot directly work effectively with such data. Therefore, data preparation is required before applying any algorithm.

# Why Data Preparation is Important?
- Machine learning models learn patterns from data. If the input data is poor, the model will produce poor predictions.
#### Common problems in raw data:
- **Missing Data:** Missing values occur when some data fields do not have any recorded information.
- **Duplicate Data:** Duplicate records are repeated entries representing the same data.
- **Incorrect Data:** Data contains wrong or inaccurate values. e.g.-Age is 250 yrs.
- **Inconsistent Data:** Same information represented in different formats or values.
- e.g.-Different date formats: 01/07/2026, 2026-07-01 and July 1, 2026
- Different country names: USA, United States and US
- **Outlier:** Data points that are significantly different from normal observations.

# Steps in Data Preparation -
## 1.Data Collection -
- Data collection is the process of gathering raw data from different sources.
#### Data Sources -
- **Databases:** MySQL, PostgreSQL, Oracle and MongoDB.
- **APIs:** Applications communicate and exchange data using APIs.
- **Sensors / IoT Device:**
- **Files:** Common formats:CSV, Excel, JSON, XML and Text files.

## 2.Data Understanding -
### Activities in Data Understanding-
#### 1. Check Dataset Size -
- The first step is to determine the dimensions of the dataset.
- Rows (Records/Observations): Each row represents one data instance or observation.
- Columns (Features/Attributes): Each column represents a variable or characteristic.

#### 2. Identify Data Types -
- Understanding the type of each feature is essential because different data types require different preprocessing techniques.
##### 1. Numerical Data -
- Numerical data consists of values that can be measured or counted and supports mathematical operations.

##### Types of Numerical Data
- **a) Continuous Data:** Continuous data can take any value within a given range, including decimal values.
- **b) Discrete Data:** Discrete data contains countable values and usually consists of whole numbers.

#### 2. Categorical Data -
- Categorical data represents categories, groups, or labels rather than numerical quantities.

##### Types of Categorical Data -
**a) Nominal Data:** Nominal data consists of categories that have no natural order or ranking.
**b) Ordinal Data:** Ordinal data contains categories that follow a meaningful order or ranking, but the differences between categories are not necessarily equal.

#### Statistical Summary -
- Statistical Summary provides a quick numerical overview of a dataset.
- It helps understand the central tendency, spread, and distribution of the data.

## 3. Data Cleaning -
- Data Cleaning (also called Data Cleansing or Data Scrubbing) is the process of identifying and correcting or removing errors, inconsistencies, duplicates, missing values, and inaccurate data from a dataset.
- The goal is to improve the quality, accuracy, consistency, and reliability of data before analysis or machine learning.

### 1. Handle Missing Values-
- Missing values occur when some data fields are empty, unavailable, or contain no value.
- **Methods to Handle Missing Values:**
  - Remove rows or columns with many missing values.
  - Replace (Impute) missing values using:
  - Mean – Average value (for numerical data)
  - Median – Middle value (useful when data has outliers)
  - Mode – Most frequent value (for categorical data)
  - Constant Value – e.g., "Unknown" or 0

### 2. Removing Duplicate Data-
- Duplicate data refers to repeated records that represent the same information in a dataset.
- These duplicates can lead to inaccurate analysis and incorrect results.
- **Methods to Remove Duplicates:**
  - Identify duplicate records using unique fields (e.g., ID or Email).
  - Keep only one copy of each duplicate record.
  - Delete or merge the repeated records.

### 3 Handling Outliers-
- Outliers are data values that are significantly higher or lower than the rest of the observations in a dataset.
- They may occur due to data entry errors, measurement errors, or genuine rare events

### Outlier Detection Methods-
#### 1. Z-Score Method-
- The Z-Score Method is a statistical technique used to detect outliers by measuring how many standard deviations a data point is away from the mean.
- A data point with a very high or very low Z-score is considered an outlier.

        Z = (X − μ) / σ
        
        Where:
        Z = Z-Score
        X = Data value (observation)
        μ (Mean) = Average of the dataset
        σ (Standard Deviation) = Measure of how spread out the data is

- **Interpretation-**
- Z = 0 → The data value is exactly equal to the mean.
- Z > 0 → The data value is above the mean.
- Z < 0 → The data value is below the mean.
- |Z| > 2 → The data value is relatively far from the mean.
- |Z| > 3 → The data value is often considered an outlier.


#### 2. IQR Method-
- The Interquartile Range (IQR) Method is a statistical technique used to detect outliers by measuring the spread of the middle 50% of the data.
- Unlike the Z-Score Method, the IQR method does not depend on the mean and standard deviation, making it more reliable for datasets that contain extreme values or are not normally distributed.
- Quartiles divide a sorted dataset into four equal parts.

			0%        25%          50%          75%          100%
			|----------|------------|------------|-------------|
			Minimum     Q1         Median         Q3         Maximum


- **First Quartile (Q1)**
- Also called the 25th percentile
- 25% of data lies below Q1.
- 75% lies above it.
- **Second Quartile (Q2)**
- Also called the Median
- 50% of values lie below it.
- 50% lie above it.
- **Third Quartile (Q3)**
- Also called the 75th percentile
-75% of values lie below it.
-25% lie above it.

### Interquartile Range (IQR)
- The Interquartile Range (IQR) measure he spread of the middle 50% of the data.
- It ignores the smallest 25% and largest 25% of values, making it resistant to extreme values.
- Formula

      IQR=Q3−Q1
	​
      Where:
       - Q1 = First Quartile (25%)
       - Q3 = Third Quartile (75%)

- Lower boundary:

		Q1 - 1.5 × IQR

- Upper boundary:

		Q3 + 1.5 × IQR

- Values outside this range are outliers.









