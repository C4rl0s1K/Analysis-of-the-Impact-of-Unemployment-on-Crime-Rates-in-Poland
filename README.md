# **Analysis of the Impact of Unemployment on Crime Rates in Poland**

### **Project Description**
The goal of this project is to analyze the relationship between unemployment rates and crime rates in Poland using data from 1999 to 2021. The analysis includes gathering, processing, and modeling data on unemployment and different types of crimes (criminal, economic, and road crimes). The objective is to assess whether higher unemployment rates lead to an increase in the number of crimes in various categories, as well as to forecast future trends.

**Note:** This project was completed as part of university studies. The full project report in Polish can be found in the attached raport.pdf file.

### **Project Structure**
1. **Data Collection**: Data on unemployment rates and the number of criminal, economic, and road crimes in Poland were obtained from Excel files. These data were processed to calculate annual average unemployment rates and the total number of crimes in each category.

2. **Exploratory Data Analysis (EDA)**: Descriptive statistics (mean, median, standard deviation) and data visualization were performed to better understand the relationships between variables.

3. **Statistical Modeling:**

- **Linear Regression:** Linear regression models were applied to assess the impact of unemployment on the number of criminal, economic, and road crimes.
- **Correlation Analysis:** Pearson correlation coefficients were calculated for the three types of crimes.
- **t-Tests:** The number of crimes between low and high unemployment groups was compared using t-tests.
- **Forecasting:** ARIMA models were used to forecast future crime rates, considering seasonality and stationarity of the data.

4. **Visualization:** Trend graphs, histograms, and ACF/PACF plots were used to better understand the data and the results of the analyses.

5. **Clustering:** The K-means clustering method was employed to identify patterns in the crime data based on unemployment levels.

### **Technologies Used**
**Programming Language:** Python

**Libraries:**

- Pandas: for data manipulation

- Matplotlib / Seaborn: for data visualization

- Scikit-learn: for regression modeling, correlation analysis, and dataset splitting

- Statsmodels: for ARIMA modeling

- SciPy: for statistical tests (t-test, Pearson correlation)