 Credit-Risk-Analysis-
 
   Jill requested data preperation, statisical reasoning and machine learning applied to a credit report. The Purpose of this analysis was determine the credit risk inbalance classifications using different techniques to train, evaluate loans which were to reflected the good verse riskyloans.
   It was advised to use credit dataset from a lending sevice company called LendingClub, to use various algorithms within the datasets to predict credit risk. Now, recomendation on if the predictive credit risk will be implemented within this evaluation.   
   
   Sample of the following data set:
   ![2022-11-22 13 27 43](https://user-images.githubusercontent.com/107796290/203392959-c16b1837-5ca0-4cf8-b90f-f66f7eaf256b.png)

   
   To begin the resampling  of the data training we will use the algorithms to resample the data to make presictions and evaulate the model's performances.  
   In reviewing the balance of our target values we have a low risk of 68,470 to the high rosk of 347. ![2022-11-22 13 30 08](https://user-images.githubusercontent.com/107796290/203393490-4050bc80-8360-43ab-83c5-cddc6e684270.png)

   * First, review and decribe the balance accuracy scores of y_test and y_predict which calculated 0.6571840065203901. 
   * Next, recorded the confusion_matrixto calculate an array:![2022-11-22 13 33 48](https://user-images.githubusercontent.com/107796290/203394005-f06395e9-76c3-4238-8948-89419a13d7af.png)
   * Another imbalanced classification report demosted the high-risk and low risk loans. 
  ![2022-11-22 13 36 01](https://user-images.githubusercontent.com/107796290/203394571-34cbe97b-3761-4931-bd8b-8ee067b72933.png)

  - According to the table:



SMOTE Oversampling provided a resample of the training data resulting low-risk 51366 and high risk the same, 51366.  
* After calculationg the blanced accuracy score 0.6619848637108801.
* The confusion-matric test and predict was ![2022-11-22 13 40 10](https://user-images.githubusercontent.com/107796290/203395190-b7b69331-fbca-4dc5-a3fe-0cc4fd5e23f2.png)

*Classification report imbalanced test and predict.
![2022-11-22 13 40 57](https://user-images.githubusercontent.com/107796290/203395425-32a81fea-baab-4b95-9b46-10844345f7bb.png)

Then this analysis was to tested and compared the performances of the algorithms to the undersampling algorithms performance by using the Centroids algorithm. The testing results below:
* Using the libraries to resample the data using the clustercentroids resampler to determoine the counter high-risk 246 and low rish result 246 the same. 
* Balanced accuracy score resulted in the oversampling was 0.5441784794709592.
* Confusion_matrix(y_test,y_pred) was 
*The imbalanced classification report was to compare the high-risk to low risk as you can set in the table.
![2022-11-22 13 49 43](https://user-images.githubusercontent.com/107796290/203397099-366e748b-c3be-433b-b9c2-81f073283c53.png)


OVER and UNDER COMBINATION SAMPLING:
The Over and Under Combination Sampling algorithms to determine the best performance compared to the other sampling in this analysis. TO do this count the class target as "counter" from the library and use the data resamped to train the logic regression model.

* In this resampling trained data with SMOTEEN Counter results for high-risk was 51361 and the low risk was 46653. 


* ![2022-11-22 13 56 31](https://user-images.githubusercontent.com/107796290/203398180-97ed5a48-c70c-41f7-9c25-2dedaaa937c7.png)
* Next calculate the balanced accuracy score was 0.6440876547898007 from the sklearn metrics. 
* 
* The confusion matrix results array implicated variations compared to the other algorithms.
* 
![2022-11-22 13 58 18](https://user-images.githubusercontent.com/107796290/203398525-8a41c199-cecd-4dd8-9975-05450c94dd4c.png)


Confusion matric from sklean mertics. 

The classification report from sklearn metrics 
