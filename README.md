# Predicting-the-price-of-Airbnb-rentals-in-New-York-City
In this project I attempted to use multiple ML techniques to see how effectively I could predict the price of Airbnb rentals in New York City. This project was part of a kaggle competition I had entered.

Data
The dataset used was a .csv file consisting of 41331 rentals between 2008 and 2020. Given the relatively unintensive wrangling required for the data, I cleaned my dataset in Excel and selected a total of 37 variables that would be used to predict price in the various models. I didn't necessarily needall 37 variables for each technique but I knew that at least 37 of these variables would be useful in some capacity for my analysis. 

Measure of success
To measure the success of my predictions, I measured the RMSE(Root Mean Squared Error) on the test sample of data. RMSE is most useful when large errors are particularly undesirable and It would provide a strong baseline for how effective my model is at predicting Airbnb prices. 

Techniques
I initially used basic techniques such as Linear Regression and Random Forest to get a sense of how well I could predict the price of rentals in New York. Tinkering with this basic process allowed me to hone in on the variables that seemed to affect the price of Airbnb rentals the most. I then proceeded to use a Tunned Random Forest model to gain more effective predicitons. Although my test RMSE was significantly reduced, I decided to employ a more complex technique to acheive better results. I finally opted to convert my dataset into a matix and use XGboost to gain my most effective predictions. You can find a copy of my work in this repository.
