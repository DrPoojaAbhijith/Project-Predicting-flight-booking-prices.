# Flight-Booking-Price-Prediction
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/8351f13a-fc57-44a9-8c83-f19743e7e3a9)




## Table Of Contents

**1.	Project Objective**

**2.	Data Description**

**3.	Data Pre-processing steps and inspiration**

**4.	Inferences made from the data**

**5.	Choosing the algorithm for the project**

**6.	Motivation and reasons for choosing the algorithm**

**7.	Conclusion**
 
## Project Objective
The objective is to analyse the flight booking dataset obtained from a platform which is used to book flight tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers. Apply EDA, statistical methods and Machine learning algorithms in order to get
meaningful information from it.

## Data Description
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/58e56e8b-9903-4916-85a0-f6bfbdc53c97)

 Dataset Information:
Flight booking price prediction dataset contains around 3 lacs records with 11 attributes

 
## Data Pre-processing steps and inspiration
a.	Loading the Dataset: We Have Loaded the dataset using pandas.

b.	Checking for Data Types: It is imperative to inspect the data types of each column to ensure consistency and appropriateness for subsequent analyses and operations.

c.	Preprocessing Data: In the Preprocessing step we have Inspected the dataset. And removed the columns which unwanted. and we found that there are no missing values in the dataset. And we have done Label Encoding in order to do statical analysis. And machine learning model implementation. After that we have standardized the data which feuded to the ML models to get better performance of the model.


d.	Handling Outliers: There is an outlier in the ‘Duration’, ‘days left’, ‘price’ columns. And we have removed the outliers. With IQR Range.


## Inferences from the Data

#### So here our target is to predict price. so, our EDA will also be done by targeting the price column which is dependent on other independent variables.

### 1)	AIRLINE V/S PRICE
 ![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/e924bf98-4fc3-466c-930a-a26e524e5fc4)

•	Air India and Vistara Has Highest Ticket Price Compared to other airlines.

•	Remaining airlines prices are more or the same.

### 2)	FLIGHT V/S PRICE
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/d613fac5-2b3e-4d83-90fd-ab9c5e50d6b2)
 
•	Most of the flights are in range up to 10000 price range


### 3)	SOURCE CITY V/S PRICE
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/5ee38d56-9f8c-4fb0-b163-f86980a970aa)

•	Most of the Cities are in same range of price

### 4)	STOPS V/S PRICE
 ![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/1de472c0-3493-4097-bad8-dac0ce1043ee)

•	the price for ‘one’ stop is higher than others

### 5)	DEPARTURE TIME V/S PRICE
   ![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/5c79ed51-f7a1-43be-8a3d-0efc63178b1e)

 •	Most of the Departure Time are in same range of price. 

### 6) ARRIVAL TIME V/S PRICE
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/d23e6694-6aa4-4245-b8de-7473b9bcfd67)
 
•	Evening and Morning Prices are high and Late night is having low prices

### 7) DESTINATION CITY V/S PRICE
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/e2681812-bd5f-48d5-ab8b-0231eb5c25fc)

•	The Delhi has low price compared to others.

•	Remain all are more or the same range.

### 8) CLASS V/S PRICE
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/3de50e0c-cd91-4d40-b483-ed1845710699)
 
•	The Business class is having high price than the Economy.

### 9) DURATION V/S PRICE
 ![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/809c466b-bef8-41fa-98ed-0753f07c9c4e)

•	as The Duration Increase the prices also increasing.

•	But there is no straight forward Correlation.  Some durations having low prices also.

•	Majority of the prices are increasing as duration increase 

### 10) DAY’S LEFT V/S PRICE
 ![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/a0dc2e28-5b93-47f9-bfe4-bac22f2c6b74)

•	as The Day's left are increasing the prices falling down.

•	It is indicating that early bookings are good to save money.

### 11) CATEGORICAL FEATURES
![image](https://github.com/DASARIUDAYPRAKASH/Flight-Booking-Price-Prediction/assets/130547847/4501a2da-e6dd-4a16-8e14-b28d4d7a6179)
 
**•	AIRLINE: The Vistara and air India has high frequency respect to the count. SpiceJet is has Low Frequency**

**•	SOURCE CITY: The Delhi and Mumbai has high frequency respect to the count. Chennai is having Low Frequency**

**•	DEPARTURE TIME: Early Morning and Morning has high frequency respect to the count. Late Night is having Low Frequency.**

**•	STOPS: One Stop has high frequency respect to the count.**

**•	ARRIVAL TIME: Night and Evening has high frequency respect to the count. Late Night is having Low Frequency**

**•	DESTINATION CITY: Delhi and Mumbai have high frequency respect to the count. Chennai is having Low Frequency.**

**•	CLASS: Economy Class high Frequency.**

## Choosing the algorithm for the project
Here we have chosen different model’s that can predict the price of the flight ticket booking Models listed below:

**1.	Linear Regression**

**2.	Decision Tree Regressor**

**3.	Random Forest Regressor**

•	Motive for all this model is to predict the ticket price.

•	In this model our independent features would be all expect flight and price.

•	And we will evaluate the model performance with the help of r2 score, MAE, MAPE, MSE, RMSE. Root Mean square error (RMSE). 


## Motivation and reasons for choosing Model’s

**1.	Linear Regression**

•	Motive for choosing this model is to predict the target which is continues in nature. Which is regression problem.

**2.	Decision Tree Regressor**

•	Decision tree models are adept at handling classification and regression problems. 

•	by recursively partitioning the input space into regions, making predictions based on the majority class or average value within each region.

•	This allows them to handle both categorical and numerical data, making them versatile for a wide range of predictive tasks in various domains.

**3.	Random Forest Regressor**

•	Random Forest offers high predictive accuracy by averaging predictions from multiple decision trees, making it robust to overfitting. 

•	It handles non-linear relationships well, provides feature importance insights, and is resilient to outliers and missing data. With its scalability, ability to handle large datasets, and no assumptions about data distribution, Random Forest is a versatile choice suitable for various machine learning tasks.

## Conclusion

•	Based on the analysis conducted and the model’s performance on the dataset, it can be concluded that the Liner Regression for predicting Ticket Prices and Decision Tree Regressor and Random Forest Regressor will be fit and suitable for predicting the flight ticket booking price.

### In Linear Regression we got the evaluation matrix.

•	 r2_Score:                                               0.9049847760699258

•	mean abs error:                                          4625.601159976593

•	mean absolute percentage error:                          0.43627317283189276

•	mean sq error:                                           48931028.45225085

•	RMSE:                                                    6995.071726026178

### In Decision Tree Regressor we got the evaluation matrix.

•	r2_Score:                                                0.9761309874775854

•	mean abs error:                                          1168.7175598163174

•	mean absolute percentage error:                          0.07422407497383977

•	mean sq. error:                                          12292086.284203626

•	RMSE:                                                    3506.0071711569026

### In Random Forest Regressor we got the evaluation matrix.

•	r2_Score:                                                0.9852298788429149

•	mean abs error:                                          1085.061065975238

•	mean absolute percentage error:                          0.07049862212289662

•	mean sq. error:                                          7606330.740349579

•	RMSE:                                                    2757.9577118494003

## Thank You!

