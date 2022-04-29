Storm Motors is an e-commerce firm who acts as mediators between parties interested in selling and buying pre-owned cars. Based on the Data Collected over the years (more than 50,000 datapoints), whenever a new car details are into the system, predict what should be the selling / buying price (in Euros.) of the pre owned car.

Input Feature include: Seller details, Car specifications (gearbox type, Vehicle type, power PS, Model, Fuel type, brand, Kilometers Travelled), Condition of car (previously repaired or not), Registration Year 

Target Variable: Resale Price in Euros

**Model Accuracy by omitting missing Data**
Random Forest (train set): 92.28%
Random Forest (test set): 86.55%
Linear Regression (train set): 70%
Linear Regression (test set): 69.96%

**Model Accuracy by imputing missing Data**
Random Forest (train set): 90.65%
Random Forest (test set): 84%
Linear Regression (train set): 63.35%
Linear Regression (test set): 63.85%
