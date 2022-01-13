# Heart Failure Dataset - Insights & Classification

This project aims to find a good classification algorithm and data insights to predict future heart failure. 
The data is taken from [here](https://www.kaggle.com/fedesoriano/heart-failure-prediction) and contains 918 samples. The dataset includes for each sample 11 features, such as age, sex, maximal heart rate, etc., and the last column indicating heart failure or not.

I first study the data [here](https://github.com/anatlevari/HeartFailureClassification/blob/main/Heart%20Failure%20Insights.ipynb) to obtain insights and preparations for the classification task.
In [here](https://github.com/anatlevari/HeartFailureClassification/blob/main/Heart%20Failure%20-%20Classification.ipynb), I compared six classification algorithms to find the one best predicts heart failure based on the features.  

### Conclusion
The maximal accuracy was achieved by a random forest classifier and is equal to 94.44%. Thus, this classifier may be a good fit for future heart failure detection.

### Future Steps
* Investigate overfitting in decision tree classifier.
* Use the decision tree classification model for describing the most significant features that predict heart failure.
* Compare the classification models using metrics other than accuracy, e.g., precision and recall. 


