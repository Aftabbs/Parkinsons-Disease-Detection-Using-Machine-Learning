# Parkinson's Disease Detection
This project aims to detect Parkinson's disease using the Parkinsons Dataset. The project was completed using Jupyter Notebook, and it consists of data preprocessing, scaling, and building two different models using Random Forest Classifier (RFC) and XGBoost Classifier (XGB) to compare their performance.

# Dataset Analysis
The Parkinsons Dataset was analyzed using various data exploration techniques in Jupyter Notebook, including:
- dtypes to get an overview of the data types of each column.
- Statistical summary to understand the distribution and range of each feature.
- Conversion of object datatype to float for preprocessing purposes.
- Data Preprocessing

# The dataset was preprocessed by scaling the data using the following techniques:
- StandardScaler for the RFC model.
- MinMaxScaler for the XGB model.

Train-Test Split
The dataset was split into training and testing sets using the train_test_split function from the scikit-learn library.

# Model Building
Two models were built to detect Parkinson's disease:

A Random Forest Classifier model was built using the scikit-learn library and achieved an accuracy of 84%.
Confusion matrix analysis and feature importance were performed on the RFC model using the scikit-learn and matplotlib libraries.

An XGB model was built using the xgboost library and achieved an accuracy score of 94%.

# The feature importance of both models were compared, and it was found that the three most significant features were:
* spread1
* MDVP:Shimmer(dB)
* PPE

# Industry Use Case
The Parkinson's disease detection model can be used by healthcare professionals and medical facilities to help diagnose Parkinson's disease in patients. It can also be used for screening and early detection of Parkinson's disease, leading to better treatment options and improved patient outcomes.

# Conclusion
In conclusion, the use of Jupyter Notebook allowed for efficient data exploration and model building. The XGB model performed better than the RFC model with an accuracy score of 94%. By comparing the feature importance of both models, it was found that the three most significant features for detecting Parkinson's disease were spread1, MDVP:Shimmer(dB), and PPE.









