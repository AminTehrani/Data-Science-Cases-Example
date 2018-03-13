 Data-Science-Cases-Example
This Repository contains 4 case studies and tries to demonstrate how to tackle a use case as a Data Science

<h2> Case Study 2: Loan Defult Prediction - Finance Industry- </h2>

Brief Case Study Description:

in this case study we want to develop a model to support clinical desicion based on 3 source of data 
1- patent metrics like age, weight etc
2- pation tests like cholesterol level, glucose level etc
3- unstructured descriptions like medical state, previous drug descriptions etc

The labeled data has been provided through different comma seprated file 

<h4> Step 1- Get Data </h4>

we need to access the data using pandas tools like pd.read_csv and save them in dataframe.

<h4> Step 2- Initial exploration </h4>

In this step we use PANDAS package to store the data in DataFrame for furthur investigation and manipulation
we use basic functions to get initial insight about the data like pd.info , pd.describe, pd.isnull.count_value 
At this point we have to get some idea about missing data and how to deal with them

<h4> Step 3- Data manipulation and Visualization </h4>

In this step we manipulate data to create new features like convert age to age group
We also change the type of some data to categorical data like female and male from string to categorical (We use tools in pandas)

Later we try to visualize  numerical data to find trends and better insight using the following packages ( matplotlib, seaborn, bokeh, 
and plotify)
Some of this plots are including histograms or distplots, violinplots, and pairplots we also use correlation tools to find and identify 
corrolated featurs 


<h4> Step 4- Formulate Hypothesis </h4> 

In this step we try to identify the features correlated to the target feature. like age group, occupation group, cholglucose level etc


<h4> Step 5- Preprocessing the data </h4>

We convert some categorical values to numerical values like Female and male to 0 and 1  or convert the category of occupations 
into series of columns of 0,1 to uniqely identify occupations with zeros and ones. 
(We use tools in pandas and sklearn.preprocessing packages)
We also need to convert our target values  into columns of 0 and 1 using sklearn.preprocessing
We split the data to Training and Testing data 

<h4> Step 6- Modeling </h4>

we need to test different models and try to tune them and compare them to find the best one
Here, we use PIPELINE as the following

for <b> numerical data </b>  we'll use a function to get them and use imputer to deal with Null values 
(for example use mean value instead of NA)

for <b> text data </b> we'll act as following
<ol>
<li> Use a function to get text data </li> 
<li> Use HashingVectorizer ( tokenizer over punctuation, use ngram(1,2), dimension reducer => SelectKBest </li>
<li> Use SparseInteraction(degree=2) </li>
<li> Scale data using MaxAbsScaler </li>
<li> Use ML algorithms </li>
</ol>
For this classification could try the followung models:       
  
 <ol>
<li> XGBoost  </li> 
<li> Naive Bayes </li> 
<li>  Decision Tree </li> 
<li>  logistic regression </li> 
<li>  linear SVC </li> 

</ol>

                                                              
 We use only train data to fit the models
 we use sklearn and xgboost packages in this step )
 
<h4> Step 7 - Deep Learning model </h4>
 
 we can also use keras packages to create different neural network model with different layers and width and create a new pipelines 
 
<h4> Step 8- Compare models </h4>
 
we use accuracy scoring to find the best model 

<h4> Step 9- Save the model </h4>

after finding the best model we save the model 







