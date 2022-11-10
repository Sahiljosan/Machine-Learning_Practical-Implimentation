# Individual Household Electric Power Consumption
![](https://www.energy.gov/sites/default/files/styles/full_article_width/public/qtr-ch3-intro.jpg?itok=edlO53_p)

## <font color=#00008B>Problem Statement</font>
To predict the individual household electricity consumption depending on the following attributes.
#### Attribute Information:
1. `date:` Date in format dd/mm/yyyy
2. `time:` time in format hh:mm:ss
3. `global_active_power:` household global minute-averaged active power (in kilowatt)
4. `global_reactive_power:` household global minute-averaged reactive power (in kilowatt)
5. `voltage:` minute-averaged voltage (in volt)
6. `global_intensity:` household global minute-averaged current intensity (in ampere)
7. `sub_metering_1:` energy sub-metering No. 1 (in watt-hour of active energy).  It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered)
8. `sub_metering_2:` energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9. `sub_metering_3:` energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.


## <font color=#00008B>We have performed</font>
1. Data ingestion
2. Exploratory data analysis
3. Handling the outliers
4. Store the preprocessed data in mongoDB
5. Retrive data from mongoDB
6. Model Building
7. Standardize Scaler
8. Dumo the preprocessed data into pickle file
9. Linear Regression
10. Ridge Regression
11. Lasso Regression
12. Support vector Regression
13. Hyper-parameter turning the SVM model using GridSearchCV
14. Report ( Summary )
15. Store the Best Model in pickle file.


