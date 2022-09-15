
# Mobile Price Range Prediction
## Intoduction
In this project, we are going to explore and analyse a dataset which contains specifications of two thousand mobile phones and try to predict optimum price ranges for a list of mobile phones in the market by applying various machine learning algorithms such as decision tree, random forest and k-nearest neighbours (knn), Support vector Machine(SVM), Gradient Boosting.
## Problem Statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

**Data Description**

•	Battery_power - Total energy a battery can store in one time measured in MAh

•	Blue - Has bluetooth or not

•	Clock_speed - speed at which microprocessor executes instructions

•	Dual_sim - Has dual sim support or not

•	Fc - Front Camera mega pixels

•	Four_g - Has 4G or not

•	Int_memory - Internal Memory in Gigabytes

•	M_dep - Mobile Depth in cm

•	Mobile_wt - Weight of mobile phone

•	N_cores - Number of cores of processor

•	Pc - Primary Camera mega pixels

•	Px_height - Pixel Resolution Height

•	Px_width - Pixel Resolution Width

•	Ram - Random Access Memory in Mega Bytes

•	Sc_h - Screen Height of mobile in cm

•	Sc_w - Screen Width of mobile in cm

•	Talk_time - longest time that a single battery charge will last when you are

•	Three_g - Has 3G or not

•	Touch_screen - Has touch screen or not

•	Wifi - Has wifi or not

•	Price_range - This is the target variable with value of 0(low cost), 1(medium cost),
           2(high cost) and 3(very high cost).

## Steps involved
1) Installing libraies and getting the dataset.
2) Performing EDA (exploratory data analysis).
3) Drawing conclusions from the data.
4) Preprocessing the data.
5) Training different models.
6) Evaluating metrics of all the models.
## Model used
1. Decision Tree Classifier
2. Random Forest Classifier
3. Gradient Boosting Classifier
4. K-nearest Neighbour classifier
5. XGBoost
6. Support Vector Machine 
## Conclusion
Out of all models used , with Support vector machine  model we were able to get the  training accuracy of 98.3% and testing accuracy of 97%.hence SVM is the best performance model .The model which performed poorly was K Nearest neighbour with training accuracy of 77% and testing accuracy of 70%.
