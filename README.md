# Flight-Delay-Prediction-Using-SAS-Ent-Miner

1. Objective: To develop prediction models and predict using Decision Tree, Neural Network, Auto Neural, SVM, Naïve Bayes, Logistic Regression and Random Forest based on previous flight and weather data in the United States.

2. Data:
. Flight Operation Data: https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time
. Weather Data: https://mesonet.agron.iastate.edu/request/download.phtml

3. Tools
. SQL Server
. SAS Enterprise Miner
. R

4. Algorithm
. Decision Tree
. Neural Network
. Auto Neural
. SVM
. Naive Bayes
. Logistic Regression
. Random Forest

5. Strategy

Both flight operation and weather dataset were combined using SQL server management studio. Data exploration was done using both SAS enterprise miner and Tableau followed by data cleaning, binning, transformation and normalization. Next, the cleaned data was randomised and split into 8:2 ratio (training: score) using R. The training data was used to build predictive models using algorithm in SAS Enterprise Miner. 10 fold cross validation was selected as model evalutaion technique in training. The best performing model was tested with score data to predict the outcome. Evaluation on the result was based on a few measuring criteria such as accuracy, precision, sensitivity, specificity, recall rate, misclassification rate and computational time. 
