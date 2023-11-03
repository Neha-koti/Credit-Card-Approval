# Credit Card Approval
 Project on Credit Card Approval
A top focus for the bank has always been acquiring new credit card customers. In this project, 1549 bank customer records were taken. Four robust machine learning models were constructed to assess the creditworthiness of each customer, providing valuable insights into whether a credit card should be approved for them. This project aims to enhance decision-making processes in the financial industry while mitigating risks associated with credit card approvals.

Tools Required: MySQL, Python, PowerBI 

Using Python packages like NumPy, Pandas we do data cleaning for the given dataset first. We deal with all wrong data, missing and null values in data cleaning. Then this cleaned data is loaded into MySQL and we try to get few useful insights from various queries. Later, we transform the data such that it is suitable for ML models. This transformed data is splitted into two parts: training dataset, testing dataset. We train Machine Learning model using training dataset. After training the model we give testing dataset to the model. ML model predicts the output as covid-19 positive or negative based on its learning from training dataset (which contains various symptoms). We calculate few metrics like Accuracy, precision etc to know the ML model performance. We develop 4 ML models namely: Logistic Regression, Decision tree, SVM, and Gradient Boosting  models/Algorithms. Lastly, we compare these four models to know which ML model works best and gives better prediction results.

Features name: (Credit_Card.csv)

Ind_ID: Client ID

Gender: Gender information

Car_owner: Having car or not

Propert_owner: Having property or not

Children: Count of children

Annual_income: Annual income

Type_Income: Income type

Education: Education level

Marital_status: Marital_status

Housing_type: Living style

Birthday_count: Use backward count from current day (0), -1 means yesterday.

Employed_days: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.

Mobile_phone: Any mobile phone

Work_phone: Any work phone

Phone: Any phone number

EMAIL_ID: Any email ID

Type_Occupation: Occupation

Family_Members: Family size


Another data set (Credit_card_label.csv) contains two key pieces of information

ID: The joining key between application data and credit status data, same is Ind_ID

Label: 0 is application approved and 1 is application rejected. 


Files Description:
 ### 1. credit_card.csv,credit_card_label.csv: 
These are csv files which contains 1549 bank customer records. It is out dataset. This Dataset was provided by odin School, Hyderabad,India.

### 2. credit_card.ipynb :
It is a jupyter file which contains python code for EDA, Data cleaning, Data Transformation and ML model generation code.

### 3. Credit card Approval.pdf 
It is a pdf file which contains complete documentation about the project.



