Feature Scaling
We discussed previously that the scale of the features is an important consideration when 
building machine learning models. Briefly:

Feature magnitude matters because:
The regression coefficients of linear models are directly influenced by the scale of the variable.
Variables with bigger magnitude / larger value range dominate over those with smaller magnitude / 
value range
Gradient descent converges faster when features are on similar scales
Feature scaling helps decrease the time to find support vectors for SVMs
Euclidean distances are sensitive to feature magnitude.
Some algorithms, like PCA require the features to be centered at 0.
The machine learning models affected by the feature scale are:
Linear and Logistic Regression
Neural Networks
Support Vector Machines
KNN
K-means clustering
Linear Discriminant Analysis (LDA)
Principal Component Analysis (PCA)
Feature Scaling
Feature scaling refers to the methods or techniques used to normalize the range of independent 
variables in our data, or in other words, the methods to set the feature value range within a 
similar scale. Feature scaling is generally the last step in the data preprocessing pipeline, 
performed just before training the machine learning algorithms.

There are several Feature Scaling techniques, which we will discuss throughout this section:

Standardisation
Mean normalisation
Scaling to minimum and maximum values - MinMaxScaling
Scaling to maximum value - MaxAbsScaling
Scaling to quantiles and median - RobustScaling
Normalization to vector unit length
