# ML Model Deployment and Tracking Using MLflow

# ML Model Deployment Workflow
1. Use Case Summary
    - Objective Statement
    - Challenges
    - Analytic Method/Technique
    - Business Benefit
    - Expected Outcome
2. Business Understanding
3. Data Understanding
4. Data Preparation
5. Data Profiling
6. Data Cleansing
7. Exploratory Data Analysis
8. Preprocessing Modeling
9. Modeling using Linear Regression
10. Evaluate Model
11. Model Deployment
12. Result
13. Recommendation

# Use Case Summary
- Objective Statement:
  - To get insight how much sales based on tv advertising
  - To get insight how much money is spent on advertising on TV
  - To gain insight into the relationship between sales and TV marketing
  - To predict sales using Linear Regression based on TV advertising
  - To get insight about model deployment using MLflow

- Challenges:
  - There are no other variables as a comparison

- Methodology / Analytic Technique:
  - Descriptive Analysis
  - Graph Analysis
  - Modeling using Linear Regression
  - Model Deployment using MLflow

- Business Benefit:
  - Knowing how much sales from tv advertising
  - Knowing how sales predict results by placing ads on TV
  - Helping business team optimize spent advertising costs

- Expected Outcome:
  - Know how much sales based on TV advertising
  - Know how much money is spent on advertising on TV
  - Know about relationship between sales and TV marketing
  - Know the results of sales prediction using Linear Regression based on TV advertising
  - Know about creating model deployments using MLflow and the results

# Business Understanding
- Tv Marketing is the method of demonstrating features of products and providing their information on television to attract viewers and encourage them to buy the shown products is called trade through television marketing.
- This case has some business question using the data:
   - How much company spent money on TV advertising?
   - How much money is spent on advertising on TV?
   - How about relationship between sales and TV marketing?
   - How about the results of sales prediction based using Linear Regression on TV advertising?
   - How to create a model deployment using MLflow?

# Data Understanding

- Data of TV Marketing
- This data have 2 columns and 200 rows
- Source Code : https://www.kaggle.com/datasets/leiadis/tvmarketing
- Data Dictionary :
  - TV : money spent on advertising via TV
  - Sales : number of sales

# Data Preparation
Code Used:
- Python Version: 3.7.15
- Packages: Pandas, Numpy, Matplotlib, Seaborn, MLFlow, sklearn and Warnings

# Data Profiling
Data profiling is the process of reviewing source data, understanding structure, content and interrelationships, and identifying potential for data projects.

# Data Cleansing
The TV Marketing dataset is clean because the data no longer has missing values and the data types are already appropriate.

# Exploratory Data Analysis
- What about the relationship between sales and TV marketing based on scatterplot?

    ![Screenshot_20221117_114716](https://user-images.githubusercontent.com/113869968/202358667-52ae25b2-3ed8-4439-bf13-aa993a1506d8.png)
    
    From the chart above, it can be seen that there is a **strong relationship** between TV advertising and sales. Based on scatterplot, the relationship between TV advertising and sales is **directly proportional**. As more money is spent on advertising on TV, sales will increase.

- What about the relationship between sales and TV marketing based on correlation values?

    ![Screenshot_20221117_114728](https://user-images.githubusercontent.com/113869968/202358672-8c995eac-ffca-4126-aa17-d1c6d793b213.png)
    
    From the heatmap above, it can be seen that **there is a strong relationship** between TV advertising and sales. This is because the correlation value between sales and tv marketing is **0.78** where it is **more than 0.5**.
    
# Preprocessing Modeling

# Modeling

# Evaluate Model

# Model Deployment

# Result

# Recommendation

# MLflow
