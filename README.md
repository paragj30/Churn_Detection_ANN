# Churn_Detection_ANN

## Problem Statement:

ABC Bank, a reputable Indian bank, is an offline-online institution that provides the full range of financial services to customer categories including mid sized & large corporations, retail businesses, MSME, and agricultural.

The bank wants to forecast whether a customer would leave based on their demographics and attributes because we all know that acquiring new customers is more expensive than keeping the ones you already have.

We'll examine customer behavior, identify individuals who may leave, and forecast who will do so first. According to our client, it costs more money and is a lot difficult to achieve new customers than it does to keep the ones they already have.

To better understand the client's issue and expectations, our domain experts and data analysts met with them at the Axis Bank corporate office.

To better understand the client's issue and aspirations, our data analysts and subject experts met with them at the Axis Bank headquarters. So they simply requested the client for the required information.

The client wants us to desing a ML pipeline that can forecast which clients will leave the business. Estimating whether or not consumers leave a bank is the goal.

so that the client may create customer retention campaigns and loyalty programs to keep as many consumers as feasible.

Data Set Story:

It has 12 variables and 10,000 observations.

Information about clients is contained in independent variables.

Customer desertion is referred to as a dependent variable.

RowNumber— has no bearing on the output and relates to the record (row) number. has no impact on a consumer leaving the bank and contains random values.

Surname: A customer's choice to leave a bank is unaffected by their surname.

CreditScore—since a customer having a better credit score is less likely to churn the bank, it may have an impact on customer churn.

Geographical location may have an impact on a customer's choice to quit the bank.

Gender: It's intriguing to checks whether a customer's gender influences their choice to leave the bank.

Age—this factor is unquestionably important because older clients are less likely than younger ones to abandon their bank.

tenure: refers to the length of time that a customer has been a bank client. Typically, elder customers are more dependable and less likely to abandon a bank.

Balance: Another excellent predictor of customer churn, since customers with higher account balances are less likely to leave their bank than those with lower balances.

Number of Products: refers to the total number of goods a customer has acquired from the bank.

hasCrCard: Whether a consumer has a credit card is shown by the hasCrCard function. This column is also pertinent because cardholders are less likely to leave the bank.

IsActiveMember: Returning consumers who are active are less likely to do so

EstimatedSalary: Just like with balance, individuals with lesser salary have a higher propensity to quit the bank.

Exited—whether or not the customer left the bank. (0 = No, 1 = Yes)

Our Approach:

The only way the bank might possibly profit from this analysis, if we strive to comprehend the business issue at hand, is if we accurately identify the clients who are most likely to leave the bank.

Instead of maximizing the accuracy score and roc auc score for this, we should concentrate on raising the recall score.

We can only achieve the intended outcome by increasing the True Positives and minimizing the False Negatives because the dataset is unbalanced.
