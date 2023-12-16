
# Predictive Maintenace in Pharmaceutical Industries

 The project aims to conduct a thorough statistical analysis on the dataset obtained by monitoring a specific piece of equipment over a year in a pharmaceutical facility to extract meaningful inferences about the equipment's behavior under diverse operational scenarios, facilitating informed decisions for timely and proactive maintenance interventions.


## Project Scope
#### 1. Data Collection Methodology

- Derived from year-long equipment monitoring in a pharmaceutical facility.
- The dataset comprises axial, vertical, and horizontal velocity and acceleration data, alongside noise levels, temperature, and electric current information.
- To ensure the dataset is representative of various operating conditions,data has been collected across different scenarios, including normal operation, maintenance, and periods of equipment malfunction.

#### 2. Data Preprocessing

-  Imputation of missing values with median of respective columns, maintaining the overall statistical characteristics of the data.
- Dropping statistically irrelavant columns and records.

#### 3. Descriptive Statistics and Visualisation

- The data is summarized in terms of  mean, median, mode, and standard deviation. These measures provide insights into central tendency and variability.
- Additionally, visualizations like box plots and histograms have been used to analyze the distribution, identify outliers, and understand equipment parameter trends, crucial for detecting structural faults.

#### 4. Hypothesis Testing and Model Building

- Formulated hypotheses and performed testing to determine the predictors in s=different faulty conditions.
- A model has been used to predict the values of 
## Key Findings:

- The mean bearing temperature in faulty(symptoms of fault) conditions is significantly higher than the population mean of mean bearing temperature.
- There exists significant positive correlation between the pairs Current and Temperature, Current and Noise. The least square regression line can be used to study the same.
- The KNeighbors Regressor model is efficient in depicting relationship between the variables Noise and Temperature.
