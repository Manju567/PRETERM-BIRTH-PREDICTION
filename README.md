# Preterm Birth Prediction of Pregnant Women in Post Conization Period Using Machine Learning Techniques
# Abstract
Pregnant women who underwent excisional surgeries (conization) for cervical intraepithelial neoplasia (CIN) display high risks of preterm birth. It is crucial to predict the risks of preterm birth amongst women in their post conization periods as this has severe consequences in terms of the cost as well as the health of the mother and the baby. This paper presents a preterm birth prediction system using machine learning approaches which will allow to evaluate the risk of a preterm birth. The dataset used in this work consisted of longitudinal cervical length (CL) of different gestational periods from 725 pregnant women undergoing surveillance programs in three clinics at London University Hospitals. Several machine learning algorithms were applied to make the prediction. Model based on decision tree achieved the highest accuracy (99.3%) on the test dataset.
 # WHAT IS PRETERM BIRTH?
 
A baby born without completing a full 40 weeks of gestation period (born before 37 weeks) is considered to be premature baby and the term of the delivery is called preterm birth.
The severity of preterm birth depends on how early the delivery occurs.
According to World Health Organization approximately 15 million preterm deliveries happen every year. About 1 million babies die due to the consequences of preterm birth.

# EFFECTS OF CONIZATION SURGERY ON PRETERM BIRTH
Women who have been diagnosed with Cervical Intra epithelial Neoplasia (a pre- cancerous condition) undergo conization surgeries. These conization procedures leave a negative impact on a woman's pregnancy and greatly increases the risk of preterm birth.
As a result, pregnant women who underwent excisional surgeries (conization) for cervical intraepithelial neoplasia (CIN) display high risks of preterm birth.
Therefore, it is crucial to predict the risks of preterm birth amongst women in their post conization periods. We applied machine learning approaches to correctly predict preterm birth delivery of women in their post conization.
# RELATED WORK


# Nam et. al

conducted studies of Korean patients who had cervical conization and delivered singleton infants. Their observation included type of excisional surgery performed and second trimester cervical length at different gestational periods.

 # Kindinger et. al

supervised a retrospective analysis in clinics that specializes in caring pregnant women of post conization phase. Their research discovered that the risk of preterm birth can be reduced with a targeted cervical cerclage.
# Crane et. al
conducted a prospective cohort study in a healthcare center which included women undergone surgical treatments for CIN such as CKC, LEEP, or cryotherapy earlier and with singleton pregnancies. Based on their research, LEEP and CKC lead to spontaneous preterm delivery. A cutoff of <3.0 cm was found the best for predicting spontaneous preterm delivery in LEEP.
 # METHADOLOGY
 ![PRETERM-2](https://github.com/Manju567/PRETERM-BIRTH-PREDICTION/assets/116549275/c984d45e-8bd6-45c3-b7b5-69a2aecf1f34)


 # PROCESSING
 
**Data Acquisition:**                                                            

**Dataset Details
Data Preprocessing:
Preprocess predictor attributes •Preprocess class attributes
Scaling (Min-Max)
Source: Dryad
Instance: 730, Features: 7 Missing Values: Yes
Data Type: Nominal,
Numerical
Class Imbalance Issue: 613 Term/71 Preterm; SMOTE

  # Features
   age
   ethnicity
   cervical length during weeks
   13-15
   e cervical length during weeks 16-18
 Train set: 80%
 cervical length during weeks 20-22
 gestation at spontaneous
 delivery
 cerclage


# Data Preprocessing:

Preprocess predictor attributes
Preprocess class attributes
Scaling (Min-Max)
Class Imbalance Issue: 613 Term / 71 Preterm; SMOTE

# Split Dataset:**

Train set: 80%
Test set: 20%
# CLASSIFIERS USED AND HYPER-PARAMETER TUNING

ZERO-R
LOGISTIC REGRESSION
NAIVE BAYES
SUPPORT VECTOR MACHINE
K-NEAREST NEIGHBOR
DECISION TREE
10-fold cross validation was done on each of the classifiers. Hyper-parameters were tuned accordingly to achieve the best results.

 # Equations of the performance metrics used:

False Positive Rate = FP / TN+FP
Precision =TP / TP+FP
Precision = TP / TP+FP
Recall = TP / TP+FN
F1-Measure = 2 x recall x precision / precision + recall

 # CLASSIFIERS USED AND HYPER-PARAMETER TUNING
 
 ![PRETERM-3](https://github.com/Manju567/PRETERM-BIRTH-PREDICTION/assets/116549275/272093c2-58c2-4e32-9365-8b6e1d6d9cc8)


# RESULT

![PRETERM RESULT](https://github.com/Manju567/PRETERM-BIRTH-PREDICTION/assets/116549275/63947ccf-141e-4ef9-86bc-3d180c829235)

# CONCLUSION

The acquired dataset was trained with six machine learning algorithms (including that of Decision Tree, KNN, Logistic Regression, SVM, Naive Bayes, and ZeroR)

Our experiments have found Decision Tree algorithm attaining the best accuracy score with 99.3% accuracy on the test data.

In future, we intend to use explainable Al techniques to better comprehend the models' prediction.


