# Modeling Physical Activity using Trivisio's Colibri Wireless Unit

### Description: 
This project investigates the potential to predict the MET (Metabolic Equivalent of Task) score of users of the Colibri Wireless unit, an advanced inertial measurement unit (IMU) that tracks movement and physiological data. The research utilized data from 9 participants, each equipped with multiple IMUs and heart rate monitors, who performed various physical activities such as walking, cycling, and football. The dataset, consisting of 54 attributes, was processed to predict MET scores based on features like heart rate, temperature, acceleration, and gyroscope measurements. The project applies techniques such as data wrangling, feature selection, and linear regression to create a predictive model, ultimately demonstrating the utility of the Colibri Wireless unit for fitness tracking. The model’s evaluation includes performance metrics like R-squared, AIC, and MSE.

### Key Components:

1. Data Wrangling & Cleaning: Processed and refined the dataset by creating new columns, handling missing values, and removing redundant data.
2. Feature Selection: Used methods such as recursive feature elimination and cross-validation to identify significant features that influence MET prediction.
3. Modeling & Evaluation: Developed a linear regression model, analyzed its performance using R-squared, AIC, and MSE, and fine-tuned the model based on significant features.
4. Recommendations: Based on the findings, a software tool was developed to predict MET and track activity intensity, with recommendations for expanding the dataset and focusing on demographic groups for future analysis.

### Tools and Libraries:
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (for feature selection)
- Statsmodels (for linear regression)

This project highlights the use of advanced data analytics to enhance wearable technology applications, offering actionable insights for improving fitness tracking and user engagement.
