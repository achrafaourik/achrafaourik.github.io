## Selected projects in data science and machine learning

---
### Churn detection project
Conducted extensive analysis on real-world data of Taiwan's leading music streaming platform.
In this project, I performed all of the steps in a machine learning worfklow: <b>data cleaning, exploratory data analysis,
feature engineering, modeling (supervised and clustering) and model evaluation.</b>
I was able to create a highly accurate classification model that is able to accurately <b>predict which clients are more likely to churn.</b>

A select few of the EDA performed comparing the two profiles or churners and loyal subscribers:
<img src="assets/auto_renew.png?raw=true" />
<img src="assets/registration_method.png?raw=true" />

I have also performed clustering on the listening behavior of clients:
<img src="assets/clusters_centroids.png?raw=true" />
<img src="assets/pca_kmeans.png?raw=true" />

The evolution of performance after every iteration of improvement:
<img src="assets/evolution_iterations.png?raw=true" />

The features importance of the final XGBoost model:
<img src="assets/xgb_feat_importance.png?raw=true" />

---
### Financial Helper Bot
Chatbot that is capable of creating bank accounts, checking their balance and performing transactions on these accounts. It is also capable of doing other non-financial related tasks such as answering FAQ questions and chitchat with users.

The architecture of the project is illustrated below:
<img src="assets/graph_docker.png?raw=true" />

A demonstration of how the bot works is shown below:
<img src="assets/financial_bot.gif?raw=true" />