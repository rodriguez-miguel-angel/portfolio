# portfolio

## Google Advanced Data Analytics Portfolio Project-06

### Project Title: TikTok Claims Classification Project. Machine Learning Model. 

### Project Overview
This project focuses on developing a machine learning model for claims classification at TikTok. The goal is to accurately predict whether a video contains a claim or an opinion, helping to streamline the review process of user reports.

### Business Understanding
TikTok receives a large number of user reports identifying videos and comments that need moderation. By implementing a predictive model, TikTok aims to streamline the review process and improve the overall user experience on the platform.

### Data Understanding
The data team at TikTok has gathered information on engagement levels to use as predictive features for the machine learning model. Tree-based models like random forest and XGBoost were chosen for their robustness and predictive power. Features such as video view count and share count were found to be highly predictive of whether a video contains a claim.

### Modeling and Evaluation
Two machine learning models were developed and cross-compared - random forest and XGBoost. The random forest model outperformed XGBoost in terms of f1-score, precision, and recall. The model successfully classified claims and opinions, providing accurate predictions for user submissions. The team recommends deploying this model to the operations team for predicting the status of user claims.

### Conclusion
The machine learning model created by the TikTok data team shows promising results in claims classification. The model's high predictive power and accuracy make it a valuable tool for the operations team to prioritize and address user reports effectively. By leveraging engagement data and advanced machine learning techniques, TikTok can enhance content moderation and user experience on the platform.
