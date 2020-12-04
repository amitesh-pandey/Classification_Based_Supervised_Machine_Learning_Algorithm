"# Classification_Based_Supervised_Machine_Learning_Algorithm" 

This repository provides the practical implementation of classification based supervised Learning Algorithm which are listed below:
•	Decision Tree
•	KNN
•	Naive Bayes
•	Random Forest 
•	Support Vector Machine 

Considering a dataset, which talks about the age of the customer with their estimated salary as an input independent variable & purchased as an output dependent variable. We need to create a working model to assist the owner of SUV showroom car, which predicts whether the following customer will purchase the Brand-new SUV car or not. 

Since it is a classification-based problem statement, we need to apply all the classification-based algorithm mentioned above and compare it in order to find the algorithm which best fits the model with the highest accuracy level. 

We have compared the accuracy level using the confusion matrix techniques : 

Let us understand how confusion matrix works, considering the results obtained from the SVM algorithm:

The confusion matrix :     [[65  3]
                            [ 8 24]]
Where 
65 indicating the prediction made in 65 number of people purchasing SUV is correct.
24 indicating the prediction made in 24 people not purchasing SUV is correct
3 indicating the prediction made in 3 people not purchasing the SUV is wrong 
8 indicating the prediction made in 8 people purchasing the SUV is wrong 
Thus the accuracy level in SVM is found to have  0.9 = 90% 

Based on the comparision table mentioned below : 

SR NO 	Classification Algorithm 	Accuracy level 
1	      SVM 	                    0.9 = 90%
2	      Random Forest 	          0.91 = 91%
3	      Decision Tree	            0.91 = 91%
4	      Naive Bayes	              0.9 = 90%
5	      KNN	                      0.93 = 93%

We found that the KNN algorithm best fits the models. 
