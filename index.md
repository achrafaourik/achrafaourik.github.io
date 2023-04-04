## Selected projects in data science and machine learning

---
### Churn detection project
Conducted extensive analysis on real-world data of Taiwan's leading music streaming platform.
In this project, I performed all of the steps in a machine learning worfklow: <b>data cleaning, exploratory data analysis,
feature engineering, modeling (supervised and clustering) and model evaluation.</b>
I was able to create a highly accurate classification model that is able to accurately <b>predict which clients are more likely to churn.</b>

<b>Some select graphs of the EDA performed comparing the two profiles or churners and loyal subscribers:</b>

Distribution of churn data relative to "auto_renew":
<img src="assets/auto_renew.png?raw=true" class="center" width="500" height="300">
Distribution of churn data relative to "registration_method":
<img src="assets/registration_method.png?raw=true" class="center" width="500" height="300"/>

<b>Clusters centroids generated after performing clustering:</b>
<img src="assets/clusters_centroids.png?raw=true" class="center" width="500" height="300"/>

<b>2D Visualization of the clusters using PCA:</b>
<img src="assets/pca_kmeans.png?raw=true" class="center" width="500" height="300"/>

<b>The evolution of performance after every iteration:</b>
<img src="assets/evolution_iterations.png?raw=true" class="center" width="500" height="300"/>

<b>The Feature Importance of the final XGBoost model:</b>
<img src="assets/xgb_feat_importance.png?raw=true" class="center" width="500" height="300"/>

[View code on Github](https://github.com/achrafaourik/Churn-Prediction)

---
### Financial Helper Bot
A chatbot that is capable of creating bank accounts, checking their balance and performing transactions on these accounts. It is also capable of doing other non-financial related tasks such as answering FAQ questions and chitchat with users.

The architecture of the project is illustrated below:
<img src="assets/graph_docker.jpg?raw=true" class="center" width="500" height="300"/>

A demonstration of how the bot works is shown below:
<img src="assets/financial_bot.gif?raw=true" class="center" />

[View code on Github](https://github.com/achrafaourik/chatbot_rasa)