# Board_Game_Review_Prediction
#Overview:
The "Board Game Review Prediction" project leverages supervised machine learning to predict user ratings for board games. The dataset, sourced from GitHub, contains information on various board games, including features such as the year of publication, player count, playing time, and more. The goal of the project is to build and compare two regression models, namely Linear Regression and Random Forest Regression, to accurately predict average user ratings for board games.

#Key Steps:

Data Collection:

Data was fetched from a GitHub repository, encompassing details about a wide range of board games.

Data Cleaning:

Rows with zero reviews and missing values were eliminated to ensure a reliable and meaningful dataset.

Data Exploration:

Initial exploration involved visualizing the distribution of average ratings through histograms.
A correlation matrix was created to understand relationships between different features.

Model Training:

The dataset was split into training (80%) and testing (20%) sets.
Linear Regression and Random Forest Regression models were trained using relevant features.

Model Evaluation:

Mean Squared Error (MSE) was employed as the evaluation metric for both models.

Comparison of Models:

Linear Regression and Random Forest Regression models were compared based on their MSE values.
Random Forest Regression exhibited superior predictive performance.

Single Test Prediction:

The models were tested on individual cases, providing predictions for a single board game and comparing them against the actual rating.
Eventhough Random Regression model gave a lower MSE, here Linear Regression model gave a closer value to the actual value.

#Conclusion:
"Board Game Review Prediction" project used machine learning to foresee user ratings. Comparing models, Random Forest Regression stood out for its superior predictions.This project lays the groundwork for enhanced predictive analytics in the world of gaming preferences.










