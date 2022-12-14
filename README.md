Data

The dataset contains 32581 records. The loan_status variable is the predictor column(dependent feature). It consists of 0 and 1. The 0 indicating the credit risk free and 1 indicating the existence of credit risk. The data set clearly indicates it to be a classification Machine Learning task. So we decided to go out with classification modeling techniques such as Logistic Regression, Naive Bayes, Decision tree, Random Forest, K Nearest neighbor. The data set contains a huge number of records. There are 21 features after using encoders.Therefore it is wise to split the train test into 75:25 and n>10,000. The reason 5 models we are choosing is because of the fact that we intend to bring out the best accuracy, but making sure that the bias and variance remains balanced.

EDA

The implementation part starts with the Exploratory Data Analysis(EDA), different Visualization, feature Engineering, Ensembling methods, modeling, hyperparameter tuning. The goal is to produce a low bias and low variance model in the long run. Therefore trail and testing with sampling, tuning, feature selection methods have been carried out consistently.
The Visualization techniques were used initially as the data set was large to find the patterns, understand the data, extract the hidden information.
As per EDA is concerned it started with data cleaning such as finding null values, Nan etc. Zero value was checked as we cannot have a loan amount , person age values zero. Pandas profiling was used to get the full fledged report.
Visualization consisted of a distribution plot to check the skewness, box plot was used to remove any outliers, pair plots were used to check the relationship of each independent variable with the dependent variable. Heatmap was used to check the correlation values. Histogram was used to see if there were any deviating values. Principal component analysis. 4.) was used to see if there was any possibility of dimensionality reduction.


<img width="621" alt="Screen Shot 2022-12-14 at 2 06 25 PM" src="https://user-images.githubusercontent.com/97769635/207703269-6c9e98f0-1ed0-4337-a18a-59334666044f.png">

<img width="614" alt="Screen Shot 2022-12-14 at 2 07 18 PM" src="https://user-images.githubusercontent.com/97769635/207703414-95cb9153-a409-4d72-bfb0-99113d118a2b.png">


<img width="591" alt="Screen Shot 2022-12-14 at 2 08 08 PM" src="https://user-images.githubusercontent.com/97769635/207703543-6a070f6e-b1ef-4000-a88c-b3654c07ac6b.png">


<img width="576" alt="Screen Shot 2022-12-14 at 2 09 27 PM" src="https://user-images.githubusercontent.com/97769635/207703816-36961444-17f7-4db1-8184-6dae5133d8e0.png">

