# Salifort User Churn

### Project Overview

  The goal of this project is to increase overall growth by preventing monthly user churn on the Waze app. Churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. 
  The ultimate goal for this project is to develop a machine learning model (Random Forest, XGBoost) that predicts user churn.
  
  
### Business Understanding

  The Waze data team is currently developing a data analytics project aimed at increasing overall growth by preventing monthly user churn on the Waze app. 

### Data Understanding

  This project uses a dataset called waze_dataset.csv.The dataset contains: 14,999 rows and 12 columns – each row represents one unique user.

  
### Modelling and Evaluation
  
  To obtain a model with the highest predictive power, we developed two different models to cross-compare results: random forest and XGBoost.
  The below chart shows the most influential variables.

  <img width="428" alt="image" src="https://github.com/aliMohamed-Z/Predict-user-churn/assets/75675790/3abd3380-fa25-403b-ae9d-94fa3f33b309">

  
### Conclusion

  This modeling effort confirms that the current data is insufficient to consistently predict churn. It would be helpful to have drive-level information for each user (such as drive times, geographic locations, etc.). It would probably also be helpful to have more granular data to know how users interact with the app.
