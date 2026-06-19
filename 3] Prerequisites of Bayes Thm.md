# Covariance -
- Covariance is a statistical measure that tells us how two variables change together.
- It indicates whether two variables move in the same direction or in opposite directions.
- Covariance measures the relationship between two variables X and Y.

      If X increases and Y also increases → Positive Covariance
      If X increases and Y decreases → Negative Covariance
      If there is no consistent relationship → Covariance is near Zero

- **Formula-**

        Cov(X,Y) = Σ[(Xi - X̄)(Yi - Ȳ)] / n
        
        Where:
        
        Xi = values of X
        Yi = values of Y
        X̄ = mean of X
        Ȳ = mean of Y
        n = number of observations
# Example -

| X | Y |
|---|---|
| 2 | 4 |
| 4 | 6 |
| 6 | 8 |

## Step 1: Find Means

      ### Mean of X
      X̄ = (2 + 4 + 6) / 3
      X̄ = 12 / 3
      X̄ = 4
      
      ### Mean of Y
      Ȳ = (4 + 6 + 8) / 3
      Ȳ = 18 / 3
      Ȳ = 6

## Step 2: Calculate Deviations

| X | Y | X - Mean | Y - Mean | Product |
|---|---|----------|----------|---------|
| 2 | 4 | -2 | -2 | 4 |
| 4 | 6 | 0 | 0 | 0 |
| 6 | 8 | 2 | 2 | 4 |

### Sum of Products

(4 + 0 + 4) = 8

## Step 3: Divide by n

### Covariance Formula

Cov(X,Y) = Σ[(Xᵢ - X̄)(Yᵢ - Ȳ)] / n

### Substitute Values

Cov(X,Y) = 8 / 3

Cov(X,Y) = 2.67

## Result

**Cov(X,Y) = 2.67**

Since the covariance is positive:

- As **X increases**, **Y increases**
- X and Y move in the **same direction**
- There is a **positive relationship** between X and Y










# Correlation -
- Correlation is a statistical measure that describes both the direction and strength of the relationship between two variables.
- Its value ranges from -1 to +1, where +1 indicates a perfect positive relationship, -1 indicates a perfect negative relationship, and 0 indicates no linear relationship.
- Strength in correlation refers to how closely two variables are related.
- The closer the correlation coefficient is to +1 or -1, the stronger the relationship. The closer it is to 0, the weaker the relationship.

        r = Cov(X,Y) / (σX × σY)
        
        Where:
        
        Cov(X,Y) = Covariance between X and Y
        σX = Standard deviation of X
        σY = Standard deviation of Y
        r = Correlation coefficient
        
        Correlation Range:
        
        -1 ≤ r ≤ 1

# Example -

| X | Y |
| - | - |
| 2 | 4 |
| 4 | 6 |
| 6 | 8 |

We already calculated:

Cov(X,Y) = 2.67

Now let's calculate the Correlation Coefficient (r).

### Formula

r = Cov(X,Y) / (σₓ × σᵧ)

Where:

- Cov(X,Y) = Covariance
- σₓ = Standard Deviation of X
- σᵧ = Standard Deviation of Y

## Step 1: Calculate Standard Deviation of X

| X | X - X̄ | (X - X̄)² |
|---|--------|-----------|
| 2 | -2 | 4 |
| 4 | 0 | 0 |
| 6 | 2 | 4 |

Sum = 8

Variance(X) = 8 / 3 = 2.67

σₓ = √2.67

σₓ = 1.63

## Step 2: Calculate Standard Deviation of Y

| Y | Y - Ȳ | (Y - Ȳ)² |
|---|--------|-----------|
| 4 | -2 | 4 |
| 6 | 0 | 0 |
| 8 | 2 | 4 |

Sum = 8

Variance(Y) = 8 / 3 = 2.67

σᵧ = √2.67

σᵧ = 1.63

## Step 3: Calculate Correlation

r = 2.67 / (1.63 × 1.63)

r = 2.67 / 2.6569

r ≈ 1.00

## Result

r = 1

### Interpretation

- r = +1 indicates a Perfect Positive Correlation
- As X increases, Y increases proportionally
- All points lie exactly on a straight line

Relationship:

X ↑ → Y ↑











  
