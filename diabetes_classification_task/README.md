## 1. Logistic Regression Practice

- Notebook - [Diabetes_Model.ipynb](/diabetes_classification_task/Model.ipynb)<br/><br/>
- Dataset Used - [Diabetes Dataset from Kaggle](/diabetes_classification_task/diabetes.csv)<br/><br/>
- Libraries used -
    - Numpy
    - Pandas
    - Matplotlib
    - Sklearn
    - Seaborn
 <br/><br/>
- Cross Validation Accuracy Score: 0.81
- ROC AUC Score: 0.875 <br/><br/>
- Task List<br/><br/>
   1) [x] Import Libraries<br/><br/>
   2) [x] Dataframe basic visualization<br/><br/>
   3) [x] Check data for mean, standard deviation, minimnum and maximum values, Unique values and Value Count<br/><br/>
   4) [x] EDA (Exploratory data analysis)<br/><br/>
      1) [x] Heatmap using Seaborn to check for high multicollinearity between independent variables<br/><br/>![Seaborn_Heatmap](/diabetes_classification_task/assets/img/Heatmap.png)<br/><br/>
      2) [x] Histogram using Pandas to visualize data value range<br/><br/>![Histogram](/diabetes_classification_task/assets/img/Histogram.png)<br/><br/>
   5) [x] Check for null values in column and replace with median values to improve precision by lowering bias of model<br/><br/>
   6) [x] Define outlier threshold and replace with threshold values as outliers in the data cause problem during model fitting<br/><br/>
   7) [x] Encoded categorical features as a one-hot numeric array (no ordinal relationship exists b/w the categorical variables), this is needed for feeding categorical data to scikit-learn linear models<br/><br/>
   8) [x] Import the Sklearn libraries<br/>
      1) [x] sklearn.linear_model for LogisticRegression Model<br/>
      2) [x] sklearn.metrics for accuracy score, roc auc score, and confusion matrix<br/><br/>
   9) [x] Logistic Regression model made and fit to dataframe<br/><br/>
   10) [x] Cross validation and scores for accuracy, precision, recall and f1 calculated<br/><br/>
   11) [x] Sample weights updated to balanced to have better precisoon and lower chances of reporting false positives<br/><br/>
   12) [x] Confusion Matrix generated<br/><br/>![Confusion Matrix](/diabetes_classification_task/assets/img/Confusionmatrix.png)<br><br/>
   13) [x] ROC AUC Score calculated<br/><br/>
### Tasks Yet to be done:<br/><br/>
   15) [ ] ROC AUC curve generation
   16) [ ] More sample weight tuning
   17) [ ] Hyperparameter tuning
