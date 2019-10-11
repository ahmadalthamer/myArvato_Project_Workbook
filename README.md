# Bertelsmann Arvato Project
Arvato Financial Solutions provides credit management solutions in all segments of the customer lifecycle: ID, fraud and credit risk management, payment, Financing Services and Debt Collection Services. Our purpose is to help the company predict which person will be a potential customer
### Installations:
In addition of Anaconda distribution. you need to install the following pagckages using pip --install command
Installations
1. [progressbar](https://pypi.org/project/progressbar/)
2. [XGBRegressor](https://xgboost.readthedocs.io/en/latest/python/python_api.html)

### Summary:

Phases of the project:

1. **Customer Segmentation Report** - This analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. This used unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core
customer base of the company. 

2. **Supervised Learning Model** -This used the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

3. **Kaggle Competition** - This used the chosen model to make predictions on the campaign data as part of a Kaggle Competition and see how it measures up to the other fellow students.

### Data Files
Data are confidential
1. `azdias.csv` - Demographics data for the general population of Germany - 891,211 persons (rows) x 366 features (columns)

2. `customers.csv` - Demographics data for customers of a mail-order company - 191,652 persons (rows) x 369 features (columns)

3. `mailout_train.csv` - Demographics data for individuals who were targets of a marketing campaign (train) - 42,982 persons (rows) x 367 (columns)

4. `mailout_test.csv` - Demographics data for individuals who were targets of a marketing campaign (test) - 42,833 persons (rows) x 366 (columns)

5. `feat_info.csv` - Contains a summary of properties for each demographics data column created by the user - 366 features (rows) x 4 (columns)

### Acknowledgments

I would like to thank [Udacity](https://eu.udacity.com/) for this journey, and [Arvato](https://www.arvato.com/)  for providing the data.
