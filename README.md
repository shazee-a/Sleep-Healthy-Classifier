# Sleep Healthy Classifier

A clear and practical machine learning project for classifying sleep health patterns using a structured lifestyle and sleep dataset.

## Overview

This project explores how lifestyle and sleep-related factors can be used to predict whether a person’s sleep condition is healthy or unhealthy. The workflow includes data cleaning, exploratory data analysis, preprocessing, feature engineering, model training, and evaluation.

## What this project includes

- A complete notebook workflow in [Sleep_HealtcClassifier.ipynb](Sleep_HealtcClassifier.ipynb)
- Data exploration and visualization on the dataset in [dataset/Sleep_health_and_lifestyle_dataset.csv](dataset/Sleep_health_and_lifestyle_dataset.csv)
- Model comparison using machine learning algorithms such as Logistic Regression and Random Forest
- A simple and readable summary of the results for presentation or learning purposes

## Project goals

The main objective of this project is to:

- understand the relationship between sleep habits and lifestyle factors
- build a classifier that predicts sleep health categories
- compare model performance and identify the most effective approach

## Project structure

- [Sleep_HealtcClassifier.ipynb](Sleep_HealtcClassifier.ipynb) main analysis and modeling notebook
- [dataset/Sleep_health_and_lifestyle_dataset.csv](dataset/Sleep_health_and_lifestyle_dataset.csv) source dataset used in the project
- [README.md](README.md) project documentation

## Workflow

1. Load and inspect the dataset
2. Clean and preprocess the data
3. Explore patterns with visualization
4. Train and evaluate classification models
5. Review the results and summarize the findings

## How to run

Make sure you have Python installed, then open the notebook in Jupyter and run the cells step by step:

```bash
jupyter notebook
```

Then open [Sleep_HealtcClassifier.ipynb](Sleep_HealtcClassifier.ipynb) and run the notebook.

## Recommended environment

This project is commonly run with:

- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Result summary

The notebook provides an end-to-end example of how to:

- prepare a dataset for machine learning
- evaluate multiple models
- interpret the model performance clearly

## Model performance summary

The following table summarizes the evaluation results from the notebook:

| Model               | PCA | Accuracy | Weighted F1 Score |
| ------------------- | --: | -------: | ----------------: |
| Logistic Regression |  No |   93.33% |            93.37% |
| Logistic Regression | Yes |   69.33% |            61.52% |
| Random Forest       |  No |   96.00% |            96.00% |
| Random Forest       | Yes |   90.67% |            90.67% |

From the results above, the Random Forest model without PCA achieved the best performance.

Confusion matrix visualizations for the evaluated models are also included in the notebook so the classification results can be inspected visually.

## License

This project is available under the license included in the repository.

..
