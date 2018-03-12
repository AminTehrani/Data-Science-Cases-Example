# Data-Science-Cases-Example
This Repository contains 4 case studies and tries to demonstrate how to tackle a use case as a Data Science

<h2> Case Study 1: Quick Quote - Insurance Industry- </h2>

Brief Case Study Description:

in this case study we want to develop a model to predict the price of car insurance as a quick quotation assistant. the labeled data has been provided through SQL servers and data sets are reletivly large.  

<h4> Step 1- Get Data </h4>

In this case study we assume the data is stored in a relatioanal Database so we need to use SQL to extract data 
-- we use SQLALCHEMY to connect to sql servers and access data


<h4> Step 2- Initial exploration </h4>

In this step we use PANDAS package to store the data in DataFrame for furthur investigation and manipulation
we use basic functions to get initial insight about the data like pd.info , pd.describe, pd.isnull.count_value 
At this point we have to get some idea about missing data and how to deal with them

<h4> Step 3- Data manipulation and Visualization </h4>

In this step we manipulate data to create new features like convert age to age group or income into income range 
We also change the type of some data to categorical data like female and male from string to categorical (We use tools in pandas)

Later we try to visualize data to find trends and better insight using the following packages ( matplotlib, seaborn, bokeh, and plotify)
Some of this plots are including histograms or distplots, violinplots, and pairplots we also use correlation tools to find and identify corrolated featurs 

<h4> Step 4- Formulate Hypothesis </h4>

In this step we try to identify the features correlated to the target feature. like age group, occupation group, # of owned car, income range, # of accidant during last 5 years, marrige status, # of kids, home insurance status, car model, car price, car millage, etc



<h4> Step 5- Preprocessing the data </h4>

We convert some categorical values to numerical values like Female and male to 0 and 1  or convert the category of occupations into series of columns of 0,1 to uniqely identify occupations with zeros and ones. (We use tools in pandas and sklearn.preprocessing packages)

We split the data to Training and Testing data 

<h4> Step 6- Modeling </h4>

we need to test different models and try to tune them and compare them to find the best one
For this regression case study we could try following models: - Lasso
                                                              - elastic net
                                                              - SGD regression
                                                              - rigid regression 
                                                              - SVR( linear)
                                                              
 We use only train data to fit the models
 we also use cross validation , gridSearchCV, and RandomizedSearchCV to find the tuned model
 (we use sklearn packages in this step)
 
 <h4> Step 7- Compare models </h4>
 
 In this study we use accuracy scoring as a tool to compare these models ( use sklearn. metrics.accuracy_score )


<h4> Step 8- Save the model </h4>

after finding the best model we save the model 







