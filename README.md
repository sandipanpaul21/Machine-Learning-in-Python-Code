## How to Approach ML Problems Step by Step !! 

For THEORY PART, please refer to https://github.com/sandipanpaul21/Machine-Learning-Notes-Daywise

### 01 Know about the Dataset
* What Dataset is all about? Problem Objective ?
* Number of Rows and Columns. Data Stored is in which type? Is it a Data-frame or a Dictionary?

### 02 Univariate Analysis
* Uni means one, so Single Variable Analysis
* Mainly deals with Numerical Measures used in a dataset (Total 14 Numerical Measures)
* Measure of Central Tendency : 1. Mean, 2. Median, 3. Mode
* Measure of Data Spread : 4. Quartile, 5. Percentile, 6. Range, 7. IQR, 8. Boxplot, 9. Variance, 10. Standard Deviation
* Variation between Variables : 11. Covariance, 12. Correlation Coefficient (Pearson and Spearman)
* Measure Distribution and Peakness : 13. Skewness and 14. Kurtosis

### 03 Bivariate Analysis 
* Bi means two, so Two Variable Analysis
* There are majorly two types of Data Variable: Continuous & Categorical Variable
* So 3 possible combinations for Bivariate Analysis
  1. Continuous vs Continuous : Correlation Coefficient 
  2. Categorical vs Categorical : Chi Square Test
  3. Continuous vs Categorical : T Test (n < 30), Z Test (n > 30) and ANOVA Test

### 04 Outlier & Missing Values 
* Outlier are data points that differs significantly from other observations
* Techniques to Detect Outliers : 1. Box Plot and 2. Z-Score
* Technqiues to Remove Outliers : Capping Based on Upper and Lower Range
* Missing Values in the Dataset cause concern for Machine Learning Model
* Techniques for Imputing Missing Values
  1. Continuous Data : Median Imputation
  2. Categorical Data : Mode Imputation
  3. KNN Imputation (why better than Median and Mode imputation)

### 05 Feature Engineering 
* Tweaking the features, to increase the efficiency of the Model
* 3 Major Steps in Feature Engineering : 1.Transformation, 2.Scaling & 3. Construction
* Feature Transformation
  1. Feature transformation is performed to normalize the data
  2. Methods Used : 1.Log Transformation, 2.Square Root, 3.Cube Root & 4.Box-Cox Transformation
* Feature Scaling
  1. Feature scaling is conducted to standardize the independent features
  2. Method Used : Mix-Max Scaler
* Feature Construction
  1. It is a process of creating features based on the original descriptors
  2. Methods Used : 1.Binning and 2.Encoding

### 06 Regression Assumption
* With Boston Dataset, all 5 regression assumptions checked (Why, What and How)
  1. Linearity between Target & Features : Plot Predicted & Target
  2. Normality of Error Term : Anderson-Darling Test & Skewness in Error Term
  3. Multicollinearity among Predictors : Correlation & VIF
  4. Autocorrelation among Error Term : Durbin-Watson Test
  5. Homoscedasticity,same variance within error terms : Residual Plot
