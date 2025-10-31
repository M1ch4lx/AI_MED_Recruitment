# Recruitment Task – Classification of a Heart with Hypertrophic Cardiomyopathy (Cardiomegaly)

## Solution file

All code with brief description is inside ```cardiomegaly.ipynb``` notebook file.

## Setup python evnironment

All needed libraries are listed in requirements.txt file.

You can also use uv package manager to easily create virtual environment.

```bash
uv venv
```

```bash
uv sync
```

## Solution Description

I tested 4 different models to find which will work best for this classification task: KNN, Logistic Regression, SVM and Random Forest.

For every model I performed hyperparameters optimization and displayed test set results visualzations.

Also for Random Forest I ploted feature importance graph to see which feature had the highest impact on model conclusion.

In the end for this particular task I came to conclusion that Random Forest might be the best becouse of its explainability.