#energy_demand_forecasting

#objective
The main aim of this project is to forecast total weekly energy demand.

#who will benefit?
1. Energy companies
2. Ministry of energy.

#function of final model
i) If energy companies can accurately forecast energy consumption in the future, they will know exactly how much they need to produce.
ii) If they produce too much, the grid can be oversupplied and fail. This is wasted energy, incurred repair costs, incurred energy which is passed on to you and me. It would be an emergency.
iii) If they produce too little, there will be major power cuts. They would have to rush and pay tons of overtime costs to get power up.
iv) If energy companies can forecast energy demand sufficiently, the distribution of energy between fossil fuels and renewable energy sources can be optimized and we will have a much greener planet.
A good forecast of total weekly energy demand will ease the above problems and that is the main aim of this project.

#dataset
Was found Kaggle. https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather

#models tested
1) SARIMAX
2) Random Forest Regression
3) Gradient Boost Regression
4) XG Boost Regression

#results
Gradient Boost proved to be the best model out of the 4 tested.

#drawbacks and steps forward
The best RMSE on the testing set found was 146,529 MW. This is 2.99% of mean. 
The training set only contained data for 3 years. That is only 3 seasonal cycles. 
Given more data, the results will improve. 
Computational power is not strong to tune a larger number of model parameters as well as a wider range of parameter range.

The next step would be to predict daily demand which will be a better indicator than weekly demand.

#folders in repo
1. data - contains the datasets(raw) used as well as wrangled data (processed)
2. notebooks - contains separate notebooks for each step eda, wrangling, statistical analysis, modelling as well pickled files of the models tested)
3. presentation - summarizes the data in an easy to read manner
4. proposal - contains the project proposal which was the first input to this project
4. reports - goes into more details regarding the project outcomes