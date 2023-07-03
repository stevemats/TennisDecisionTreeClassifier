## Play Tennis Data Classification

A decision tree classifier is an algorithm used in data mining for classification. It creates a tree-like model by selecting features to split the data, recursively dividing it into subsets, and assigning class labels based on majority voting or other criteria at the leaf nodes. It is interpretable but prone to overfitting.

Data Source => [data\playtennis.csv](data\playtennis.csv)

<i>For further practice feel free to play around with random [kaggle](https://www.kaggle.com/) data and replace it with the play tennis data. </i>

#### Classification output:

---

![decision_tree](https://github.com/stevemats/TennisDecisionTreeClassifier/assets/30528167/255ee492-67f9-4f6b-b343-c638d4e0ab76)

---

#### Modules used:

- <b>pandas</b>: For data manipulation & analysis, including reading our CSV file and performing one-hot encoding.
- <b>sklearn.model_selection</b>: For splitting the data into training and testing sets.
- <b>sklearn.tree.DecisionTreeClassifier</b>: For creating the decision tree classifier model.
- <b>sklearn.metrics.accuracy_score</b>: To calculate the accuracy of the classifier.
- <b>graphviz</b>: To visualize the decision tree for the playtennis data.
