# Rahul Jha

### Click on the Project Title to view the project!

# [Project 1 - Loan Status Prediction : Project Overview](https://github.com/Rahul713713/Loan_Status_Prediction)
![](/images/loan_status.jpeg)
- Created multiple charts,graphs,countplots,etc. in order to understand how to minimise the risk of losing money while lending to customers.
- Worked on a dataset consisting of 614 rows of data for 12 different features.
- Performed univariate analysis as well as multivariate analysis on various features to understand the importance of every feature.
- Used EDA to understand how consumer attributes and different features help us in identifying customers who are eligible for a loan from customers who are not.

# Problem Statement
Predicting whether an applicant is eligible for the loan that he/she has applied for based on multiple independent variables and Machine Learning. This will help the company in automating the process of checking the eligibility of the applicant for the loan.Now,when a customer applies for a loan, the company has to make a decision whether to approve the loan or not based on the applicant's profile. 

The data that I have contains information about applicants and their Gender,Education,Self_Employed,ApplicantIncome,etc. and whether they are eligible for the loan or not.

# EDA
After cleaning the data,I started with EDA. These are some of the outcomes of EDA 

![](/images/loan_eligibilty_based_on_credit_history.png)
![](/images/loan_eligibilty_based_on_education.png)
![](/images/most_important_features.png)

# Result
    +--------------------------------------------------------------------------------+
    |           *** Model Summary *** [Performance Metric: Accuracy Score]           |
    +-----------------------------------------------+----------------+---------------+
    |                   Model Name                  | Train Accuracy | Test Accuracy |
    +-----------------------------------------------+----------------+---------------+
    |                  Naive Bayes                  |     0.794      |     0.817     |
    |              K Nearest Neighbors              |     0.836      |      0.8      |
    | Logistic Regression - Without Class Balancing |     0.807      |     0.817     |
    |   Logistic Regression - With Class Balancing  |     0.801      |     0.808     |
    |                   Linear SVC                  |     0.807      |     0.808     |
    |              SVC With Rbf Kernel              |     0.824      |     0.808     |
    |                 Random Forest                 |     0.817      |     0.808     |
    +-----------------------------------------------+----------------+---------------+
 


# [Project 2 - Genetic Mutation Classification for Cancer Treatment : Project Overview](https://github.com/Rahul713713/Genetic_Mutation_Classification_for_Cancer_Treatment)
![](/images/CancerTreatment.jpg)
- Created multiple charts,graphs,countplots,etc. in order to understand the data as this was a multiclass classification problem.
- Worked on a dataset consisting of 3321 rows of data for 4 different features.
- All the features are either categorical or text features.
- Performed univariate analysis on various features and also made machine learning models just with a specific feature  to understand the importance of every feature.
- Used Natural language techniques like TfifdVectorizer to converted text data into numerical data.
- Performed Data Analysi and Exploratory Data Analysis
- Used multiple Machine Learning Models like Naïve Bayes, KNN, Logistic Regression,etc. to solve this problem.

# Problem Statement
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers).
Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.
We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

# Result
    +--------------------------------------------------------------------------------------------+
    |                    *** Model Summary *** [Performance Metric: Log-Loss]                    |
    +---------------------------------------------+-------+------+------+------------------------+
    |                  Model Name                 | Train |  CV  | Test | % Misclassified Points |
    +---------------------------------------------+-------+------+------+------------------------+
    |                 Naive Bayes                 |  0.94 | 1.21 | 1.24 |           43           |
    |                     KNN                     |  0.99 | 1.28 | 1.33 |           44           |
    |   Logistic Regression With Class balancing  |  0.50 |  1   | 1.08 |           37           |
    | Logistic Regression Without Class balancing |  0.5  | 1.03 | 1.09 |           36           |
    |       Linear SVC With Class Balancing       |  0.54 | 1.07 | 1.12 |           36           |
    |           Random Forest Classifier          |  0.65 | 1.16 | 1.18 |           38           |
    +---------------------------------------------+-------+------+------+------------------------+

### Confusion Matrix for Logistic Regression With Class balancing 
![](/images/Confusion_Matrix.png)



