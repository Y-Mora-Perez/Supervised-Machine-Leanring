# Supervised-Machine-Leanring

### Summary And Analysis for Challenge

**Precision, recall scores, and accuracy score**

  - Oversampling
  
The precision is very low at .010 for data class which is a high risk and the prescison is very high at .997 for high data class which is a low risk. Recalls are high for high_risk loans that is 0.75 and low for low_risk loans 0.61. Accuracy score is 0.650. The f1 score is .02.
  
  - Smote Oversampling
  
The precision is very low at .011 for data class which is a high risk and the prescison is very high at .997 for high data class which is a low risk. Recalls are high for high_risk loans that is 0.63 and low for low_risk loans 0.69. Accuracy score is 0.662. The f1 score is .02.

  - Undersampling
  
 Original: Counter({'low_risk': 51366, 'high_risk': 246}), After Undersampling Counter({'high_risk': 246, 'low_risk': 246}).
 
 
 The precision is very low at .006 for data class which is a high risk and the prescison is very high at .995 for high data class which is a low risk. Recalls are high for high_risk loans that is 0.68 and low for low_risk loans 0.41. Accuracy score is 0.547. The f1 score is .01
 
  
  - Combination Sampling


 The precision is very low at .009 for data class which is a high risk and the prescison is very high at .997 for high data class which is a low risk. Recalls are high for high_risk loans that is 0.72 and low for low_risk loans 0.57. Accuracy score is 0.547. The f1 score is .02.
 


**Summary**

By looking at the summary for all sampling techniques you can see that they are all pretty similar to one another. But
undersampling is worst as its accuracy score is just 0.547 and f1 score 0.01 and smote oversampling is the best as its accuracy scoore is .662 but the f1 score is still just .02. Even though smote oversampling has the best accuracy i would have choosen to use oversampling because it has recalls of 0.75 for high_risk loans and 0.61 for low_risk loans, remember that low values of precision shows that there will be high number of false positive.
