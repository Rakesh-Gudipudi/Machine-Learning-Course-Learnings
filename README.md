# Rakesh-Gudipudi-Machine-Learning-Course-Learnings
1. Generate a simulated two-class data set with 100 observations and two
features in which there is a visible but non-linear separation between the two classes.
Show that in this setting, a support vector machine with polynomial kernel (with degree
greater than 1) or a radial kernel will outperform a support vector classifier on the
training data. Which technique performs best on the test data? Make plots and report
training and test error rates in order to back up your assertions.

2. Use ‘Heart’ dataset. Remove if there is example with missing data. Split into
70-30 train test data. Fit Support Vector Classifier (Linear SVM) to the training data.
Report training set and test set accuracy. Change value of C and plot training and test
set accuracy with varied values of C. Provide your insights on the effect of changing C on
training and test set accuracy. Experiment with other Kernels and report your findings
about accuracy on Test data.

3. Use the UCI car repository dataset.
(http://archive.ics.uci.edu/ml/datasets/Car+Evaluation)
a) Apply Decision Tree, Bagging and Random Forest with 50 trees and with a maximum
depth of five for each tree. Report the accuracies for each method. You can use builtin
classifier. Mention what criteria you used.
b) Show how the accuracy changes along with the increase of number of trees in a plot.
c) Show variable importance in a plot in terms of decrease of your used criteria and
express relative to the maximum.
