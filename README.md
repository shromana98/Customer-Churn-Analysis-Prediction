# Customer-Churn-Analysis-Prediction
# 🎯Objective: " 📊Customer Churn Analysis and Prediction🤖💡"

Churn prediction means detecting which customers are likely to cancel a subscription to a service based on how they use the service. 
It is important to know many businesses because acquiring new clients often costs more than retaining existing ones.

# 🎯 The main objectives:

1. Finding the % of Churn Customers and customers that keep in with the active services.
2. Analysing the data in terms of various features responsible for customer Churn
3. Finding a most suited machine learning model for correct classification.

# 🔍 Data Cleaning:

* Telecom Churn Dataset(Source: Kaggle).
* Dealt with the null values, duplicates, data type of columns.

 # 📊 Exploratory Data Analysis (EDA) :

1. Univariate Analysis: In univariate analysis I get the unique labels of categorical features, as well as get the range & density plots

2. Bivariate Analysis: In bivariate analysis I checked the features relationship with target variable.

3. Multivariate Analysis: In multivariate analysis I checked the relationship between two variable with respect to the target variable.

# 💡 Insights:
 i) 1869 of customer have left about 26.5 percentage from overall.
ii) Loss around $2862927 due to customer churn.
iii) Customers with monthly contract are more likely to churn
iv) Several customers choose the Fiber optic service and customers who use Fiber optic have high churn rate,
this might suggest a dissatisfaction with this type of internet service
4. Correlation
5. Checked Outliers in the dataset

# 🔍 Data Pre-Processing:

1. Checked Missing Value
2. Used Encoding for Categorical Features
3. Scaled the data with the help of Standard scalar

# 🤖 Model Training and Evaluation:

- The data is imbalance, so balanced the data with the help of SMOTEENN
- Leveraging various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, Gradient Boosting, Adaboosting , Voting Classifier etc
   I built predictive models to forecast customer churn.

# ⚙️ Hyperparameter Tuning:

* Used Randomized SearchCV to improve performance of model and get the best hyperparameters for the model 

# 💡 Model Evaluation:

Adaboost Classifier well performed on training data with accuracy 80% and the test score is 81% after applying Hyperparameter tuning score is 84%.

# 🚀 Conclusions: 
Once we can identify those customers that are at risk of cancelling, we would know exactly what marketing action to take for each individual customer to maximize the chances that the customer will remain