# [Project 3 - Flight Fare Prediction : Project Overview](https://github.com/Rahul713713/Flight_Fare_Prediction)
![](/images/indigo.png)
- Created multiple charts,graphs,countplots,etc. in order to understand how price varies with different features.
- Worked on a dataset consisting of 10683 rows of data for 10 different features.
- Performed univariate analysis as well as multivariate analysis on various features to understand the importance of every feature.
- Performed data cleaning, data preprocessing and exploratory data analysis to understand the independent variables and prepare the data for modeling.
- Implemented multiple regression algorithms and came up an r square value of 0.85 with XGB.

# Problem Statement
Predict the ticket prices of flights based on multiple independent variables and machine learning algorithms.

The data that I have contains information such as Airline,Date_of_Journey,Source,Duration,etc. and I have to predict price of the tocket based on these features and machine learning.

# EDA
After cleaning the data,I started with EDA. These are some of the outcomes of EDA 

![](/images/Most_Used_Airlines.png)
![](/images/price_vs_airplanes.png)
### Feature Importance
![](/images/Feature_Importance.png)

# Result

    +-----------------------------------------------------------------------------------+
    | *** Model Summary *** [Performance Metric: R squared(Coefficient Of Determination)] |
    +--------------------------------+---------------+---------------+------------------+
    |           Model Name           |      MAE      |      RMSE     |    R squared     |
    +--------------------------------+---------------+---------------+------------------+
    |       Linear Regression        |    1927.93    |      2418     |       0.62       |
    |         Decision Tree          |    1328.57    |      2418     |       0.73       |
    |         Random forest          |    1183.04    |    2096.69    |       0.8        |
    |              XGB               |    1135.49    |    1820.25    |       0.85       |
    +--------------------------------+---------------+---------------+------------------+



# [Project 4 - Investment Management : Project Overview](https://github.com/Rahul713713/Investment-Management)
![](/images/Investment_Management.jpg)
- Created multiple charts,graphs,boxplots,etc. in order to understand the data and where the company should invest in order to avoid risks.
- Worked with 3 different datasets by merging them together.
- Cleaned the data in each datset and checked for missing values so that they can be merged together.
- Performed data analysis on the different datasets keeping in mind the two constraints provided by the company.

# Problem Statement
The problem involves a company which wants to make some investments in few companies to get profits.They are mostly focused on investing in young start-ups and small or mid-size companies. The head of the company wants to understand the world wide trends in investments so that the top managers can decide where they should invest to get good profits.

The company wants to invest in areas where most of the other investors are investing.Since,it's their first investment they want to play safe and avoid huge risks.The objective of this problem is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

# Observations
After cleaning the data,I started with EDA. These are some of the outcomes of EDA and the important results 

![](/images/Amount_raised_across_four_categories.png)
![](/images/Top_three_countries_for_investment.png)
![](/images/Amount_invested.png)

# Result
- The company should make a venture type investment.
- The top country in terms of the number of investments (and the total amount invested) is USA. 
- The top three countries for investemnt are USA,Great Britain and India.
- The sectors 'Others', 'Social, Finance, Analytics and Advertising' and 'Cleantech/Semiconductors' are the most heavily invested ones.

In case we don't want to consider 'Others' as a sector, 'News, Search and Messaging' is the next best sector

# Project Conclusion
The company should invest in one of these top three countries: USA,Great Britain and India. The type of investment should be venture and the major sectors for investment should be 'Others', 'Social, Finance, Analytics and Advertising' and 'Cleantech/Semiconductors'.



# [Project 5 - Forecasting Restaurant's Visitors : Project Overview](https://github.com/Rahul713713/Forecasting_Restaurant-s_Visitors)
![](/images/Restuarant.png)

# Problem Statement
We have to forecast the daily customers for four restaurants using the their previous records of daily customers. Our dataset considers daily visitors to four restaurants located in the United States Of America. The dataset also includes the holidays that falls between this time interval where we have to analyze the daily customers and forecast for the future. The dataset contains 478 days of restaurant data and an additional 39 days of holiday data for forecasting purposes. 

# Models Used For Forecasting
- SARIMA
- SARIMAX
                 
# Observations 
![](/images/ETS_decomposition.png)
![](/images/Forecast.png)
![](/images/Tableau_Forecasting.png)
