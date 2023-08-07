# TelecomChurnPrediction

Customer Churn Prediction at Telecom Interconnect

The project assigned to me as the final project of the bootcamp, the contents was involved by lessons from sprint 11 - 16.

In this particular sprint, I am endeavoring to synthesize and apply all the knowledge and insights I have learned throughout Sprints 11 to 16.

# **Project Insight**

Interconnect, a telecommunications provider, is eager to predict their customer churn rate. Should it become known that a customer intends to discontinue service, they will be interested to stay through the offer of promotional codes and exclusive package options. The marketing team at Interconnect has gathered various pieces of customer personal data, encompassing details regarding the data packages chosen and associated contracts.

Within the scope of this project, I endeavored to construct a predictive model employing gradient boosting algorithms, specifically Random Forest, Gradient Boosting, and CatBoost. I executed target data balancing by utilizing the upsampling method and implemented one-hot encoding. After executing several models, it was discerned that Random Forest, Gradient Boosting, and CatBoost attained a superior ROC-AUC score of 0.85, surpassing other models. In order to optimize the outcome, I deployed a Voting Classifier model to make the best result, founded on the highest score from the previous models. The concluding accuracy score remained consistent at 0.85, with the utilization of the 'soft' parameter within the voting process.

Customer churn is clearly bad for company profitability. There are various strategies that can be implemented to eliminate customer churn. The best way to avoid customer churn is to use KYC, this method need to be done so the company can get to know their customers better. It includes identify customers who are at risk of become churned, and for the company they need to increase their customers satisfaction. To improve customer service is, of course, a top priority to address this issue. Building customer loyalty through relevant experiences and customized services is an alternative strategy to reduce customer churn. Some companies have conducted surveys of customers churn to understand why they are no longer using the company's services in order to adopt a proactive approach to avoid future customer churn.
