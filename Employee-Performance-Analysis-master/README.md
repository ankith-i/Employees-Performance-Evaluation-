# Analysis of Employee Performance

## Project Overview

### Objectives

The primary goals and expectations from this project include:
- A comprehensive breakdown of performance by department.
- Identification of the top three pivotal factors influencing employee performance.
- Development of a predictive model to forecast employee performance using various factors.
- Suggested strategies to boost employee performance based on analytical insights.

### Data Examination

- The dataset in question is structured with categorical attributes. While most predictor variables are ordinal, some are nominal. The target metric, termed 'Performance Rating,' is ordinal.
- The dataset undergoes preprocessing methods like Label Encoding and Standardization. The Correlation Coefficient aids in discerning relationships amongst variables. Key features for the analysis encompass attributes such as Department, Job Role, Environment Satisfaction, percentage of the latest salary increment, work-life equilibrium, tenure in the company, duration in the current role, years since the last promotion, and years under the current manager.
- A variety of algorithms, including but not limited to Logistic Regression, Support Vector Machine, Decision Tree, and XGBoost Classifier, are employed to train the data and make predictions. 
- A distinct segment of the analysis zeroes in on performance metrics on a departmental level.

### Project Breakdown

The project's purpose revolves around discerning attributes affecting employee performance, building an accurate predictive model for employee Performance Rating, and deducing actionable insights and recommendations. The execution followed these steps:
1. Data importation, understanding the predictor and target variables, and handling missing data points.
2. Analyzing department-wise performance metrics.
3. Encoding ordinal variables using Label Encoding.
4. Utilizing correlation coefficients to understand variable interrelationships and selecting pertinent attributes.
5. Data normalization, followed by dataset division into training and testing subsets.
6. Algorithmic training and accuracy assessment to determine the most suitable model.
7. Finalizing and saving the top-performing model.

### Findings

- Utilizing the Random Forest algorithm, augmented with GridSearchCV, yielded a remarkable accuracy of 93%. Features like Environment Satisfaction, recent salary increments, and work-life balance showcased positive correlations. This suggests their proportional relationship with the Performance Rating. Conversely, factors such as tenure since the last promotion and duration under the current manager demonstrated an inverse relationship.
- The three paramount influencers on employee performance are:
   1. Satisfaction with the work environment (39.5%)
   2. The percentage increase in the most recent salary (33.3%)
   3. Time span since the previous promotion (16.7%)

### Deep Dive Insights

- Among various models, Random Forest with GridSearchCV outperformed others with a 93% accuracy rate, closely followed by the XGBoost Classifier at 92.8%.
- Noteworthy attributes demonstrating positive correlations include work environment satisfaction, the magnitude of the latest salary hike, and equilibrium between professional and personal life. These factors, when enhanced, can significantly boost the Performance Rating. In contrast, variables like the number of years since the last promotion or under the current manager's guidance, inversely impact the rating.
- It's clear that fostering a conducive work environment, timely salary revisions, and aiding employees in achieving work-life balance can drastically uplift performance. Periodically rotating managerial roles can also inject fresh perspectives and dynamism, positively impacting performance.

### Strategic Suggestions

- A conducive work environment can act as a catalyst in elevating employee performance. Periodic salary reviews and increments can further motivate employees. Ensuring employees have a balanced work-life is crucial. Additionally, periodic managerial role rotations can introduce fresh challenges and perspectives, invigorating employee performance.
