# What is Machine Learning?
Machine learning is the field of study that gives computers the ability to learn without being explicitly being programmed to do so.

The spam filter is a good example. Given both examples of which are spam (by users marking emails that are spam) and which are ham (normal emails).
Which allows the spam filter program to learn how to differentiate which is which.

The examples that is used to train a model is called "training set" and each training example is called a "training instance" or sample.

## Types of Machine Learning Systems

**Supervised Learning**
In supervised learning the training set you feed to the algorithm includes the desired solutions called labels. 

Tasks:
1. supervised learning task is called <ins>classification</ins>. (example: which are spam, which are ham emails)
2. <ins>regression</ins> task -> used to predict a target numeric value, for example: the price of a car, given a set of features (mileage, age, brand, etc).

Both classification and regression models can be used interchangeably.

**Un-supervised Learning**
In unsupervised learning the training data is unlabled, which means the system tries to learn without a teacher. It finds connections between user's interactions with data,
and categorizes the users by themselves, this is called <ins>clustering</ins>.

Visualization algorithm are also good examples of unsupervised learning. You feed them alot of complex and unlabled data and they output a 2D or 3D representation of your data.

Tasks:
1. <ins>Dimensionality reduction</ins> in which the goal is to simplify the data without losing too much information.
One way to do this is to merge several correlated features into 1. Example, a car's mileage may be strongly correlated with it's age, so DR algorithm will merge them into 1 feature that represents the car's wear and tear. This is called <ins>feature extraction</ins>.

2. <ins>Anomaly Detection</ins>, example: detecting unusual credit card transactions to prevent fraud, catching manufacturing defects, or automatically removing outliers from a dataset before feeding it to another learning algoritm.

3. <ins>Novelty Detection</ins>, it aims to detect new instances that look different from all instances in the training set. The goal is to recognize data that lies outside the distribution of known training data but not necessarily mean the data is anomalous or incorrect. Example: A self-driving car encountering a new type of road sign.

4. <ins>Anomaly detection</ins> identifies data points that deviate significantly from the expected pattern or behavior. These deviations are often considered outliers or errors. Example: A fraudulent transaction in a banking system.

**Semi-supervised Learning**


**Self-supervised Learning**
