# Data Science Wage Prediction 2020 (During Crisis)

* Developed an instrument to estimates Data Scientists wages (MAE ~ $ 15 K) to serve as a wage comparator when negotiating the pay.
* Used Selenium and Chromdriver to scraped over 1000 job descriptions on from Glassdoor.
* Quantified technical requirements from skills requirements and emphasize placed on Python, Excel, AES & Spark. 
* Tested the mode on Lasso, Random forest, Linear regression using GridsearchCV to find the best fit  
* Developed front end API using flask 

## Packages & Tool Kit
**Packages:** Pandas, Numpy, Sklearn, Matplotlib, Seaborn, Flask.

**Web Framework:** ```pip install -r requirements.txt``` 


## Resources & References

**Front End Production Flask:** https://towardsdatascience.com/productionize-a-machine-learning-model-with-flask-and-heroku-8201260503d2

**Github:**

https://github.com/arapfaik/scraping-glassdoor-selenium

https://github.com/PlayingNumbers

## EDA Results & Insights

![alt text](https://github.com/Rupesh707/Data-Science-Wage-Prediction2020/blob/master/Images/Avg_salary_by_%20state.png "Average Salary by top 10 States")
![alt text](https://github.com/Rupesh707/Data-Science-Wage-Prediction2020/blob/master/Images/Correlations_Viz.png "Correlations")
![alt text](https://github.com/Rupesh707/Data-Science-Wage-Prediction2020/blob/master/Images/Jobs_by_Location.png "Jobs by Location")

## Models Used

Comparisons were made with a different model to find the most suitable Mean Absolute Error (MAE). From the below models, Random Forest model outclassed the rest.

*	**Random Forest** : MAE = 14.90

*	**Linear Regression**: MAE = 20.76

*	**Lasso Regression**: MAE = 21.09


## To further improve 

Contributions are open to everyone.
