# AIML-Task5
# Decision Trees and Random Forest for Classification

This project investigates the use of tree-based machine learning models—Decision Trees and Random Forests—for classification problems using a structured data set, for example, the heart disease data set. The primary aim is to train these models, plot their decision process, examine overfitting, interpret the importance of features, and gauge their performance using cross-validation.

First, the dataset is read in and investigated to know its form and look for missing values. Features and target variables are then divided, and data is split into training and test sets for enabling unbiased assessment.

A Decision Tree Classifier is trained on the training data, and its structure is represented using Graphviz, which gives a good intuitive sense of how decisions are being made at each node. The accuracy of the model and classification report on the test set give an idea about its predictive performance. To overcome possible overfitting, a second Decision Tree with restricted depth is trained and tested, illustrating how controlling tree complexity can enhance generalization.

Finally, a Random Forest Classifier, which is an ensemble of multiple decision trees, is trained. This model generally provides better accuracy and resilience by eliminating variance. Its performance is compared with the Decision Tree models using the same metrics.

Feature importance scores derived from the Random Forest identify the variables that most impact the model's prediction, supporting interpretability and feature selection. Lastly, 5-fold cross-validation is used to evaluate the stability and generalization capability of the model over various data splits.

This project delivers an end-to-end workflow for employing tree-based models in classification tasks, with a focus on visualization, overfitting prevention, feature interpretation, and robust testing. It is best suited for binary classification problems but can be used for other datasets by modifying the input data path. Hyperparameters such as tree depth and number of estimators should be tuned by users to maximize model performance.

In general, this project illustrates how Random Forest and Decision Trees can be successfully used in solving real-life classification issues, with both strong predictive power and interpretability.
