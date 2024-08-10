Project Overview:  
In order to reduce energy consumption and extend equipment lifespan, there is a need to generate and implement a Room Occupancy Detection model.  
Predicting room occupancy will enable automatic adjustment of the HVAC (Heating, Ventilation and Air Conditioning) system setpoints that will minimize energy consumption when the room is not occupied.  

Installation and Setup:  

Codes and Resources Used:  

·      Editor: Jupyter Notebook   
·      Python Version: 3.9.13

Python Packages Used:  

·      Data Manipulation: pandas, numpy  
   
·      Data Visualization: matplotlib, seaborn  

·      Machine Learning: sklearn  

Data:  
The dataset used for this project was taken from the UC Irvine Machine Learning Repository.  
The data used is the Occupancy Detection which consists of three datasets. The three datasets was used as training, validation and test datasets respectively.  

Results and Evaluation:  
There were two models generated for this project namely the K Nearest Neighbor (KNN) and the Support Vector Machine (SVM) models. These models support binary classification which aligns with this project.  
Both models performed well predicting the target for both the validation dataset and the test dataset.  
The accuracy scores for both models using the validation and test datasets were over 90% with the SVM performing slightly better compared to the KNN model.

References:  
1. Candanedo, Luis. (2016). Occupancy Detection . UCI Machine Learning Repository. https://doi.org/10.24432/C5X01N.
2. SVM vs KNN in Machine learning. https://www.geeksforgeeks.org/svm-vs-knn-in-machine-learning/
3. Brownlee, Jason(2020). How to Predict Room Occupancy Based on Environmental Factors. https://machinelearningmastery.com/how-to-predict-room-occupancy-based-on-environmental-factors/
4. Mazuder, Saikat. (2024). 5 Techniques to Handle Imbalanced Data for a Classification Problem. https://www.analyticsvidhya.com/



