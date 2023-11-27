# Human-Activity-Recognition-using-Machine-Learning

# The Business Problem
We aim to build a machine learning model to classify a person's actions from a series of measurements captured by sensors. We train our model using the Human Activity Recognition dataset, which is built from recordings of 30 subjects performing daily activities through sensors in their smartphones. We will use suitable models and metrics for this task and evaluate the best model performance. 

# Goals
1.	To explore, analyze and preprocess the data to ensure data quality and provide more reliable predictions.
2.	To create an accurate and robust machine learning model for Human Activity Tracking Recognition. 
3.	To classify the type of movement among six categories: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, and LAYING.
4.	Comparing our results with a research paper that uses machine learning models to predict human activity.

# Details on the dataset
- Dataset:
The dataset has been collected as part of an experiment consisting of a group of 30 volunteers aged 19-48. They performed six different activities while wearing a waist-mounted smartphone equipped with accelerometer and gyroscope sensors. 
How was it collected:
•	The dataset was collected from 30 individuals, referred to as "subjects" in this dataset, who wore smartphones attached to their waists while performing various activities.
•	During these activities, data was recorded using sensors, specifically accelerometers and gyroscopes, integrated into the smartphones. 
•	To ensure accuracy and reliability, the experiment was also video recorded, and the collected data was manually labeled.
What does it contain:
•	Total 563 features including the Subject and Activity.
•	Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30
•	Using the sensors, the dataset captures two main types of signals: '3-axial linear acceleration' (tAcc-XYZ) from the accelerometer and '3-axial angular velocity' (tGyro-XYZ) from the gyroscope. These signals come with multiple variations. 
•	To prepare the data for analysis, it underwent preprocessing, including the application of noise filters. 
•	The dataset was then sampled in fixed-width windows, each lasting 2.56 seconds and overlapping by 50%. As a result, each window contains 128 readings, providing a comprehensive set of data for further analysis.

# Who collected the dataset:
The data has been gathered by the following contributors:
Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Alessandro Ghio(1), Luca Oneto(1) and Xavier Parra(2).
1 - Smartlab - Non-Linear Complex Systems Laboratory
DITEN - Universit‡  degli Studi di Genova, Genoa (I-16145), Italy. 
2 - CETpD - Technical Research Centre for Dependency Care and Autonomous Living
Universitat PolitËcnica de Catalunya (BarcelonaTech). Vilanova i la Geltr˙ (08800), Spain.

# Link to the dataset: 
https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

# Methodology
Python will serve as the primary programming language for constructing solutions, with the utilization of Python libraries like pandas and NumPy for data analysis and transformation as needed. Additionally, we will harness open-source libraries from scikit-learn for the implementation of classification models taught as part of this course. 

# We will include below steps in our project implementation: 
I.	Exploratory Data Analysis
II.	Data Pre-processing
III.	Train Test split for modelling
IV.	Prediction using Logistic Regression; Bagging and Boosting Techniques.
V.	Metrics evaluation and finding the model with the best accuracy.
VI.	Discuss the results and compare with Research paper based on the same dataset.

# Applications of the Project: 
Our ML model designed for predicting human activity has numerous applications in healthcare and in continuous monitoring of an individual's daily lifestyle through smartphones:
1.	Daily Health Monitoring: In future, these results can be used for making smart watches and similar devices which can track a user’s activity and notify him/her of the daily activity log. 
2.	Elderly Care: They can also be used in devices in the hospitals for monitoring patients especially elderly people, or anyone who needs constant supervision.
