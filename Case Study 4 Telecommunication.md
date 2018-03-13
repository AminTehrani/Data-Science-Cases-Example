 Data-Science-Cases-Example
This Repository contains 4 case studies and tries to demonstrate how to tackle a use case as a Data Science

<h2> Case Study 2: Loan Defult Prediction - Finance Industry- </h2>

Brief Case Study Description:

in this case study we want to develop a model to predict if a loan request will be paid or be late paid or be charge off to assist the officer.

 The labeled data has been provided through different comma seprated file inclueding customer data like ammount of loand, etc and one Json file including federal and rigional indicators like unemployment rate etc.

<h4> Step 1- Get Data </h4>

we need to access the data using pandas tools like pd.read_csv and pd.read_json and save them in different dataframes
We need to merge dataframes into one DataFrame and deal with NAN values. 


<h4> Step 2- Initial exploration </h4>

In this step we use PANDAS package to store the data in DataFrame for furthur investigation and manipulation
we use basic functions to get initial insight about the data like pd.info , pd.describe, pd.isnull.count_value 
At this point we have to get some idea about missing data and how to deal with them

<h4> Step 3- Data manipulation and Visualization </h4>

In this step we manipulate data to create new features like convert age to age group or income into income range 
We also change the type of some data to categorical data like female and male from string to categorical (We use tools in pandas)

Later we try to visualize data to find trends and better insight using the following packages ( matplotlib, seaborn, bokeh, and plotify)
Some of this plots are including histograms or distplots, violinplots, and pairplots we also use correlation tools to find and identify corrolated featurs 

Some potential visualization and correlations are including (income vs loan amount),(income vs interest rate),( # of owned properties vs loan ammount) we need to use our target as color to help visualization 
We also need to group by the data by year, month and rigeon and try to find new correlation like ( regional unemployment rate vs # of charged off loan) or (Fed Fund Rate vs loan amount ) etc

<h4> Step 4- Formulate Hypothesis </h4>

In this step we try to identify the features correlated to the target feature. like age group, occupation group, # of owned car, income range, # of accidant during last 5 years, marrige status, # of kids, home insurance status, car model, car price, car millage, etc



<h4> Step 5- Preprocessing the data </h4>

We convert some categorical values to numerical values like Female and male to 0 and 1  or convert the category of occupations into series of columns of 0,1 to uniqely identify occupations with zeros and ones. (We use tools in pandas and sklearn.preprocessing packages)
We also need to convert our target values (paid or be late paid or be charge off) into 2 columns of 0 and 1 using sklearn.preprocessing
We split the data to Training and Testing data 

<h4> Step 6- Modeling </h4>

we need to test different models and try to tune them and compare them to find the best one
For this classification could try the followung models:   

<ol>
<li> </li>
<li> </li>
<li> </li>
<li> </li>

</ol>
                                                              
 We use only train data to fit the models
 (we use sklearn packages in this step)
 
 <h4> Step 7- Compare models </h4>
 
We need to define our scoring metric for comparing the models like : confusion matrix, sensitivity/ recall , specificity , precision 

<h4> Step 8- Save the model </h4>

after finding the best model we save the model 







