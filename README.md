# CMSC422 - Introduction to Machine Learning

Welcome to my repository for ```CMSC422 - Introduction to Machine Learning``` at the ```University of Maryland, College Park```. This repository includes a summary and the grade received for the homeworks and projects that I completed throughout this course. Due to university policies, the code for these projects is not publicly available. If you are an employer or have a legitimate request to view the code, please contact me directly.

## Assignments 

### Project 1: **Classification**
**Description:**  
- Implemented several core machine learning classification algorithms completely from scratch in Python.
- Built **baseline classifiers** (e.g., always predict majority class, first-feature rule) to understand evaluation and accuracy computation.
- Designed a **Decision Tree classifier** with configurable maximum depth, implementing recursive training, prediction, and visualization of learned trees.
- Developed a **K-Nearest Neighbors (KNN) classifier** and **epsilon-ball classifier**, including support for hyperparameter tuning and dimensionality reduction experiments.
- Implemented a **Perceptron classifier**, training it on multiple datasets (e.g., sentiment analysis, digit classification) and visualizing decision boundaries in low dimensions.
- Conducted **empirical analysis** through training/test accuracy evaluation, learning curves, hyperparameter curves, and dimensionality reduction studies.
- Strengthened understanding of **bias-variance tradeoff**, **overfitting vs. underfitting**, and **generalization performance**.

**Grade:** 94.5/100
- Question 2 had minor errors in the code
- Incorrectly described the difference for WU5

--- 

### Project 2: **Multiclass and Linear Models**  
**Description:**
- Implemented multiclass reductions (One-vs-All, All-vs-All) and a tree-based multiclass reduction for a text-based wine classification task (datasets: WineData, WineDataSmall). Includes code and examples to train depth-limited decision trees, inspect learned trees, and compare against simple baselines.
- Implemented a generic gradient descent optimizer in `gd.py` (adaptive step size, trajectory tracking) and used it for optimizing linear models.
- Implemented a generic linear classifier framework in `linear.py` with an L2 regularizer and a pluggable loss interface. `SquaredLoss` is provided; `LogisticLoss` and `HingeLoss` are implemented/used to compare performance on toy 2D datasets and the binary wine task (WineDataBinary). Experiments include evaluating accuracy and inspecting top-ranked features (words) for interpretability.

**Grade:** 100/100

---

### Project 3: **PCA, Softmax Regression and NN**
**Description:**
- Implemented end-to-end dimensionality reduction, multiclass linear classification, and a fully-connected neural network from scratch in Python.
- PCA (`dr.py`): implemented `pca(X,K)` to center data, compute the sample covariance, perform eigen-decomposition, sort eigenpairs, and return projected data (`P`), projection matrix (`Z`), and eigenvalues (`evals`). Used for visualizing eigendigits and variance-explained experiments.
- Softmax regression (`softmax.py`): implemented a numerically-stable softmax classifier with vectorized cost and gradient computations, trained using `scipy.optimize.minimize` (L-BFGS-B). Implemented `cost`, `train`, and `predict` to classify MNIST digits.
- Neural network (`nn.py`): implemented a configurable fully-connected NN (ReLU/Linear activations), forward/backprop, squared-loss and its gradient, and SGD with momentum for parameter updates. Included helper utilities for batching, one-hot encoding, and MNIST loading in `utils.py`.
- 
**Grade:** 

---

### Project 4: ****  
**Description:**  


**Grade:**

---

### Project 5: ****
**Description:**


**Grade:**


---

## Disclaimer

**## CONTACT ME IF YOU WOULD LIKE TO SEE THE CODE, UNDER UNIVERSITY RULES I AM NOT ALLOWED TO POST PUBLICLY ON HERE**

If you are interested in reviewing the code or have any questions related to the projects, please reach out to me directly.
