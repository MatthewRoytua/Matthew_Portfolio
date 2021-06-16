# Matthew_Portfolio
Data analyst and data science portfolio

# [Project 1: Data Exploration: Project Overview](https://github.com/MatthewRoytua/Projects/tree/main/Project_1)
Explore 5 high level business questions related to the data with Pandas and Data Viz (seaborn, matplotlib):

* What was the best month for sales? How much was earned that month?
* What city had the highest number of sales?
* What time should we display advertisements to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most?

![](/images/comparison.png)


# [Project 2: Titanic Survivor Classifier: Project Overview](https://github.com/MatthewRoytua/Projects/tree/main/Project_2)

The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, 
there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, I build a predictive model that answers the question: “What sorts of people were more likely to survive?” 
using passenger data (ie name, age, gender, socio-economic class, etc).

![](/images/accuracy_score.png)


# [Project 3: Data Exploration: Project Overview](https://github.com/MatthewRoytua/Projects/tree/main/Project_3)

From the data provided from [Our World in Data](https://ourworldindata.org/covid-deaths), explore the spread of infection and 
death worldwide caused by Covid-19 using [Microsoft SQL Server](https://github.com/MatthewRoytua/Projects/blob/main/Project_3/Covid_Portfolio_Project.sql).
And create a simple dashboard using [Tableu Public](https://public.tableau.com/app/profile/matthew5246/viz/CovidDashboard_16231640872460/Dashboard1)

![](/images/coviddash.JPG)


# [Project 4: Data Science Salary Estimator: Project Overview](https://github.com/MatthewRoytua/Projects/tree/main/Project_4)

* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* Built a client facing API using flask

Code and Resources Used:
* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle
* For Web Framework Requirements: pip install -r requirements.txt
* Scraper Github: https://github.com/arapfaik/scraping-glassdoor-selenium
* Scraper Article: https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905
* Flask Productionization: https://towardsdatascience.com/productionize-a-machine-learning-model-with-flask-and-heroku-8201260503d2

![](/images/Project_4_HeatMap.png)  ![](/images/Project_4_Job_State.png) 
