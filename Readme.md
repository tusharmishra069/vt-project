# White Wine Quality Prediction

This project leverages machine learning techniques to predict the quality of white wine based on its physicochemical properties. By analyzing a comprehensive dataset, we build and evaluate models—primarily using a Support Vector Machine (SVM) classifier—to estimate wine quality scores. The project includes data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

## Overview

Wine quality assessment is a challenging task, often requiring expert tasters. Automating this process using data-driven approaches can help wineries maintain consistency and improve product quality. This project demonstrates how machine learning can be applied to real-world datasets to solve such classification problems.

## Dataset

The dataset used in this project contains physicochemical measurements of white wine samples, along with quality ratings assigned by human experts.

- **File:** [WhiteWineQuality.csv](WhiteWineQuality.csv)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Samples (Rows):** 4,898
- **Features (Columns):** 12

### Dataset Description

Each row in the dataset represents a different white wine sample from the Portuguese "Vinho Verde" region. The columns include various chemical properties and a quality score (the target variable). The quality score is an integer between 0 and 10, reflecting the wine's perceived quality.

#### Features

1. **Fixed acidity**: Tartaric acid content (g/dm³)
2. **Volatile acidity**: Acetic acid content (g/dm³)
3. **Citric acid**: Citric acid content (g/dm³)
4. **Residual sugar**: Sugar remaining after fermentation (g/dm³)
5. **Chlorides**: Salt content (g/dm³)
6. **Free sulfur dioxide**: Free SO₂ (mg/dm³)
7. **Total sulfur dioxide**: Total SO₂ (mg/dm³)
8. **Density**: Density of the wine (g/cm³)
9. **pH**: Acidity or basicity
10. **Sulphates**: Potassium sulphate content (g/dm³)
11. **Alcohol**: Alcohol content (% by volume)
12. **Quality**: Quality score (0–10, target variable)

### Dataset Insights

- The dataset is imbalanced, with most wines rated between 5 and 7.
- Features are continuous and require normalization for optimal model performance.
- Some features, such as alcohol and volatile acidity, are known to have a strong influence on perceived quality.


## Getting Started

To run the project, clone the repository and follow the instructions in the notebooks. Ensure you have the required dependencies installed, as listed in `requirements.txt`.

## References

- [UCI Machine Learning Repository: Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. "Modeling wine preferences by data mining from physicochemical properties." Decision Support Systems, Elsevier, 47(4):547-553, 2009.

