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

##### 










