# capstone_project
1. Project Statement
The project aims to employ Legal Analytics in order to predict the winning party given a case. The primary
objective of a Law Firm is to fight cases where chances of success is high. Appropriate analysis and Machine
Learning models aid a firm or a lawyer to make an informed choice based on historical data and sound
statistical analysis.

2. Dataset Details 
The database used dates back to the year 1946 during the beginning of Vinston Court and Warren Court.
There have been many versions since then. The data available can be used with various statistical packages
to perform various analyses with respect to what the business/ Law firm considers important. The advanced
modelling and EDA techniques used in the project will enable the business to calculate and view
relationships among the variables which shall aid the management in making informed decisions. The
database consists of information from 1946. Thus with increase in information, the needed responsibility to
alter/ transform the data is carried out

3. Complexity Involved
a. Find the key area, gaps identified in the topic survey where the project can add value to the
customers and business.
b. Since datasets involving court cases have multiple variables, the variables that aid in the prediction of
"partyWinning" have to be selected. Certain predictor variables involve information that a law firm may
not have access to, before the case begins in the supreme court. Hence these variables are removed
c. Merging of different columns so that it makes sense which further reduces processing and execution
time and then building an accurate model with decent respective model scores using required
libraries and algorithms.To obtain duration of the case , various columns were merged through
appropriate datetime techniques.
d. Since each column is unique, the null value imputation was done diligently using hot deck imputation.
e. Finding out the best target variable as the dataset contained multiple potential target variables.


4. Project Outcome

- Commercial: Given the details of a case, the law firm will be able to predict the outcome which shall
enable the agency to maintain a better track record and select cases where the chances of winning are high.

- Social:Should the petitioner reconsider filing a case based on model results. This will help the petitioner in
saving time and money. Hence the law firm will be able to provide alternate solutions to the petitioner and
gain reputation for the same.


5. METHODOLOGY TO BE FOLLOWED
[a] The Primary step of this project is to understand the relationship between data and the field of Law. The
US supreme court database is used for this project. A dataset which focuses on the case details and final
judgement is chosen for analysis .
[b] As Legal Analytics is a broad field, the plausible target variables and
their respective predictor variables are studied. The Target variable has been identified as the winning party
and the case details as the predictor variables.
[c] The necessary data is prepared only when the data has
been studied for its important characteristics and the potential anomalies it may possess. Exploratory Data
Analysis is performed on the data using Univariate-Bivariate-Multivariate analysis through visual inspection or
statistical tests based on the type of data. These steps build the necessary foundation to perform feature
engineering, data reduction and transformation. 
[d] The next phase is to create a model which is capable of
capturing the characteristics of the target variable. This involves selecting an optimal Hypothesis function (ML
model ) which captures the true relationship between the explanatory and response variables (Low Bias). At
the same time the model must also be able to make good predictions for data that it has not seen before
(Low Variance). Basic models such as Logistic Regression, Linear Regression to advanced models such as
AdaBoost and XGBoost could be tested for the same. 
[e] Various metrics can be used to evaluate the
efficiency of a model. Based on what the business/ research considers important, specific metrics and
thresholds can be used to make our model more appropriate for the Business problem at hand. On achieving
the necessary sufficiency , the model and the methodology is further evaluated in the presence of an industry
mentor.
