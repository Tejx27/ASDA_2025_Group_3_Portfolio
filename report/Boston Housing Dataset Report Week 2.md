# Basic EDA Report

# 1. Dataset Overview

<table><tr><td>Item</td><td>Description</td></tr><tr><td>Dataset name</td><td>The Boston Housing Dataset</td></tr><tr><td>Number of rows</td><td>506</td></tr><tr><td>Number of columns</td><td>14</td></tr><tr><td>Format file (.csv, .txt, etc)</td><td>.csv</td></tr><tr><td>Authors of the dataset</td><td>Prasad Perera</td></tr><tr><td>Source (name)</td><td>Kaggle – Prasad Perera</td></tr><tr><td>Source (link)</td><td>https://www.kaggle.com/code/prasadperera/the-boston-housing-dataset</td></tr></table>

# Short description (what is it about?)

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA.

# 2. Structure of the dataset

<table><tr><td>Column name</td><td>Data type</td><td>Non-null count</td><td>Unique values</td><td>Example values</td></tr><tr><td>CRIM</td><td>float64</td><td>506</td><td>504</td><td>0.00632</td></tr><tr><td>ZN</td><td>float64</td><td>506</td><td>26</td><td>18.0</td></tr><tr><td>INDUS</td><td>float64</td><td>506</td><td>76</td><td>2.31</td></tr><tr><td>CHAS</td><td>int64</td><td>506</td><td>2</td><td>0</td></tr><tr><td>NOX</td><td>float64</td><td>506</td><td>81</td><td>0.538</td></tr><tr><td>RM</td><td>float64</td><td>506</td><td>446</td><td>6.575</td></tr><tr><td>AGE</td><td>float64</td><td>506</td><td>356</td><td>65.2</td></tr><tr><td>DIS</td><td>float64</td><td>506</td><td>412</td><td>4.09</td></tr><tr><td>RAD</td><td>int64</td><td>506</td><td>9</td><td>1</td></tr><tr><td>TAX</td><td>float64</td><td>506</td><td>66</td><td>296.0</td></tr><tr><td>PTRATIO</td><td>float64</td><td>506</td><td>46</td><td>15.3</td></tr><tr><td>B</td><td>float64</td><td>506</td><td>357</td><td>396.9</td></tr><tr><td>LSTAT</td><td>float64</td><td>506</td><td>455</td><td>4.98</td></tr><tr><td>MEDV</td><td>float64</td><td>506</td><td>229</td><td>24.0</td></tr></table>

# 3. Descriptive statistics

Numeric columns

<table><tr><td></td><td>CRIM</td><td>ZN</td><td>INDUS</td><td>CHAS</td><td>NOX</td><td>RM</td><td>AGE</td><td>DIS</td><td>RAD</td><td>TAX</td><td>PTRATIOB</td><td>LSTAT</td><td>MEDV</td></tr><tr><td>count</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td><td>506.000</td></tr><tr><td>mean</td><td>3.614</td><td>11.364</td><td>11.137</td><td>0.069</td><td>0.555</td><td>6.285</td><td>68.575</td><td>3.795</td><td>9.549</td><td>408.237</td><td>18.456</td><td>356.674</td><td>12.653</td></tr><tr><td>std</td><td>8.602</td><td>23.322</td><td>6.860</td><td>0.254</td><td>0.116</td><td>0.703</td><td>28.149</td><td>2.106</td><td>8.707</td><td>168.537</td><td>2.165</td><td>91.295</td><td>7.141</td></tr><tr><td>min</td><td>0.006</td><td>0.000</td><td>0.460</td><td>0.000</td><td>0.385</td><td>3.561</td><td>2.900</td><td>1.130</td><td>1.000</td><td>187.000</td><td>12.600</td><td>0.320</td><td>1.730</td></tr><tr><td>25%</td><td>0.082</td><td>0.000</td><td>5.190</td><td>0.000</td><td>0.449</td><td>5.885</td><td>45.025</td><td>2.100</td><td>4.000</td><td>279.000</td><td>17.400</td><td>375.378</td><td>6.950</td></tr><tr><td>50%</td><td>0.257</td><td>0.000</td><td>9.690</td><td>0.000</td><td>0.538</td><td>6.208</td><td>77.500</td><td>3.207</td><td>5.000</td><td>330.000</td><td>19.050</td><td>391.440</td><td>11.360</td></tr><tr><td>75%</td><td>3.677</td><td>12.500</td><td>18.100</td><td>0.000</td><td>0.624</td><td>6.624</td><td>94.075</td><td>5.188</td><td>24.000</td><td>666.000</td><td>20.200</td><td>396.225</td><td>16.955</td></tr><tr><td>max</td><td>88.976</td><td>100.000</td><td>27.740</td><td>1.000</td><td>0.871</td><td>8.780</td><td>100.000</td><td>12.126</td><td>24.000</td><td>711.000</td><td>22.000</td><td>396.900</td><td>37.970</td></tr></table>

