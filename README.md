# student-performance-analysis-eda
Exploratory Data Analysis on Student Performance Analysis using Python

This project performs Exploratory Data Analysis (EDA) on a student performance dataset containing 33 socio-academic features.
The goal is to analyze how parental background, family conditions, study habits, and lifestyle factors influence students’ academic performance.

The project focuses on insight generation and statistical understanding, without using heavy machine learning models.

Objectives

Understand the structure and quality of the dataset

Analyze academic performance using grades (G1, G2, G3)

Study the impact of:

Parents’ education

Family size and relationships

Alcohol consumption

Study time

Gender

Identify factors affecting final student performance

Dataset Information

Dataset: Student Performance Dataset (UCI Repository)

Total Features: 33

Target Variable:

G3 – Final Grade

Key Attributes:

Parental education (Medu, Fedu)

Family size and marital status

Study time

Alcohol consumption (weekday & weekend)

Family relationship quality

The dataset contains no missing values, making it suitable for direct analysis.

Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Methodology

Data loading and inspection

Data quality check (missing values, data types)

Feature engineering (total score & average score)

Univariate analysis (distribution plots)

Bivariate analysis (boxplots, comparisons)

Correlation analysis using heatmaps

Insight generation based on visual evidence

Key Visualizations

Parents’ education distribution

Parents’ education vs student performance

Family size and relationship quality impact

Alcohol consumption vs academic performance

Study time vs grades

Gender-wise performance comparison

Correlation heatmap between academic and lifestyle factors

Key Insights

Students with higher parental education tend to perform better academically

Study time has a positive impact on academic performance

Higher alcohol consumption negatively affects student grades

Students with strong family relationships score higher on average

Second-period grade (G2) strongly influences the final grade (G3)

Gender differences exist but are not the dominant factor in performance
