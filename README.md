# vaccine_multi_label_classification
Project Description:
1. Converting each file to a pandas dataframe.
2. Dropped all columns that are not necessary for model performance.
3. As the remaining columns had medium to low amount of null values, used the column median to fill them.
4. Performed same methods of the testing features.
5. Used MinMaxScaler to normaliza data.
6. Made a dictionary with all necessary models and iterated through it while usinf accuracy as a metric to evaluate the models.
7. Decided upon random forest classifier.
8. Predicted probabilities for both labels and used the ROC AUC score for these labels.
9. Recieved a very suitable score.
10. Plotted necessary roc auc graphs.
11. Predicted probabilities for testing features, saved them and downloaded the csv file. 
