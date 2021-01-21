# Linear Regression Ecommerce Consulting Project

Provided with a dataset about a companies' mobile app and website usage I try and gain insights about how they should take to improve dollars spent on their product. Data also provided in the dataset is Average Session Length, Yearly Time Spent, Yearly Dollars Spent and Length of Membership. We are ultimately trying to predict how much a user will spend per year and what could we do to improve this number, i.e. get users to spend more money.

By exploring the data there are a lot of initial correlations that are easy to see such as Yearly Time Spent and Average Session Length. Also, Time on App and Yearly Dollars Spent as well as Time on Webiste and Yearly Dollars Spent.

Once the data was processed and ready for the model it was fit using a Linear Regression. The test data was then run through the model and scored a Mean Absolute Error of ~8. This means for a prediction of how much someone was going to spend yearly, the model on average was only 8 dollars off.

What was important to note is the coefficients. The strongest predictor was Length of Membership, this is not suprising if they are loyal to the brand for a logn time they are more likely to spend a lot of money and time on the product. What was suprising was the difference between the coefficients of Time spent on the mobile app vs Time spent on the website. The coefficient for Time spent on the mobile app had a value of almost 39, where the coefficient for the website was a measly 0.45. For context the highest predictor Length of Membership had a value of 61. 

This leaves two possible routes to give the company. 

1) Spend more resources on further developing the mobile application because it already seems to be successful and working well. Whereas the website is far     inferior and not worth the time or effort.

2) Spend more resources on the website because the mobile app is doing so well there is no need to keep improving. Try and concentrate on efforts on getting the website to be as productive as the mobile app.


Programming Languages: Python

Tools/Libraries: Pandas, NumPy, SciKit-Learn(SKLearn), Matplotlib, Seaborn, Jupyter Notebook,
