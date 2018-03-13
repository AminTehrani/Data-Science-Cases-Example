 Data-Science-Cases-Example
This Repository contains 4 case studies and tries to demonstrate how to tackle a use case as a Data Science

<h2> Case Study 4: Support advertising decisions - Telecommunications Industry- </h2>

Brief Case Study Description:

in this case study we want to develop a model to support advertising decisions based on customers data saved in HDSF clusters.

the data is not labeled. 

<h4> Step 1- Get Data </h4>

first we need to create a spark profile (it can be local profile or server profile)
then we can access the data using pyspark tools and save them in dataframe.

<h4> Step 2- Initial exploration </h4>

In this step we use PANDAS package for furthur investigation and manipulation
we use basic functions to get initial insight about the data like pd.info , pd.describe, pd.isnull.count_value 
At this point we have to get some idea about missing data and how to deal with them

<h4> Step 3- Data manipulation and Visualization </h4>

In this step we manipulate data to create new features like convert age to age group
We also change the type of some data to categorical data like female and male from string to categorical (We use tools in pyspark)

We may need to modify our pyspark codes to create these new data types by map-reduce fnuctions

Later we try to visualize   data to find trends and better insight using the following packages ( matplotlib, seaborn, bokeh, 
and plotify)
Some of this plots are including histograms or distplots, violinplots, and pairplots we also use correlation tools to find and identify 
corrolated featurs 


<h4> Step 4- Formulate Hypothesis </h4>

In this step we try to identify the features correlated to the target feature. like age group, avg. data usage per week, zip code, service speed, cable status etc 


<h4> Step 5- Preprocessing the data </h4>

We convert some categorical values to numerical values like Female and male to 0 and 1.
We may need to modify our pyspark codes to createconvert these data types by map-reduce fnuctions
We split the data to Training and Testing data 

<h4> Step 6- Modeling </h4>

we need to test different models and try to tune them and compare them to find the best one.
For this clustering case study, we could try the following models:       
  
 <ol>
<li> K-means  </li> 
<li> Bisecting k-means </li> 
<li>  GMM </li> 
 <li>  NMF </li> 


</ol>

                                                              
 (we use pyspark.ml , sklearn packages in this step )
 
<h4> Step 7 - Deep Learning model </h4>
 
 we can also use keras packages to create different neural network model with different layers and width
 
<h4> Step 8- Compare models </h4>
 
we should choose metrics to compare the models it can be crosstab , cosine similarities etc

<h4> Step 9- Save the model </h4>

after finding the best model we save the model 







