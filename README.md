# Estimation of Obesity Level

---

## Overview

The **Estimation of Obesity Level** project leverages data analysis and predictive modeling to classify individuals into different obesity levels based on health metrics and lifestyle factors. With the rising prevalence of obesity and its significant impact on global health, this project aims to support early intervention and personalized treatment strategies.

## Motivation

Obesity is a multifaceted health challenge influenced by genetics, lifestyle, environment, and culture. It is associated with serious conditions like diabetes, cardiovascular disease, and hypertension. This project aims to create a predictive model to classify individuals by obesity level using health data, which could inform personalized healthcare and targeted interventions.

## Dataset

The dataset includes **2111 individuals** with attributes such as:
- **Weight, Height, Age**
- **Family history of overweight**
- **Frequency of food consumption, physical activity, and water intake**

The data is clean, with no missing values, covering a wide age range and both genders, providing a solid foundation for predictive modeling.

## Key Sections

### 1. Data Exploration
   - Analyzed key attributes (**weight**, **age**, **height**, **meal frequency**), with visualizations including frequency tables, histograms, and boxplots.
   - Generated **correlation matrices** to explore variable relationships.

### 2. Modeling and Analysis
   - **Multiple Linear Regression**: Used to identify predictive relationships (e.g., age, height, physical activity frequency).
   - **Multiple Logistic Regression**: Employed for classification, achieving an accuracy rate of **55%**, evaluated using a **confusion matrix**.

### 3. Key Observations
   - Positive correlations exist between **height and weight** and **age and weight**.
   - Inverse correlation between physical activity frequency and weight, highlighting the role of regular exercise in weight management.
   - Scatter and correlation matrices provided insights into variable relationships.

### 4. Model Performance
   - Logistic regression model accuracy: **55%** (error rate: **45.11%**). This highlights potential for further model tuning and additional feature inclusion.

## Tools and Techniques

- **Python** for data processing, visualization, and modeling.
- Libraries: **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn** for data handling, visualization, and machine learning.

## Conclusion

This project showcases how data-driven techniques can estimate obesity levels, emphasizing the influence of factors like physical activity on obesity. The model highlights the potential of machine learning in public health, aiding in early prevention and personalized care.

## Future Work

- **Model Enhancement**: Improve accuracy with additional features or alternative modeling approaches.
- **Dataset Expansion**: Broaden dataset demographics for generalizability.
- **Advanced Algorithms**: Explore more sophisticated machine learning models for enhanced predictive performance.

## Installation and Usage

1. **Clone the Repository**
   ```sh
   git clone https://github.com/temashidzo/obesity-estimation.git
2. **Install Required Packages**
   pip install -r requirements.txt
3. Run the Analysis Execute the Jupyter notebook or Python script to view the data exploration and model results.



