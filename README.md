# Predicting Low Birth Weight Among Pregnant Women
# Overview
This is my exploration of a dataset on the risk factors associated with pregnant women delivering babies with low birth weight. Studies show that neonates born with low birth weight suffer from many health complications such as respiratory distress, and admission to the neonatal intensive care unit (NICU). These neonates also suffer a high chance of neonatal mortality than children born of normal weight. The goals of the project were to:
•	Perform statistical analysis on the data to identify the risk factors that are significantly associated with delivering children with low birth weight. 
•	Build a machine learning classification algorithm to predict the likelihood that a woman would deliver a baby of low birth weight. 

# Data
This dataset was acquired from the research study of a graduate student. I love the topic and would have normally analyzed such data using SPSS and Excel. This was a new step for me, and I was very excited to explore this entirely in Python. 

 # Project Division
This project is divided into three separate Jupiter notebooks. Each notebook is designed to tackle a different challenge in the data analysis process. They include:
•	Part 1: Data Cleaning and Feature Engineering
•	Part 2: Statistical Analysis
•	Part 3: Machine Learning Model Prediction 



I explored the data and identified some factors and built an SVM algorithm to help predict the likelihood a woman would deliver a baby of low birth weight.

### The Big Picture
With the increasing adoption of AI systems in healthcare to analyze the multitude of clinical data such as those obtained from Electronic Health Records, this project could easily be utilized for analyzing such EHR records at the gynecological wards. A lot of the data gathered in this dataset are routinely gathered for pregnant women during the course of pregnancy. Which makes our machine learning model and statistical analysis very relevant to the hospital decision-making process. 

# Solving the problem
### Statistical Analysis
•	Performed a crosstab and chi-square contingency analysis to determine the relationship between categorical features of the data and low birth weight. 
•	Built a function to dynamically build a combined distribution and contingency table to ease the visualization and interpretation of results. 
•	Performed and built a combined table of an independent t-test analysis between the numerical features and low birth weight
•	Explore the data further to see other risk factors associated with stillbirth or neonatal mortality 

### Machine Learning Classification Model 
Built and compared the sensitivity and specificity of two classification algorithms: Logistics Regression and Support Vector Machine. Although accuracy for the two models was generally between 80 – 82%, SVM performed better in terms of its sensitivity (41.57%) and specificity (91.82%). As a classification algorithm for hospital diagnosis, the model’s high specificity could help doctors quickly determine which women have a lesser risk of delivering an LBW baby. This could therefore allow doctors and nurses to more adequately focus their attention on women who most need their help.

# Interpretation of Results
The results showed that being pregnant while under the age of 20 years (29.72%) was significantly associated with delivering a baby with LBW (p = 0.0026) as compared to the percentage of women who delivered normal birth weight babies (19.07%). Women who have never given birth before (46.85%), or were pregnant for the first time (42.31%) were also significantly associated with the delivery of a baby of LBW. Although only 0.81% of women developed severe pre-eclampsia, having severe pre-eclampsia was however significantly associated with delivering a child of LBW. Also, female babies were significantly found to have lower birth weight than male babies

From the analysis, children born with low birth weight were significantly more likely to experience respiratory distress (14.34%) or end up being stillborn (7.69%). By comparison, only 1.59% of children with normal birth weights are stillborn

***Other things to note***
From the analysis, we saw that the proportion of women dying from childbirth (maternal mortality) was very low: 10 out of 1356 women, representing only 0.74% of the study population. This was a significant observation as it corroborated the results from many recent studies showing that, strategies being implemented to combat maternal mortality in Ghana were yielding good results.
