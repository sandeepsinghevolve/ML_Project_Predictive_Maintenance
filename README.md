# ML_Project_Predictive_Maintenance
"Predictive Maintenance with Machine Learning"
# Introduction
The title of the project is "Predictive Maintenance with Machine Learning". For more detailed descriptions of this project, please read the following sections.

# Problem statement
Machines are critical to all business nowadays, and we expect them to operate at peak level for long time. Normally, we can use corrective maintenance strategy to make the best use of machines. But we could end up costing even higher due to downtime and labor.

Preventive maintenance comes in to reduce unplanned failures while businesses try to address problem in advance. However, the costs could still be high. By using predictive maintenance, we can prevent those unexpected problems more efficiently. We can fix the machines just in time as we monitor and predict the status of them.

In this project, predictive maintenance is the main concept. There are two aspects to do the predictive maintenance in this project, supervised and unsupervised learning. In supervised learning, predicting remaining useful life and failure prediction are the goals. While in unsupervised learning, detecting anomalies of the machine is the target. Python and its machine learning related libraries are the main tools in this project. The solution of this project could help industry to lower the chance of unexpected downtime and reduce costs.

# Aims and objectives
The aim of this project is to propose machine learning solutions for predictive maintenance in responds to Industry 4.0. There are three tasks proposed:
* Anomaly detection: The model should be able to detect the anomalies within data.
* Remaining useful life prediction: The model should be able to predict the remaining useful life of a machine to help people be prepared for maintenance or replacement.
* Failure prediction: The model should be able to predict whether there will be a failure.
# Data source
From DCS,PLC Server including Field sensors,Battery,HT & LT Motors DE & NDE sensors.
IT & QC Deparment data
# Solution approach
This project follows CRISP-DM methodology. Supervised and unsupervised algorithms are used to address set tasks. Please notice that artificial neuron network (ANN) is not explored in this project.
* Anomaly detection: Local Outlier Factor (LOF), Elliptic Envelope, Isolation Forest and One-Class Support Vector Machine (SVM) are used.
* Remaining useful life prediction: Support Vector Machine Regressor is used. For automated machine learning example, Tree-based Pipeline Optimization Tool (TPOT) is used. The output best model is evaluated together. Since the data is rather high-dimensional, feature importance analysis is performed to reduce the training size. The feature-reduced-version of dataset is also modeled to compare the computing time and results.
* Failure prediction: Logistic Regression, KNeighbors Classifier, C-Support Vector Clas- sification with liner kernel, C-Support Vector Classification with RBF kernel, Gaussian Naive Bayes, Decision Tree and Random Forest Classifier are applied.
# Summary of contributions and achievements
* Anomaly detection: All the models achieve almost 100% recall rate and over 70 F1 score.
* Failure prediction: The best classifierachieves87.51% accuracy and five classifiers achieve over 80% accuracy
