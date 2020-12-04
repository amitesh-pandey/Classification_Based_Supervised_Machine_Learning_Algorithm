"# Classification_Based_Supervised_Machine_Learning_Algorithm" 
.
This repository provides the practical implementation of classification based supervised Learning Algorithm which are listed below:<br/>
•	Decision Tree <br/>
•	KNN <br/>
•	Naive Bayes <br/>
•	Random Forest <br/>
•	Support Vector Machine <br/>

Considering a dataset, which talks about the age of the customer with their estimated salary as an input independent variable & purchased as an output dependent variable. We need to create a working model to assist the owner of SUV showroom car, which predicts whether the following customer will purchase the Brand-new SUV car or not. Since it is a classification-based problem statement, we need to apply all the classification-based algorithm mentioned above and compare it in order to find the algorithm which best fits the model with the highest accuracy level. <br/>

We have compared the accuracy level using the confusion matrix techniques : <br/>

Let us understand how confusion matrix works, considering the results obtained from the SVM algorithm:<br/>

The confusion matrix :     [[66  2] 
                            [ 8 24]] <br/>
Where <br/>
65 indicating the prediction made in 65 number of people purchasing SUV is correct.<br/>
24 indicating the prediction made in 24 people not purchasing SUV is correct.<br/>
3 indicating the prediction made in 3 people not purchasing the SUV is wrong.<br/>
8 indicating the prediction made in 8 people purchasing the SUV is wrong.<br/>
Thus the accuracy level in SVM is found to have  0.9 = 90%. <br/>

Based on the comparision table mentioned below : <br/>

SR NO 	Classification Algorithm 	Accuracy level <br/>
1	      SVM 	                    0.9 = 90% <br/>
2	      Random Forest 	        0.91 = 91% <br/>
3	      Decision Tree	            0.91 = 91%<br/>
4	      Naive Bayes	            0.9 = 90% <br/>
5	      KNN	                    0.93 = 93% <br/>

We found that the KNN algorithm best fits the models. 
