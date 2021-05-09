# FeatureSelectionTechniques

The techniques for feature selection in machine learning can be broadly classified into the following categories:

-- Supervised Techniques: These techniques can be used for labeled data, and are used to identify the relevant features for increasing the efficiency of supervised models like classification and regression.

-- Unsupervised Techniques: These techniques can be used for unlabeled data.

From a taxonomic point of view, these techniques are classified as under:

A. Filter methods
B. Wrapper methods
C. Embedded methods
D. Hybrid methods

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**A. Filter Methods:**
Filter methods pick up the intrinsic properties of the features measured via univariate statistics instead of cross-validation performance. These methods are faster and less computationally expensive than wrapper methods. When dealing with high-dimensional data, it is computationally cheaper to use filter methods.

- Information Gain: Information gain calculates the reduction in entropy from the transformation of a dataset.
- Chi2 Test: Used for categorical features in a dataset. We calculate Chi-square between each feature and the target and select the desired number of features.
- Fisher's Score: Widely used one....
- Correlation Coefficient:
- Variance Threshold:
- Mean Absolute Difference:
- Dispersion Ratio:


**B. Wrapper Methods:**
Wrappers require some method to search the space of all possible subsets of features, assessing their quality by learning and evaluating a classifier with that feature subset.

- Forward Feature Selection
- Backward Feature Selection
- Exhaustive Feature Selection
- Recurssive Feature Selection

https://www.analyticsvidhya.com/blog/2020/10/feature-selection-techniques-in-machine-learning/


**C. Embedded Methods:**
Embedded methods are iterative in the sense that takes care of each iteration of the model training process and carefully extracts those features which contribute the most to the training for a particular iteration.

- LASSO Regualization
- Random Forest Importance

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Dropping Constant Features:
  - Variance threshold removes all low variance features
  
2. With help of Correlation:
  - Find Independent and Dependent. If Dependent is closely related to the independent, don't remove
  - If 3 features are related to eachother, then take 1
  - If both features are related, take 1

3. Using Information Gain for Classification:

4. Using Information Gain for Regression:

5. ChiSquare test for Feature Selection:

6. Select KBest Algorithm:

7. Feature Importance with ExtraTreeClssifier: 
