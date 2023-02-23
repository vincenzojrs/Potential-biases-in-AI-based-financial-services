# Ethics in AI: Potential biases in AI-based financial services

Alberto Danese, Head of Data Science at Nexi Italy and Kaggle Grandmaster, challenged us to identify bias in the data collected by a financial institution on users who have applied for a mortgage. "application_train.csv" of the [Home Credit Default Risk Kaggle competition](https://www.kaggle.com/competitions/home-credit-default-risk/data) was used as reference dataset.

The predictive variables in the dataset concerned biographical, social, and economic information about the users, while the target variable shows the propensity of a user to repay her debt.

### Main findings:
* According to the xgboost model, the relevant variables mostly come from third-party sources, over which the bank has no control.
* It is therefore confirmed that eliminating all ethical variables causes a slight decrease in AUC which is not as significant as expected.
* Our framework raises the trade-off between bank interests and users' eligibility for mortgages. 

More at [PDF + jupyter notebook](https://github.com/vincenzojrs/Potential-biases-in-AI-based-financial-services/raw/main/Potential%20biases%20in%20AI-based%20financial%20services.pdf)

### Team:
* Fabiana Caccavale - *ML Specialist*
* Matteo Gioia - *Ethics Specialist*
* Martina Manno - *ML Specialist*
* Vincenzo J. Striano - *ML Specialist and Team Leader*
* Antonio Marco Vita - *Analyst*
