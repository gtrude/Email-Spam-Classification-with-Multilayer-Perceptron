# Email-Spam-Classification-with-Multilayer-Perceptron

This project focuses on classifying emails as spam or non-spam using the MultilayerPerceptronClassifier in SparkML. Key points:

Algorithm: Utilizing Multilayer Perceptron Neural Networks for binary classification.
Data Structure: The dataset has 30 columns, including an 'Email No.' index, 'Spam' label (1 for spam, 0 for non-spam), and 28 word occurrence features.
Featurization: Preprocessing involves defining 'features' and 'label' columns, along with proper array layer definition.
Classifier Configuration: Utilizing the MultilayerPerceptronClassifier with layers=[a, 14, 4, b], where 'a' is input variables and 'b' is output options.
Accuracy Evaluation: Calculating accuracy after applying the classifier on the featurized data.
Explore the code for a comprehensive understanding of the email spam classification process with SparkML.
