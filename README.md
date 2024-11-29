# -Global-Growth-and-Demographics-Study


Python Project | Master’s Program | August 2023


Exploring Global Economic and Demographic Patterns

📌 Project Overview
This project delves into the World Development Data to uncover key economic, demographic, and developmental insights. Through a combination of statistical methods, data visualizations, and machine learning, the analysis aims to:

Identify global patterns and disparities in economic development.
Evaluate the impact of policies on economic performance.
Segment countries into meaningful clusters for targeted strategies.
This multifaceted approach provides actionable insights for stakeholders in policy-making, economics, and international development.

🛠 Methodology
1. Descriptive Statistics
Explored key features like GDP, Population Density (PopDens), and Fertility Rate (FertRate).
Summarized the central tendencies, variability, and distributions of the dataset.
2. Boxplot of GDP by Region
Visualized regional GDP distributions to identify disparities and outliers.
3. T-Test for Regional Comparison
Compared GDP between Asia and Americas using a two-sample t-test.
Results informed whether significant economic differences exist between the two regions.
4. A/B Testing with Paired T-Test
Assessed the impact of a policy change on GDP by comparing GDP in 2000 and 2020.
Evaluated statistical significance through a paired t-test.
5. Linear Regression
Modeled the relationship between GDP and features like PopDens and FertRate.
Evaluated model performance using the Mean Squared Error (MSE).
6. K-Means Clustering
Grouped countries based on demographic and economic features (PopDens, GDP, LifeExpBirth).
Identified clusters to reveal similarities and differences across nations.
🎯 Key Insights
📊 Descriptive Statistics
Substantial variation in population-related variables (PopTotal, PopDens).
High standard deviation in GDP, reflecting global economic heterogeneity.
🌎 Regional Comparisons
T-Test: No significant difference in GDP between Asia and the Americas.
T-statistic: -0.994
P-value: 0.320
🧪 Policy Impact Assessment (A/B Testing)
No statistically significant change in GDP before and after the policy change.
T-statistic: -1.723
P-value: 0.086
📈 Predictive Modeling
Linear regression model highlighted potential issues with the selected features (PopDens, FertRate).
Mean Squared Error (MSE): 2.68e+24
🗺 Country Clustering
K-Means identified three distinct clusters based on demographic and economic variables.
Clusters revealed patterns of economic performance and population dynamics.
🔍 Key Business Insights
Regional Disparities

Significant variations in GDP across regions highlight diverse economic performances.
Policy Impact

While the A/B test suggested some impact of the policy change, results were not statistically significant.
Predictive Modeling

Linear regression provides a foundational model but requires refinement for improved performance.
Country Clustering

Clustering results can inform targeted policy and business strategies tailored to each group.



📂 Repository Structure
css
Copy code
📁 world-development-analysis  
│  
├── 📁 data  
│   └── Raw and processed datasets.  
│  
├── 📁 src  
│   └── Code for EDA, statistical tests, modeling, and clustering.  
│  
├── 📁 results  
│   └── Visualizations, statistical summaries, and model outputs.  
│  
└── README.md  



🚀 Getting Started
Prerequisites
Python 3.7+
Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy


 
💡 What I Learned
This project strengthened my skills in:

Statistical Analysis: Using t-tests and A/B testing to evaluate data.
Visualization: Creating insightful plots to highlight trends.
Machine Learning: Implementing clustering and regression models.
Data Storytelling: Communicating findings effectively to inform decision-making.



🤝 Connect with Me
I’m excited to share this project and hear your feedback!

Kiran

🌐 https://www.linkedin.com/in/kiran2323/

📧 Email:  sai.kiran112311@gmail.com
