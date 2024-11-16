# CISIAS-cyber-attack-voting-classifier
 The CISIAS Cyber Attack Voting Classifier combines Random Forest, KNN, and Logistic Regression models using hard voting to enhance cyberattack detection. Each model contributes robust predictions, and the majority class is selected for the final decision, ensuring accurate and reliable threat classification.

# Key Components:
Random Forest:
A decision-tree-based classifier that creates multiple trees during training and aggregates their outputs to reduce overfitting and enhance robustness.

K-Nearest Neighbors (KNN):
A distance-based algorithm that classifies data points based on the majority class of their nearest neighbors, ensuring effective local decision-making.

Logistic Regression:
A probabilistic model that predicts attack classes using linear combinations of input features, contributing interpretability and precision to the ensemble.

Process:
Each model is trained individually on a preprocessed cybersecurity dataset containing labeled traffic data.
Their outputs are combined through hard voting, where the final class prediction is determined by the majority vote among the three classifiers.
