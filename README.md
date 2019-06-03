# Black-Friday
This time I am doing it using R language. let's see the results. The solutions includes eda(exploratory data analysis), data visualizations, modelling with Machine learning Models such as XgBoost and AdaBooost etc and check the performance using rmse metrics etc to compare the results.

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for a selected high volume products from last month.

They want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

# Frame the problem
Before looking at the data it is important to understand how does the company expect to use and benefit from this model? This first brainstorming helps to determine how to frame the problem, what algorithms to select and measure the performance of each one.

We can categorize our Machine Learning (ML) system as:

Supervised Learning task: we are given labeled training data (e.g. we already know how much a customer spent on a specific product);

Regression task: our algorithm is expected to predict the purchase amount a client is expected to spend on this day.

Plain batch learning: since there is no continuous flow of data coming into our system, there is no particular need to adjust to changing data rapidly, and the data is small enough to fit in memory, so plain batch learning should work.
