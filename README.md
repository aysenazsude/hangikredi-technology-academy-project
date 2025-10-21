# hangikredi-technologyschool

This project uses data analysis and machine learning to improve the performance of bank marketing campaigns. The primary challenges addressed are the lack of effective customer targeting (Segmentation) and the inability to forecast campaign outcomes (Success Prediction).

The project proposes a two-stage strategic approach:

Customer Segmentation: Grouping customers based on similar characteristics.

Success Prediction: Building a model to predict the success of future campaigns based on these segments and historical data.

# Dataset Used
The analysis was conducted on a dataset from a Portuguese bank's direct marketing campaigns (conducted via phone calls). The classification goal is to predict whether a customer will subscribe to a term deposit (the 'y' variable).


# Methodology
Exploratory Data Analysis (EDA):

Statistical relationships between customer attributes (e.g., job, marital status, balance, loan status) and the campaign outcome ('y') were examined.


Chi-square and T-tests were used for this analysis.

Customer Segmentation (Step 5):

The K-Means algorithm was used to group customers.


Data was preprocessed using OneHotEncoder for categorical data and StandardScaler for numerical data.

The analysis resulted in 4 distinct customer clusters (segments).

The clusters were visualized in 2D using PCA (Principal Component Analysis).

Campaign Success Prediction (Step 6):

A predictive model was built using customer demographics, previous campaign data, and the newly created 'cluster' feature.

A Random Forest Classifier was chosen for the model.

The model achieved approximately 91% accuracy in predicting campaign success.


# Conclusion
This project demonstrates that an integrated approach of customer segmentation and success prediction can create a strong, data-driven foundation for marketing strategies. This method allows for more targeted and personalized campaigns, which can significantly increase success rates and improve customer engagement.
