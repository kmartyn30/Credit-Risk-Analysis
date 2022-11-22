 Credit-Risk-Analysis-
 
   Jill requested data preperation, statisical reasoning and machine learning applied to a credit report. The Purpose of this analysis was determine the credit risk inbalance classifications using different techniques to train, evaluate loans which were to reflected the good verse riskyloans.
   It was advised to use credit dataset from a lending sevice company called LendingClub, to use various algorithms within the datasets to predict credit risk. Now, recomendation on if the predictive credit risk will be implemented within this evaluation.   
   
Part one of this analysis was based on the credit risk of resampling with several algorithms.   Sample of the following data set:
   ![2022-11-22 13 27 43](https://user-images.githubusercontent.com/107796290/203392959-c16b1837-5ca0-4cf8-b90f-f66f7eaf256b.png)
   
   To begin the resampling  of the data training we will use the algorithms to resample the data to make presictions and evaulate the model's performances.
   
   In reviewing the balance of our target values we have a low risk of 68,470 to the high rosk of 347. 
   ![2022-11-22 14 10 03](https://user-images.githubusercontent.com/107796290/203401123-cf8ccf5f-b896-4d00-9b00-3ae16873b5b0.png)
   
 OVERSAMPLING:
This anaylsis, was a naive random oversampling algorithm to compare two oversamples algorithms to determine the performance. In doing so we will count the target class using the "counters" from the library. 
  
  *The naive random oversampling was resampling training data with the naive random oversampling algorithm result counter low risk 51366 and high risk same resample 51366. 
  
  ![2022-11-22 14 14 30](https://user-images.githubusercontent.com/107796290/203402123-7ae49377-2cb2-4eab-bd48-ae1a90758eaf.png)

* Another review and decribe the balance accuracy scores of y_test and y_predict which calculated 0.6571840065203901. 
 
 * Next, recorded the confusion_matrix to calculate an array:
  ![image](https://user-images.githubusercontent.com/107796290/203402614-6845fd59-c6e0-494e-850a-8571838e197e.png)

   * Another imbalanced classification report demosted the high-risk and low risk loans. 
  ![2022-11-22 13 36 01](https://user-images.githubusercontent.com/107796290/203394571-34cbe97b-3761-4931-bd8b-8ee067b72933.png)

  - According to the table:



**SMOTE** 
The SMOTEENN algorithm was used to predict credit risk. The datasets were using with imbalance-lean and scikit-learn libraries with oversampling and undersampling with the algorithm to determine the results from a combinational approach. The steps that were taken were use the SMOTEENN algorithm resample the data, utilize the counters to view the target classes, train regression classifier, calculated the balanced accuracy score and confusion matrix. 


Oversampling provided a resample of the training data resulting low-risk 51366 and high risk the same, 51366.  
![2022-11-22 14 20 37](https://user-images.githubusercontent.com/107796290/203402948-a8f380b7-1879-4b70-a695-a8649f0cb7b9.png)

* After calculationg the balanced accuracy score 0.6619848637108801.

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

* Next calculate the balanced accuracy score was 0.6440876547898007 from the sklearn metrics. 
 
* The confusion matrix results array implicated variations compared to the other algorithms. Confusion matric from sklean mertics. 
![2022-11-22 14 30 11](https://user-images.githubusercontent.com/107796290/203404484-4a995b65-e33f-4f63-a9f8-aabbe83ca8b3.png)

The imbalanced classification report from sklearn metrics. 
![2022-11-22 14 31 11](https://user-images.githubusercontent.com/107796290/203404661-42e76f21-20dc-4b24-a12c-b6b5bc9ed02a.png)
