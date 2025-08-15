#########  for dataset email at vishallaxmi77@gmail.com   or call at +91 8604970105 or at +91 9214110226



###############################  FOR PROJECT1  ########################################

this is a housing price prediction modelling for regression problem i taken  typicall and most sufficient steps for this project i have started from data loading then preprocessing till upto model evaluation all the way through eda etc.
this project has given me an idead of how the flow must be and how to approach the problems of machine learning.
it was quite easy to do since i have the prior theoritical knowledge and have hands on practice of python and machine learning related coding.

############################## FOR PROJECT2  ###########################################
Summary
This notebook demonstrates a typical machine learning workflow, starting from data loading and ending with model evaluation.

Data Loading and Initial Inspection: We began by loading the dataset from 'Week3_GA_dataset.csv' into a pandas DataFrame and inspected its structure and initial rows to understand the data types and identify potential issues like missing values.

Handling Missing Values: We addressed the missing values represented by '?' in columns 'V1' and 'V2' by replacing them with NaN (Not a Number) and then imputing these missing values with the median of their respective columns.

Data Type Conversion: The columns 'V1' and 'V2' were converted from object type to numeric to prepare them for model training.

Categorical Feature Encoding: The categorical column 'V5' was transformed using one-hot encoding to convert it into a numerical format suitable for the machine learning model.

Target Variable Encoding: The 'Target' column, which is the variable we want to predict, was encoded into numerical labels (0 and 1) using Label Encoding.

Data Splitting: The dataset was split into training and testing sets to train the model on a portion of the data and evaluate its performance on unseen data.

Model Training: A Logistic Regression model was chosen and trained on the prepared training data.

Model Evaluation: Finally, the trained model was evaluated on the test set using metrics such as accuracy and a classification report to understand its performance, particularly its ability to predict the target variable. The evaluation revealed a higher recall for class 0 compared to class 1, suggesting the model is better at identifying instances of class 0.


################################### project3  ###############################################

Missing values in 'Age', 'InGamePurchases', 'Location', and 'GameDifficulty' were handled using median and mode imputation.
The model for predicting EngagementLevel achieved an accuracy of 0.883 and performed well across all engagement levels (High, Low, Medium), with F1-scores between 0.86 and 0.90.
The model for predicting InGamePurchases had an accuracy of 0.8135 but completely failed to predict the positive class (players who made purchases), with precision, recall, and F1-score all being 0.0 for this class.
K-Means clustering segmented players into 4 distinct groups. Cluster 0 showed a notably higher average for InGamePurchases.
The model for predicting GameDifficulty achieved an accuracy of 0.5265 but struggled to predict 'Hard' and 'Medium' difficulties effectively, performing well only for 'Easy'.
Applying SMOTE to address class imbalance in the InGamePurchases prediction model improved the model's ability to predict the minority class, although recall and precision for the minority class remained relatively low.
A RandomForestClassifier model built to predict GameDifficulty achieved an overall accuracy of approximately 52.65% but struggled to predict "Hard" and "Medium" difficulties effectively due to class imbalance, showing a strong bias towards predicting "Easy" difficulty.
An initial attempt at churn prediction based on low sessions or playtime showed near-perfect accuracy but was identified as potential data leakage. A redefined churn definition and subsequent modeling attempts, even with SMOTE, failed to effectively predict the churn class (class 1), indicating severe class imbalance and the model's inability to identify these instances.
A genre recommendation system was successfully developed using cosine similarity based on preprocessed player features, providing sample genre recommendations for players based on the preferences of similar players.
Player segments (clusters) were successfully leveraged to develop targeted marketing strategies and personalized in-game experience recommendations for each cluster, demonstrating how distinct player group characteristics can inform business decisions.
