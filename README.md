## Capstone-Diabetes
# The main objectives of this project are: 
To develop a predictive model using machine learning algorithms to identify individuals at high risk of diabetes. 
To analyze the key health indicators contributing to diabetes risk. 
To evaluate the performance of different models (e.g., logistic regression, decision trees, random forests, etc.) for accuracy and interpretability. 
 

# Personal objectives of this project including: 
Learning the end-to-end process/steps to perform analysis on data provided 
Learning the tools/approaches/methods for working on data analysis.
 
# Data Overview: 
The Behavioral Risk Factor Surveillance System (BRFSS) is the nation's premier system of health-related telephone surveys that collect state data about U.S. residents regarding their health-related risk behaviors, chronic health conditions, and use of preventive services. Established in 1984 with 15 states, BRFSS now collects data in all 50 states as well as the District of Columbia and three U.S. territories. BRFSS completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world. 

The objective of the BRFSS is to collect uniform, state-specific data on preventive health practices and risk behaviors that are linked to chronic diseases, injuries, and preventable infectious diseases in the adult population. Factors assessed by the BRFSS include tobacco use, health care coverage, HIV/AIDS knowledge or prevention, physical activity, and fruit and vegetable consumption. Data are collected from a random sample of adults (one per household) through a telephone survey. 2015 dataset was selected for this project, which contains over 441,000 records with 330 columns. After the data cleaning and preprocessing phase, only 250,000 records with 22 columns representing various health-related attributes such as: 
Age, Gender, and BMI. 
Smoking and Alcohol Consumption. 
Physical Activity, Diet, and Blood Pressure. 
Previous Medical History (e.g., stroke, heart attack). 
Diabetes Status (binary target variable).

# Basic Information​
Dataset source -https://www.kaggle.com/code/alexteboul/diabetes-health-indicators-dataset-notebook/input​
Background understanding - The Behavioral Risk Factor Surveillance System (BRFSS)​
Data Understanding - 2015 Codebook Report​

# Dataset review and analysis​
# Data Selection – Year 2015, latest in the records.​
Data Cleaning​
From 400K records to 250K records​
From 330 Columns to 22 Columns​

# Data preprocessing​
Define Positive (value = 1) and Negative (value = 0) value for the data​
Data exploratory analysis​
Analyst Data including the correlation of features/columns​

# Outputs – prepare data for modeling​
Cleaned dataset with original diabetes status​
Positive, Negative & prediabetes ​

Cleaned dataset with binary diabetes status.​
Positive & Negative (converted prediabetes to negative)​

Cleaned dataset with 50% balanced outcome​
Added 40K random record for  non-diabetes ​

# Model Development (Binary Diabetes Dataset)​
Random Forest ​
Accuracy – 85%​

Logistic Regression ​
Accuracy – 87%​

KNN for Classification ​
Accuracy – 85%​

# Train Test Split​
Test sample selection – 20%​

# Correlation Heatmap Review​

# Features Selection​
15 correlate features selected for prediction.​
HighBP, HighChol, BMI, Stroke, HeartDiseaseorAttack, PhysActivity, HvyAlcoholConsump, AnyHealthcare, GenHlth, PhysHlth, DiffWalk, Sex, Age, Education, Income​

# Prediction ​
User Interface for collection user input.​
Prediction Output​

​