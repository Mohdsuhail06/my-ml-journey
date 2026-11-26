# My ML Journey 🚀

I'm learning to become a **Machine Learning Engineer**, one small project at a time.
Every topic is learned from the main ML books (Géron, ISLP, ...) and ends with real projects on GitHub,
written from scratch first and then checked against scikit-learn.

## Foundations: Python, Git and data

| Project | What it does |
|---|---|
| [first-python-repo](https://github.com/Mohdsuhail06/first-python-repo) | Reads an expenses CSV and prints a summary (Git, GitHub, virtual environments) |
| [grocery-cleaning](https://github.com/Mohdsuhail06/grocery-cleaning) | Finds and fixes 6 problems in messy grocery data (pandas) |
| [cars-data-cleaning](https://github.com/Mohdsuhail06/cars-data-cleaning) | Cleans 10,921 real Jordan car listings and finds a hidden meaning in missing data |

## Part 1: Regression ✅

Predicting a number. All four projects use real Jordan used-car listings and are written from scratch in NumPy.

| Lesson | Project | What it does |
|---|---|---|
| 1.1 Simple linear regression | [linear-regression-from-scratch](https://github.com/Mohdsuhail06/linear-regression-from-scratch) | Car price from age: closed form + gradient descent, equal to scikit-learn |
| 1.2 Multiple linear regression | [price-predictor](https://github.com/Mohdsuhail06/price-predictor) | Price from age, mileage, fuel, gearbox and make: normal equation, one-hot, scaling; R² 0.19 → 0.31 |
| 1.3 Honest evaluation | [price-predictor / evaluate.py](https://github.com/Mohdsuhail06/price-predictor) | Hand-written cross-validation, a fixed cleaning rule, and a data-leakage experiment |
| 1.4 Overfitting, bias-variance | [overfitting-lab](https://github.com/Mohdsuhail06/overfitting-lab) | A degree-11 curve memorizes 12 cars (train error 0, test 57,349 JOD); degree chosen with CV and learning curves |
| 1.5 Regularization | [regularization-lab](https://github.com/Mohdsuhail06/regularization-lab) | Ridge, Lasso, Elastic Net from scratch: test error 57,349 → 8,909 JOD; Lasso keeps 16 of 768 columns |

## Part 2: Classification (next)

Predicting a category (yes / no, spam / not spam): logistic regression, metrics, k-NN, Naive Bayes, SVM.
Planned projects: `iris-baseline`, `churn-prediction`, `spam-filter`.

## The plan

1. Regression ✅ · 2. Classification · 3. Trees and ensembles · 4. Unsupervised learning ·
5. ML engineering (pipelines, tuning, SHAP) · 6. Deep learning (PyTorch) · 7. NLP and LLMs · 8. Deployment and MLOps
