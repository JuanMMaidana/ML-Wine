# Wine Quality Prediction

This project leverages machine learning to analyze and predict the quality of wines based on their physicochemical properties. Through this case study, we aim to showcase how data can be utilized to build predictive models and derive insights into wine quality evaluation.

## Dataset

The dataset used in this project is the [Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) from Kaggle. It includes chemical measurements and quality scores for red and white wines. The key features are:

- **Chemical Properties:** These include variables such as acidity, sugar content, pH level, alcohol percentage, etc.
- **Target Variable:** The quality score, which ranges from 0 to 10 and is assigned by wine tasters.

The dataset has been preprocessed and is ready for analysis. It is an excellent resource for classification and regression tasks.

## Objective

The main goal of this case study is to build a machine learning model that predicts the quality of wine based on its chemical attributes. This involves:

1. **Exploratory Data Analysis (EDA):** Understanding the dataset's structure, identifying patterns, and uncovering relationships between variables.
2. **Feature Engineering:** Preparing the dataset for modeling by handling missing values, scaling, and selecting the most relevant features.
3. **Model Training and Evaluation:** Experimenting with different machine learning algorithms to achieve high accuracy in quality prediction.
4. **Interpretability:** Analyzing feature importance to gain insights into the factors that most influence wine quality.

## Methodology

The analysis and implementation follow the detailed steps outlined in the [case study blog post](https://juanmmaidana.github.io/posts/wine/). The workflow includes:

1. Data preprocessing and cleaning.
2. EDA using visualizations and statistical analysis.
3. Training models such as decision trees, random forests, or neural networks.
4. Fine-tuning hyperparameters for improved performance.
5. Evaluating the model using metrics like accuracy, precision, recall, or mean squared error.

## Requirements

To run the code, you need the following dependencies:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook (optional, for interactive analysis)

You can install the required packages with:

```bash
pip install -r requirements.txt
