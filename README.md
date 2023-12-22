**Team Members**:  Ananya Anand, Lyushen Song, Leonardo Trucios Cevasco, Mauro Wang


**Project Title**: Default Probability of Credit Card - Taiwan 2006


**Background**:  In the 1990s, there was an economic boom related to the development of real estate projects in Taiwan, which led to the creation of new banks to facilitate financing. After a saturation of the real estate sector, bank profits stagnated, which is why banks began to develop a business strategy related to the issuance of credit cards. To implement this strategy, financial institutions had to reduce the usual credit card requirements, which triggered a crisis in 2006, where total card debt reached USD 268 billion, affecting more than half a million of people.


**Problem Statement**: Nowadays, both banks and people are alert about the responsible management of credit cards. On the banks' side, maintaining adequate credit health is crucial to complying with the banking regulations established in their jurisdiction. Regarding individuals, maintaining appropriate financial behavior is essential to maintain stable financial health and avoid long-term negative consequences, such as: high interests or a decrease in the individual's credit score. The purpose of this project is to analyze demographic characteristics and financial behavior to project default probabilities. In relation to the financial behavior variables, we have information during the months of April 2005 until September 2005, as well as the result of the credit card default in October 2005. Our objective is to develop a Machine Learning model that allows classifying the non-payment outcome, based on the analysis of the individual's behavior during the last 6 months. Finally, with respect to the application of this project in business, we consider that the ability to predict the risk of default in time is decisive for banks to be able to take financial measures or develop contingency plans for clients prone to default.


**Data sourcing**: The group will make use of the 'Default of credit card clients' dataset in.csv format, which is a carefully curated and investigated dataset from the UC Irvine Machine Learning Repository. This dataset is also available on Kaggle. This dataset, which focuses on Taiwanese consumers with default payments, covers a monthly period from April 2005 to September 2005. Following the collection of data, a thorough preprocessing stage was carried out to guarantee the data's accuracy and consistency in format. The fact that this dataset hasn't changed since 2016 in order to preserve data consistency is notable. Strict compliance and data privacy guidelines were followed, and no personal user data was included. Additionally, there are no specific access requirements needed to view this dataset; it is available to the general public. https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset


**Description of dataset**: This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. The dataset includes 30,000 rows ; 25 columns and 25 different variables. The description of the variables in the dataset are as follows:
* X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
* X2: Gender (1 = male; 2 = female).
* X3: Education (1 = graduate school; 2 = university; 3 = high school; 0, 4, 5, 6 = others)
* X4: Marital status (1 = married; 2 = single; 3 = divorce; 0=others).
* X5: Age (in years).
* X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -2: No consumption; -1: Paid in full; 0: The use of revolving credit; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
* X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
* X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
* Y: client's behavior; Y=0 then not default, Y=1 then default


**Project Title**: Default Probability of Credit Card - Taiwan 2006
