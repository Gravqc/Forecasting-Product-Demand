# Forecasting Product Demand

## 📖 Introduction
This project is an ML-based approach to forecast product demand using historical sales and production records. It employs various deep learning and machine learning algorithms, including Random Forest, Linear Regression, and Moving Average, to enhance forecasting accuracy. This system is designed to aid companies in efficient resource utilization and maximizing profits by preparing more accurate production plans and managing inventory.

## 🛠️ Installation
**Requirements:**
- Jupyter Notebook/Visual Studio
- Python libraries: NumPy, pandas, scikit-learn, etc.

**Setup:**
- Install the required software and libraries.
- Clone the repository and navigate to the project directory.
- Load the project into Jupyter Notebook/Visual Studio and run it.

## 👨‍🏫 Get Started
To use the forecasting system:
1. Input the historical data of product demand.
2. Choose the forecasting model and parameters.
3. Run the model to predict future demand.

## 📘 Documentation
The project includes a detailed examination of time-series data to forecast product demand accurately. Techniques used:
- **Simple Moving Average (SMA)**: A statistical technique used for trend prediction over a specific period.
- **OUTPUT:**
   ![image](https://github.com/Gravqc/Sales-Predict/assets/90492971/95aeef6b-0748-4c57-97f6-d8601533f7df)

- **Random Forest Regression**: A supervised ML algorithm widely used in regression problems.
- **OUTPUT:**
  ![image](https://github.com/Gravqc/Sales-Predict/assets/90492971/8cebe0b1-4586-4ae2-8344-f7726fff717f)

- **Linear Regression**: A technique for modeling the relationship between a dependent variable and one or more independent variables
- **OUTPUT:**
 ![image](https://github.com/Gravqc/Sales-Predict/assets/90492971/6444ac92-11c6-4081-8cde-7aaa5e624e8c)

## Conclusion and Impact

### Result Summary
Our exploration into demand forecasting using various models has yielded insightful results. The RMSE values indicate the predictive accuracy of each model, with the Moving Average model achieving an RMSE of 46.7284, the Random Forest Regression model at 1259.52, and the Linear Regression model at 1100.32. While these values exceed the typical standards for RMSE, they provide a baseline for understanding model performance given the dataset's limitations.

### Understanding the Model Implications
- **Model Selection**: The choice between Linear Regression, Moving Average, and Random Forest Regression should be guided by specific needs and constraints of the application, such as the available data volume, required model interpretability, and the acceptable level of complexity.
- **Data Considerations**: The quality and volume of data significantly impact model accuracy. The current models' limitations highlight the importance of a comprehensive and clean dataset for training to achieve more accurate predictions.
- **Overfitting Concerns**: The complexity of the Random Forest model makes it more prone to overfitting compared to simpler models like Linear Regression or Moving Average, especially when data is limited.

### Strategic Impact
- **Operational Efficiency**: Despite the current limitations, employing these models can still guide inventory management, production planning, and other operational activities, leading to improved efficiency and cost savings.
- **Business Decisions**: These models, with further refinement and better data, can significantly enhance decision-making processes by providing more accurate forecasts, thereby aligning supply with demand more effectively.
- **Continuous Improvement**: This project underscores the need for ongoing model evaluation and data collection. As more data becomes available and models are refined, we expect predictive accuracy to improve, yielding even more substantial business benefits.



