# Autoscout24-Car-Price-Prediction-Tool

In this project, a model that will help Autoscout24 predict the future prices of vehicles was developed. With the inflation of price, shortage of raw materials and even the current war happening between Ukraine and Russia, Autoscout24 is finding it challenging to settle on a fair price of the cars that is benefiticial to both the customers and the car dealers. There is also very high competition in the market, the customers are not very loyal as well. 

For this project the dataset was collected from two sources and integrated together after cleaning the dataset. 

First Dataset: https://www.kaggle.com/datasets/ander289386/cars-germany

Second Dataset: https://www.kaggle.com/datasets/promptcloud/autoscout-automotive-data

The null hypothesis formulated stated that none of the features of the vehicle were significant to determining the price and the reverse was the alternate hypothesis. This was hypothesis was tested with t-test and p-value. The result led to the rejection of the null hypothesis for all vehicle features except the car's model.
Using predictive analysis, a multiple linear regression model was developed to find the relationship between the vehicle futures and the price. The R squared value was 0.828 meaning that only 82.8% of the price is explained by the vehicle features. The model was trained with the data between 2011-2020 and was tested with the data in 2021. This way the model was tested to predict the future prices of the car.

With the presented regression model, the future prices of German cars sold by Autoscout24 can be estimated. The values are not exact, but it gives a rough estimate of what the prices can be. With the model, Autoscout24 can determine what car features have the most effect in determining the price of the car and dynamic pricing can be achieved. This prediction tool will also help Autoscout24 to manage their dealership pricing strategy better.
