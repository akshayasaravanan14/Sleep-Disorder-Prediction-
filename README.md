# Sleep Disorder Prediction

This project aims to predict sleep disorders based on various lifestyle and medical variables such as age, BMI, physical activity, sleep duration, blood pressure, and more.

## About the Dataset

The Sleep Health and Lifestyle Dataset contains 400 rows and 13 columns, covering a wide range of variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate, daily steps, and the presence or absence of sleep disorders.

### Key Features of the Dataset:

- **Comprehensive Sleep Metrics:** Explore sleep duration, quality, and factors influencing sleep patterns.
- **Lifestyle Factors:** Analyze physical activity levels, stress levels, and BMI categories.
- **Cardiovascular Health:** Examine blood pressure and heart rate measurements.
- **Sleep Disorder Analysis:** Identify the occurrence of sleep disorders such as Insomnia and Sleep Apnea.

## Data Preprocessing

The dataset underwent several preprocessing steps, including handling missing values, encoding categorical variables, and splitting the 'Blood Pressure' column into systolic and diastolic values.

## Exploratory Data Analysis (EDA)

The EDA process was divided into two phases:

### Phase 1:

- Understanding the data through visualizations of various variables such as gender, age, sleep duration, quality of sleep, physical activity level, stress level, BMI category, daily steps, and sleep disorder.

### Phase 2:

- Analyzing the correlation between different variables, such as gender and sleep disorder, occupation and sleep disorder, and BMI category and sleep disorder.

## Model Building

Two classification algorithms were used for predicting sleep disorders:

1. **Decision Tree Classifier:** Achieved an accuracy of 87%.
2. **Random Forest Classifier:** Achieved an accuracy of 89%.

## Conclusion

- Gender, occupation, and BMI are identified as significant factors influencing sleep disorders.
- The Random Forest Classifier outperformed the Decision Tree Classifier with an accuracy of 89%.

