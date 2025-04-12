# Air-Quality-Prediction-for-Smart-Cities-using-Machine-Learning-Algorithms

## Description
The project focuses on predicting air quality levels using machine learning techniques. It primarily involves analyzing air quality data, identifying patterns, and developing predictive models to forecast pollution levels. The emphasis is on understanding the impact of various pollutants on the Air Quality Index (AQI) and using this information to improve public health awareness and environmental monitoring.
## Dataset
Access the dataset here:
<a href = 'https://www.kaggle.com/code/alicankal/aqi-india-2015-2020-analysis'> Data </a>
## Goal
The main goal is to predict the AQI category based on features such as levels of major pollutants (e.g., PM2.5, PM10, NO2, SO2, CO, O3) using machine learning models. This can help in alerting communities and authorities about potential air quality hazards and enable better decision-making.
## Process
- Data Collection: The dataset was collected from Kaggle, containing air quality data from multiple cities in India over several years.
- Data Preprocessing:
Cleaning missing values,
Standardizing and normalizing the data,
Encoding categorical features,
Dropping unnecessary columns,
- Exploratory Data Analysis (EDA):
Visualized distributions of pollutants,
Analyzed AQI levels across different cities and timeframes,
Used correlation heatmaps to find relationships between pollutants and AQI,
- Model Building and Evaluation:
Used various models including Artificial Neural Networks, Support Vector Machines,
Performed hyperparameter tuning,
Split data into training and testing sets,
Evaluated using accuracy, precision, recall, and F1-score
## Insights
PM2.5 and PM10 are the most influential pollutants affecting the AQI.
Hybrid model (Artificial Neural Networks, Support Vector Machines) outperformed other models in terms of accuracy and robustness.
Pollution is higher in industrialized and urban regions, especially during the winter months.
A clear seasonal trend in air quality was observed, with worse conditions in colder months.

![image](https://github.com/user-attachments/assets/67ac24c6-e8ea-44bc-9cf1-6a7ac20c99e1)
![image](https://github.com/user-attachments/assets/cf640de8-692c-4142-bc53-e88447b19d07)
![image](https://github.com/user-attachments/assets/bd49400c-d753-4441-bd8b-9f2174b8d58d)
![image](https://github.com/user-attachments/assets/65cb7b8c-1340-4948-803d-5f1cd0eb910a)

## Conclusion
The project successfully demonstrated that machine learning models, especially ensemble methods like Artificial Neural Networks and Support Vector Machines, can effectively predict AQI categories based on pollutant concentrations. These predictions can be crucial for policymakers, environmental agencies, and the general public to understand and act on air quality issues. The study emphasizes the need for continuous air quality monitoring and the use of predictive analytics for better environmental management.


