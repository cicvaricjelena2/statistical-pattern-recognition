Statistical Pattern Recognition

Project Overview

This project explores statistical pattern recognition and classification techniques through the implementation of Bayesian decision theory, statistical hypothesis testing, and linear classification algorithms.

The project consists of two main parts, focusing on probabilistic classification of Gaussian-distributed data and the design of linear classifiers for multiclass classification problems.

The main objective is to understand how statistical properties of data, decision criteria, and classifier parameters influence classification performance and decision boundaries.

Part 1: Bayesian Classification and Hypothesis Testing

This part focuses on the classification of two-dimensional data generated from bimodal Gaussian probability distributions.

Each class is modeled as a mixture of two multivariate Gaussian distributions with different means, covariance matrices, and mixing probabilities.

1. Data Generation and Distribution Analysis

* Generation of two bimodal Gaussian classes.
* Sampling of 500 observations per class.
* Visualization of generated samples.
* Calculation and visualization of theoretical probability density functions.
* Comparison of theoretical distributions with empirical histograms.

2. Bayesian Minimum Error Classifier

A Bayesian classifier based on the minimum probability of classification error is implemented.

The classification decision is determined by comparing posterior probabilities of the two classes.

The analysis includes:

* Bayesian decision rule.
* Discriminant function calculation.
* Decision boundary visualization.
* Experimental and theoretical classification error estimation.

3. Bayesian Minimum Risk Classifier

A minimum risk classifier is developed by introducing different costs for classification decisions.

The objective is to penalize certain classification errors more heavily than others.

The influence of decision costs on the classification threshold and decision boundary is investigated.

4. Neyman-Pearson Classifier

The Neyman-Pearson approach is implemented to control one type of classification error while minimizing the other.

The analysis includes:

* Likelihood ratio testing.
* Decision threshold selection.
* Numerical estimation of classification errors.
* Visualization of decision regions.

5. Wald Sequential Probability Ratio Test

A sequential classification approach is implemented, where observations are evaluated one at a time until sufficient statistical evidence is obtained to make a decision.

The analysis investigates:

* Sequential likelihood ratio calculation.
* Upper and lower decision thresholds.
* Type I and Type II error probabilities.
* Average number of observations required for classification.
* Relationship between classification reliability and sampling requirements.

Part 2: Linear Classification Methods

The second part investigates linear classification techniques using three synthetic two-dimensional classes.

The objective is to design linear decision boundaries and analyze their classification performance.

1. Synthetic Data Generation

* Generation of three classes with Gaussian distributions.
* Definition of class means and covariance matrices.
* Visualization of generated samples.
* Analysis of class distributions and separability.

2. Linear Classifier Using the Resubstitution Method

A linear classifier is implemented using the resubstitution approach.

The method involves:

* Estimation of class mean vectors.
* Calculation of covariance matrices.
* Optimization of the projection direction.
* Selection of the decision threshold.
* Construction of linear decision boundaries.

3. Multiclass Classification

The pairwise classification approach is applied to distinguish between three classes.

Classification results are evaluated using a confusion matrix and graphical representation of decision regions.

4. Desired Output Method

A second linear classification approach is implemented using a desired output matrix.

The classifier parameters are estimated by solving a system based on the training samples and desired output values.

The influence of different desired output values on the resulting classifier parameters and decision boundaries is also investigated.

Technologies & Libraries

* Python
* NumPy
* SciPy
* Matplotlib
* Scikit-learn
* Seaborn
* Scikit-image
* Jupyter Notebook

Repository Structure

statistical-pattern-recognition/
│
├── README.md
├── Drugi_domaci.ipynb
├── Treci_zadatak.ipynb
├── requirements.txt
└── .gitignore

How to Run

1. Clone the repository:

git clone https://github.com/cicvaricjelena2/statistical-pattern-recognition.git

2. Navigate to the project directory:

cd statistical-pattern-recognition

3. Install the required dependencies:

pip install -r requirements.txt

4. Launch Jupyter Notebook:

jupyter notebook

5. Open either notebook and execute the cells.

Key Takeaways

This project demonstrates the application of statistical decision theory and linear classification methods to pattern recognition problems.

It explores the relationship between probability distributions, classification criteria, decision costs, and classification boundaries.

The experiments provide practical insight into Bayesian decision-making, hypothesis testing, sequential classification, and linear classifier design.

Author

Jelena Cicvarić

Electrical Engineering | Machine Learning | Data Science

GitHub Profile
