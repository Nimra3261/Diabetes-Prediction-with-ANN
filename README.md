# Diabetes Prediction using Artificial Neural Network (ANN)

This repository contains a Jupyter notebook for predicting diabetes using an Artificial Neural Network (ANN). The model is trained and evaluated on the Pima Indians Diabetes Dataset.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to build a predictive model to identify whether a patient has diabetes based on diagnostic measurements. The notebook demonstrates the following steps:

1. Data Preprocessing
2. Feature Selection
3. Model Training using ANN
4. Model Evaluation

## Dataset

The dataset used in this project is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database), which contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

## Installation

To run the notebook, you need to have Python and Jupyter installed. Additionally, you need to install the required libraries specified in the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/diabetes-prediction-ann.git
    cd diabetes-prediction-ann
    ```

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook Diabetes\ Prediction\ with\ ANN.ipynb
    ```

3. Run the cells in the notebook to preprocess the data, train the model, and evaluate the results.

## Results

The final model is evaluated on the test set with the following metrics:

- Precision
- Recall
- F1-Score
- Accuracy

Example output:
```
              precision    recall  f1-score   support

Not Diabetes     0.8624    0.9400    0.8995       100
    Diabetes     0.8667    0.7222    0.7879        54

    accuracy                         0.8636       154
   macro avg     0.8645    0.8311    0.8437       154
weighted avg     0.8639    0.8636    0.8604       154
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

