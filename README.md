 Credit-Risk-Analysis-
 
  Jill requested data preparation, statistical reasoning, and machine learning applied to a credit report. The Purpose of this analysis was to determine the credit risk imbalance classifications using different techniques to train and evaluate loans that reflected good verse risky loans. The machine learning data points are assigned based on the interval parameters of the algorithm. The data model will query, decide, and apply the fit, model, and predict. It advised using a credit dataset from a lending service company, LendingClub, to use various algorithms within the datasets to predict credit risk. Now, the recommendation on if the predictive credit risk implements within this evaluation.
The credit risk analysis base on two parts: credit risk ensemble and resampling credit risk for this analysis. Each data set is required to read the CSV and perform data cleaning on the Leading club data set.
PART I:
Part one of this analysis based on the credit risk of resampling with several algorithms. Sample of the following data set:
 
![2022-11-22 13 27 43](https://user-images.githubusercontent.com/107796290/203392959-c16b1837-5ca0-4cf8-b90f-f66f7eaf256b.png)
   
To begin the resampling of the data training we will use the algorithms to resample the data to make presictions and evaulate the model's performances.
   
In reviewing the balance of our target values we have a low risk of 68,470 to the high risk of 347. 
![2022-11-22 14 10 03](https://user-images.githubusercontent.com/107796290/203401123-cf8ccf5f-b896-4d00-9b00-3ae16873b5b0.png)
   
 OVERSAMPLING:
This anaylsis, was a naive random oversampling algorithm to compare two oversamples algorithms to determine the performance. In doing so we will count the target class using the "counters" from the library. 
  
 *The naive random oversampling was resampling training data with the naive random oversampling algorithm result counter low risk 51366 and high risk same resample 51366.   
![image](https://user-images.githubusercontent.com/107796290/203409713-2aac84e9-4da6-4352-a066-2c4220489f18.png)

* Another review and describe the balance accuracy scores of y_test and y_predict which calculated 0.6571840065203901. From the predicting values within the test set against the model. The y_tests the outcome from the original data set. The accuract score is a 65 percentange of the model correct at the time.
 
* Next, recorded the confusion_matrix to calculate an array:
![image](https://user-images.githubusercontent.com/107796290/203402614-6845fd59-c6e0-494e-850a-8571838e197e.png)

* Another imbalanced classification report showed the high-risk and low risk loans. 
![2022-11-22 13 36 01](https://user-images.githubusercontent.com/107796290/203394571-34cbe97b-3761-4931-bd8b-8ee067b72933.png)

  - According to the table the imblanced classifiction report breaks down the precision, recall, F1 support for credit risk. In order to predict and validate the model. The SVM model cis to predict the data set. The F1 average/total implicated is low high- risk 0.01 and low- risk is moderate 0.57. 


**SMOTE** 
The SMOTEENN algorithm was used to predict credit risk. The datasets were using with imbalance-lean and scikit-learn libraries with oversampling and undersampling with the algorithm to determine the results from a combinational approach. The steps that were taken were use the SMOTEENN algorithm resample the data, utilize the counters to view the target classes, train regression classifier, calculated the balanced accuracy score and confusion matrix. 


Oversampling provided a resample of the training data resulting low-risk 51366 and high risk the same, 51366.  
![2022-11-22 14 20 37](https://user-images.githubusercontent.com/107796290/203402948-a8f380b7-1879-4b70-a695-a8649f0cb7b9.png)

* After calculationg the balanced accuracy score 0.6619848637108801. From the predicting values within the test set against the model. The y_tests the outcome from the original data set. The accuract score is a 66 percentange of the model correct at the time. Close to the above model Navie Random oversampling of 65%.

* The confusion-matric test and predict: 
 ![2022-11-22 14 21 34](https://user-images.githubusercontent.com/107796290/203403054-9eef61ea-df79-403f-9b89-a73e014ffc9f.png)

*Classification report imbalances test and predict.
![2022-11-22 14 22 41](https://user-images.githubusercontent.com/107796290/203403246-e61b4923-6d50-48fd-a3dd-a455820f216c.png)

**UNDERSAMPLING algorithm:**
Then this analysis was to tested and compared the performances of the algorithms to the undersampling algorithms performance by using the Centroids algorithm. The testing results below:

![2022-11-22 14 26 15](https://user-images.githubusercontent.com/107796290/203403929-b7548719-8cad-4529-b526-c3b74c9a0fc9.png)

* Using the libraries to resample the data using the** **clustercentroids**** resampler to determine the counter high-risk 246 and low rish result 246 the same. 
![2022-11-22 14 28 04](https://user-images.githubusercontent.com/107796290/203404163-6d6b5ac7-f9fd-4fc9-beb8-ec72daee2c11.png)

* Balanced accuracy score resulted in the oversampling was 0.5441784794709592.

* Confusion_matrix:
![2022-11-22 14 27 27](https://user-images.githubusercontent.com/107796290/203404089-15ae40ec-f656-4750-8019-c3ad09f1b58e.png)
 
*The imbalanced classification report was to compare the high-risk to low risk as you can set in the table.
![2022-11-22 14 28 41](https://user-images.githubusercontent.com/107796290/203404251-c53f0e43-5f14-41b4-8f14-457706ebc83a.png)

OVER and UNDER COMBINATION SAMPLING:
The Over and Under Combination Sampling algorithms to determine the best performance compared to the other sampling in this analysis. TO do this count the class target as "counter" from the library and use the data resamped to train the logic regression model.

* In this resampling trained data with SMOTEEN Counter results for high-risk was 51361 and the low risk was 46653. 
![2022-11-22 14 29 22](https://user-images.githubusercontent.com/107796290/203404371-460a7c94-489e-447d-bf85-cabdef649b0d.png)

* Next calculate the balanced accuracy score was 0.6440876547898007 from the sklearn metrics. From the predicting values within the test set against the model. The y_tests the outcome from the original data set. The accuract score is a 64 percentange of the model correct at the time. In a close range to the two algorithm tests above respectively. 
 
* The confusion matrix results array implicated variations compared to the other algorithms. Confusion matric from sklean mertics. 
![2022-11-22 14 30 11](https://user-images.githubusercontent.com/107796290/203404484-4a995b65-e33f-4f63-a9f8-aabbe83ca8b3.png)

The imbalanced classification report from sklearn metrics. 
![2022-11-22 14 31 11](https://user-images.githubusercontent.com/107796290/203404661-42e76f21-20dc-4b24-a12c-b6b5bc9ed02a.png)


PART 2:

The loan credit risk sample is below as a sample to the dataset extracted. 

![image](https://user-images.githubusercontent.com/107796290/203407370-e9997744-633e-4dfe-b3cc-dbb92113c7a5.png)

Then the data was split into training and testing on loan status as our target.  


![2022-11-22 14 48 54](https://user-images.githubusercontent.com/107796290/203407771-9512ad0b-aa6b-45a9-82b7-7b0fe443394b.png)

Then the blance of our target values of the low-risk were 68,470 and high-risk 347. 
![image](https://user-images.githubusercontent.com/107796290/203408054-83c4ecb5-1a4e-4965-89b1-c7f0dd02bab2.png)


BALANCED RANDOM FOREST CLASSIFIER 
As we resample the train data with Balanced Random Forest Classifier first to fit the train data then calculate the balanced accuracy score 0.7885466545953005. From the predicting values within the test set against the model. The y_tests the outcome from the original data set. The accuracy score is a 79 percentange of the model correct at the time. A higher rate than all the above models. Although the accuracy score is not always an appropriate performance metric. 

Then use the confusion matrix: 
![2022-11-22 15 08 27](https://user-images.githubusercontent.com/107796290/203411279-9ad1b213-2cbf-4411-a17d-844250a4031e.png)

The table represents the imbalanced classification report:
![2022-11-22 15 09 01](https://user-images.githubusercontent.com/107796290/203411375-0f983ad3-dd0c-4c71-b07b-0933bb2f806d.png)


**EASY ENSEMBLE ADABOOST CLASSIFIER**
In addition the Easy Ensemble AdaBoost Classifier algorithm, in a jupyter environment to test and predict credit reports for the loans. 

The balanced accuracy score was 0.925427358175101.

Confusion matrix array results:
![2022-11-22 15 12 31](https://user-images.githubusercontent.com/107796290/203411973-f08a1d70-f902-4e80-a082-efa94053f88b.png)

The imbalanced classification report shown below:

![image](https://user-images.githubusercontent.com/107796290/203412227-d74d3dfa-3b58-4db6-b13f-da0913bda518.png)
