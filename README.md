Conclusion
It is clear that there are a few features have a greater influence on target variable. Using gridsearchcv, it is possible to make the the different models more accurate with more optimized hyper parameters KNN Classifier, Decisiontree Classifier and SVC show similar test and train acccuracy. However, the training time is the least with KNN and most with SVC.

Next steps / Recommendations
We would continue with fine tuning the study -

Cross-Validation: We could do K-Fold Cross-Validation by splitting the data into k subsets, training the models k times, each time using a different subset as the validation set and the remaining data as the training set.
Regularization - We could do L1 and L2 Regularization by adding regularization terms to the loss function to prevent overfitting. Dropout (for Neural Networks): Randomly drop units during training to prevent co-adaptation.
Early Stopping - We could monitor model performance on a validation set and stop training when performance starts to degrade.
Better Model Evaluation with different metrics - We could use Precision, Recall, F1 Score, AUC-ROC, AUC-PR, and Specificity instead of just Accuracy.