Categorical/object columns  

<table><tr><td></td><td>CHAS</td><td>RAD</td></tr><tr><td>Count</td><td>506</td><td>506</td></tr><tr><td>Number of 
unique values</td><td>2</td><td>9</td></tr><tr><td>Most frequent 
value</td><td>0</td><td>24</td></tr><tr><td>Most frequent 
value 
(frequency)</td><td>471</td><td>132</td></tr><tr><td>Least frequent 
value</td><td>1</td><td>7</td></tr><tr><td>Least frequent 
value 
(frequency)</td><td>3</td><td>17</td></tr></table>

3. Missing values and duplicates  

<table><tr><td>Column name</td><td>Missing count</td><td>% Missing</td></tr><tr><td>CRIM</td><td>0</td><td>0.00 %</td></tr><tr><td>ZN</td><td>0</td><td>0.00 %</td></tr><tr><td>INDUS</td><td>0</td><td>0.00 %</td></tr><tr><td>CHAS</td><td>0</td><td>0.00 %</td></tr><tr><td>NOX</td><td>0</td><td>0.00 %</td></tr><tr><td>RM</td><td>0</td><td>0.00 %</td></tr><tr><td>AGE</td><td>0</td><td>0.00 %</td></tr><tr><td>DIS</td><td>0</td><td>0.00 %</td></tr><tr><td>RAD</td><td>0</td><td>0.00 %</td></tr><tr><td>TAX</td><td>0</td><td>0.00 %</td></tr><tr><td>PTRATIO</td><td>0</td><td>0.00 %</td></tr><tr><td>B</td><td>0</td><td>0.00 %</td></tr><tr><td>LSTAT</td><td>0</td><td>0.00 %</td></tr><tr><td>MEDV</td><td>0</td><td>0.00 %</td></tr></table>

Total missing values: 0

Percentage of dataset affected:  $0.00\%$

Duplicated rows found: 0

Percentage of rows in dataset affected:  $0.00\%$

# 4. Data consistency

<table><tr><td>Item</td><td>Description</td></tr><tr><td>Does the dataset contain unnecessary columns? Which?</td><td>No unnecessary columns; all 14 columns (CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT, MEDV) are relevant for housing price prediction.</td></tr><tr><td>Do the data types correspond to the columns?</td><td>Yes, data types are appropriate: CRIM, ZN, INDUS, NOX, RM, AGE, DIS, PTRATIO, B, LSTAT, MEDV (float); CHAS, RAD, TAX (int).</td></tr><tr><td>Is the labelling of the columns appropriate?</td><td>Yes, column names are clear and descriptive (e.g., CRIM for crime rate, MEDV for median value).</td></tr><tr><td>Are there mixed values in column (e.g., number and characters)?</td><td>No, all columns contain only numeric values (no mixed types like numbers and characters).</td></tr><tr><td>Are string column clean?</td><td>No string columns present, so not applicable.</td></tr><tr><td>Does the dataset look machine generated?</td><td>No, it is a real-world dataset collected from Boston housing data</td></tr><tr><td>Other</td><td>None</td></tr></table>

# 5. Overall assessment

Is it worth it to further analyze the dataset?

Yes, valuable for learning and modeling housing prices.

What possible analysis can be performed?

> EDA: Histograms, scatter plots, correlation heatmap.  
>Stats:Outlier detection,hypothesis testing.  
$\succ$  Advanced: PCA, clustering, predictive modeling.

# 6. Next steps

- Handling missing values? How?

No missing values; use df fillsna() or df.dropna() if any.

-Removing duplicates?

No duplicates; use df.dropDuplicates() if present.

-Cleaning the columns? Which?

$\succ$  Already clean.

-Creating a subset of the dataframe?

Yes. E.g., df['rm', 'lstat', 'medv']
