                                                     Project: Metro-interstate-traffic-volume

Question/need:

This aim of this project is to create a predictive model using different machine learning models to predict traffic volume of metro interstate located in US. The model has different features such as weather features and holidays that is primary correlated with the traffic volume.


Data Description:

The data represent the Hourly Interstate 94 Westbound traffic volume for MN DoT ATR station 301, roughly midway between Minneapolis and St Paul, MN. Hourly weather features and holidays included for impacts on traffic volume. There are different features as the following.



holiday Categorical	US National holidays plus regional holiday, Minnesota State Fair(e.g., Columbus Day , None)


temp Numeric	Average temp (in Kelvin e.g., 288, 289)


rain_1h	 Numeric Amount in mm of rain (raining per hour - e.g., 0,1)


snow_1h	Numeric	Amount in mm of snow (snowing per hour - e.g., 0,1)


clouds_all	Numeric	Percentage of cloud cover (e.g., 45, 1 )


weather_main	Categorical	Short textual description of the current weather (e.g, Clouds , clear)


weather_description	Categorical	Longer textual description of the current weather (e.g, sky is clear, few clouds)


date_time		DateTime	Date, Time and Hour of the data collected in local CST time (e.g., 2017-01-01 00:07:57)


traffic_volume	Numeric	Numeric Hourly I-94 ATR 301 reported westbound traffic volume (e.g., 6542,4516)



Tools:


I will use python to tackle this problem following libraries:
Panda: For data Processing and data cleaning. 
Matplotlib: For visualization, the relation between features.
And I will build the prediction model using the following machine learning models:


-	Linear Regression
-	Random Forest Regressor
-	Decision Tree Regressor

