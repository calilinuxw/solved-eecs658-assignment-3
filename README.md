Download Link: https://assignmentchef.com/product/solved-eecs658-assignment-3
<br>
Deliverables:

<ol>

 <li>Copy of Rubric3.docx with your name and ID filled out (do not submit a PDF)</li>

 <li>Python source code for CompareMLModelsV2</li>

 <li>Screen print showing the successful execution of CompareMLModelsV2 4. Answers to the following questions for CompareMLModelsV2:

  <ol>

   <li>Based on accuracy which model is the best one?</li>

   <li>For each of the 11 other models, explain why you think it does not perform as well as the best one.</li>

  </ol></li>

 <li>Python source code for dbn.py</li>

 <li>Screen print showing the successful execution of dbn.py 7. Answers to the following questions about dbn.py:

  <ol>

   <li>Does the program use k-fold cross-validation?</li>

   <li>What percentage of the data set was used to train the DBN model?</li>

   <li>How many samples are in the test set?</li>

   <li>How many samples are in the training set?</li>

   <li>How many features are in test set?</li>

   <li>How many features are in the training set?</li>

   <li>How many classes are there?</li>

   <li>List the classes.</li>

  </ol></li>

</ol>




Assignment:

<ul>

 <li>This assignment has two parts:</li>

 <li>Part 1: Expand our comparison ML classifiers to include SVM, Decision Tree, Random Forest, ExtraTrees, and Neural Network.

  <ul>

   <li>Enhance your CompareMLModels program and call it</li>

  </ul></li>

</ul>

CompareMLModelsV2 so that it includes the SVM, Decision Tree, Random Forest, ExtraTrees, and Neural Network.

<ul>

 <li>It should now do the following:</li>

 <li>Uses 2-fold cross-validation to produce a test set of 150 samples of the iris data set with the following ML models:</li>

</ul>

<ul>

 <li>Naïve Baysian (NBClassifier)</li>

 <li>Linear regression (LinearRegression)</li>

 <li>Polynomial of degree 2 regression (LinearRegression)</li>

 <li>Polynomial of degree 3 regression (LinearRegression)</li>

 <li>kNN (KNeighborsClassifier)</li>

 <li>LDA (LinearDiscriminantAnalysis)</li>

 <li>QDA (QuadraticDiscriminantAnalysis)</li>

 <li>SVM (svm.LinearSVC)</li>

 <li>Decision Tree (DecisionTreeClassifier)</li>

 <li>Random Forest (RandomForestClassifier)</li>

 <li>ExtraTrees (ExtraTreesClassifier)</li>

 <li>NN (neural_network.MLPClassifier)</li>

 <li>For each of the 12 models the program should display (with a label before each model’s display indicating which model the results are for):

  <ul>

   <li>Confusion matrix</li>

   <li>Accuracy metric</li>

  </ul></li>

 <li>If the values in your confusion matrices do not add up to 150, then you did something wrong.</li>

 <li>Part 2: Implement the deep learning DBN example at:

  <ul>

   <li><a href="https://github.com/albertbup/deep-belief-network/blob/master/README.md">https://github.com/albertbup/deep-belief</a><a href="https://github.com/albertbup/deep-belief-network/blob/master/README.md">network/blob/master/README.md</a></li>

   <li>Name the program dbn.py</li>

   <li>The code has two imports from SupervisedDBNClassification. Use the one “from dbn import SupervisedDBNClassification” and comment out the other one. Note: The sample code uses “from dbn.tensorflow import SupervisedDBNClassification” and has “from dbn import SupervisedDBNClassification” commented out.</li>

   <li>More details regarding the program can be found at:</li>

  </ul></li>

</ul>

<a href="https://medium.com/analytics-army/deep-belief-networks-an-introduction-1d52bb867a25">https://medium.com/analytics-army/deep-belief-networks-an-introduction</a><a href="https://medium.com/analytics-army/deep-belief-networks-an-introduction-1d52bb867a25">1d52bb867a25</a>




Remember:

<ul>

 <li>Your Programming Assignments are individual-effort.</li>

 <li>You can brainstorm with other students and help them work through problems in their programs, but everyone should have their own unique assignment programs.</li>

</ul>