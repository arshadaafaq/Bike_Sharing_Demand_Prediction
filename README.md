Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Project Summary -
The Seoul Bike Sharing Demand Prediction project is a great example of the typical process for a data science project. It involves five key stages: defining a problem, data processing, modeling, evaluation, and deployment.

The first step in this project was to define the problem. The objective was to predict the demand for shared bikes in Seoul based on various features such as temperature, rainfall, season, and snowfall. To achieve this objective, the project involved a thorough understanding of the data by examining its properties, including its size, shape, and quality.

Data processing is the next step, and it involves cleaning and preparing the data for modeling. In this project, the data was wrangled, and new features were engineered. One example is the creation of new columns such as month and weekdays. These features were added to the dataset to provide a deeper understanding of how various factors influence bike rentals in Seoul.

After data processing, the project involved Exploratory Data Analysis (EDA) to gain further insight into the data. The EDA stage helped to identify relationships between the dependent variable, 'Rental Bike Count,' and other independent variables such as temperature, rainfall, and functioning day.

One of the significant findings from the EDA stage is that rented bikes are less used in winters than summers. Also, functioning day is a crucial factor in determining the number of bikes rented. By checking the correlations, the team discovered that some columns contained outliers that could affect the models' performance. Therefore, they took steps to address the issue by removing the outliers.

Next, we performed one-hot encoding to convert categorical variables to a format that is more predictable. They also checked for multicollinearity to avoid redundancy in the model. To optimize the models' performance, the team transformed the variables to a standard scalar (z-score transformation).

The next step was to split the dataset into training and testing sets. Our team has used a 0.20 ratio to ensure the model's performance is not overfitted. They applied multiple linear regression, ridge regression, lasso regression, elastic net, polynomial regression, decision tree, and random forest.

To evaluate the model's performance, the team used adjusted R2 and RMSE as evaluation metrics. The results showed that the Random Forest model outperformed other models. Random Forest had the highest adjusted R2 score, indicating that it was the best model to deploy.

In summary, the Seoul Bike Sharing Demand Prediction project demonstrates the importance of following best practices in data science projects. Our team thoroughly understood the problem and the data and applied various data processing techniques, including feature engineering and data cleaning. We also performed EDA, model evaluation, and selection, and ensured transparency and interpretability of the model by using model explainability.
