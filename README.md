### Telecom Churn Prediction <br>

#### Problem Statement <br>

Business Problem Overview
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this project, you will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

### Dataset Feature Description
The Dataset contains the following columns:
||Column Name|Description|
|:--|:--|:--|
||**CustomerID**| Passenger Identity |
||**Gender	Whether**| Whether the customer is a male or a female |
||**SeniorCitizen**| Whether the customer is a senior citizen or not (1, 0) |
||**Partner	Whether**| the customer has a partner or not (Yes, No) |
||**Dependents**| Whether the customer has dependents or not (Yes, No)|
||**Tenure**| Number of months the customer has stayed with the company |
||**PhoneService**| Whether the customer has a phone service or not (Yes, No) |
||**MultipleLines**| Whether the customer has multiple lines or not (Yes, No, No phone service) |
||**InternetService**| Customer’s internet service provider (DSL, Fiber optic, No)|
||**OnlineSecurity**| Whether the customer has online security or not (Yes, No, No internet service)|
||**OnlineBackup**| Whether the customer has online backup or not (Yes, No, No internet service)|
||**DeviceProtection**| Whether the customer has device protection or not (Yes, No, No internet service)|
||**TechSupport**| Whether the customer has tech support or not (Yes, No, No internet service) |
||**StreamingTV**| Whether the customer has streaming TV or not (Yes, No, No internet service)|
||**StreamingMovies**| Whether the customer has streaming movies or not (Yes, No, No internet service) |
||**Contract**| The contract term of the customer (Month-to-month, One year, Two year)|
||**PaperlessBilling**| Whether the customer has paperless billing or not (Yes, No)|
||**PaymentMethod**| The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))|
||**MonthlyCharges**| The amount charged to the customer monthly|
||**TotalCharges**| The total amount charged to the customer|
||**Churn**| Whether the customer churned or not (Yes or No)|

The solution code is divided into the following sections:

Data understanding

Preprocessing

EDA

Handle missing values

Feature Engineering

#### Models Used
Logistic Regression <br>
Decision Tree<br>
RandomForest<br>
Randomized Search Cv - Random Forest
