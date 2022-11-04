# Capstone_2_Appliance_Energy_Prediction

#Google Drive Link- https://drive.google.com/drive/folders/1BCkmDXLOwWRts3pVDx4WYIMVi2iDKa4M?usp=share_link

#Github Link- https://github.com/pankaj-beldar/Capstone_2_Appliance_Energy_Prediction

The understanding of the appliances energy use in buildings has been the subject of numerous research studies , since appliances represent a significant portion (between 20 and 30% of the electrical energy demand . For instance, in a study in the UK for domestic buildings , appliances, such as televisions and consumer electronics operating in standby were attributed to a near about 10% increase in the electricity consumption. Regression models for energy use can help to understand the relationships between different variables and to quantify their impact. Thus, prediction models of electrical energy consumption in buildings can be useful for a number of applications: to determine adequate sizing of photovoltaics and energy storage to diminish power flow into the grid , to detect abnormal energy use patterns , to be part of an energy management system for load control , to model predictive control applications where the loads are needed , for demand side management (DSM) and demand side response (DSR) and as an inputfor building performance simulation analysis
Regression plot of Dependent Variable with other Features
![RegressionPlot](https://user-images.githubusercontent.com/111692879/199649195-4d1664f7-f77f-42a3-aad1-6cc368bae5e4.png)

Daywise hourly Appliances use-
![day hourwise Appliances](https://user-images.githubusercontent.com/111692879/199649307-c6a09056-bca3-4dcb-b38b-a54a1e15f233.png)
![phase of day](https://user-images.githubusercontent.com/111692879/199649394-aded34c3-db72-4abc-a097-fcde00638c97.png)

Feature Selection-
F Value-

![F value](https://user-images.githubusercontent.com/111692879/199649454-09a99f99-950f-488f-8e53-201ef203f02b.png)

Variance Threshold-

![threshold variance](https://user-images.githubusercontent.com/111692879/199649544-fde47b5f-f72b-4119-931c-950ac73be9be.png)

Principal Component Analysis-

![pca](https://user-images.githubusercontent.com/111692879/199649584-8bd1f456-8bfd-4f89-be8c-e8e0dd734f80.png)

Feature Importartance-

![ft](https://user-images.githubusercontent.com/111692879/199897746-b5a56d96-bfb0-48e8-8c41-af59468be97b.png)


Optimal Model Based on R2 Score, MAE, RMSE

![result](https://user-images.githubusercontent.com/111692879/199649795-25e666c0-d512-4b50-a2f3-1496fc6e6b81.png)

Model Explanability- LIME, Eli5

![image](https://user-images.githubusercontent.com/111692879/199649880-52ae52de-e8f2-41bc-956c-d82e571291d5.png)


The household appliance energy consumption prediction models based on Linear Regression, Lasso Regression, Ridge Regression, DecisionTree Regressor Random Forest Regressor, Adaptive Boosting Regressor, Gradient Boosting Regressor, Bagging Regressor, K Neighbors Regressor and Linear SVM are explored.
Upon appropriate preprocessing and fitting the ten models, we compare and evaluate the best model with lowest error and the highest R-squared score.
When evaluating the influence of Random Variable attribute the linear models have assigned near zero weights to the random variable, negating its influence in prediction of the target variable.
Random Forest Regressor was found to be the best performing model with an R-squared score of 0.64.
After optimizing the hyperparameters of the Random Forest Regressor,doing principle Component Analysis, its R-squared score increased from 0.62 to 0.64.
Data from a wireless sensor network that measures humidity and temperature has been proven to increase the prediction accuracy. The data analysis showed that data from the kitchen, laundry room, living room and bathrooms had the most important contributions. Data from the other rooms also helps in the prediction. When looking at the appliances in each room , it can be seen that the laundry, kitchen and living rooms would be expected to have the highest contributions because of the equipment present. The prediction of appliances’ consumption with data from the wireless network indicates that it can help to locate where in a building the main appliances’ energy consumption contributions are found.
When using all the predictors the light consumption was ranked highly. However, when studying different predictor subsets, removing the light consumption appeared not to have a significant impact. This may be an indication that other features are correlated well with the light energy consumption.
The possible explanation for why the pressure has a strong prediction power may be related to its influence on the wind speed and higher rainfall probability which could potentially increase the occupancy of the house.
As this dataset has a time component to it, we believe that better performances can be achieved by using Time Series Analysis concepts.
This study has found curious relationships between variables. Future work could include considering weather data such as solar radiation and precipitation. Also occupancy and occupant’s activity information could be useful to improve the prediction and find its relationship with other parameters (exterior weather for example). The wireless sensors could also measure CO2 and noise to help in the prediction and to track the occupant’s movement from room to room and time spent in each room.
