# Codeaplha_1
# Titanic Survival Prediction

## Overview

This project aims to predict survival on the Titanic using machine learning techniques. The dataset used is the famous Titanic dataset from Kaggle, which contains information about passengers onboard the Titanic, including whether they survived or not.

## Dataset Information

The Titanic dataset consists of the following columns:

- `PassengerId`: Unique identifier for each passenger.
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger's name
- `Sex`: Passenger's gender (Male or Female)
- `Age`: Passenger's age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Installation

1. Clone this repository: `git clone https://github.com/your-username/titanic-survival-prediction.git`
2. Navigate to the project directory: `cd titanic-survival-prediction`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Ensure you have Python installed.
2. Install the required libraries as mentioned above.
3. Download the Titanic dataset (train.csv) from [Kaggle](https://www.kaggle.com/c/titanic/data) and place it in the project directory.
4. Run the Jupyter Notebook or Python script: `python titanic_prediction.py` or `jupyter notebook titanic_prediction.ipynb`.
5. Follow along with the code and comments to understand the data preprocessing, model training, and evaluation.

## Files

- `train.csv`: The training dataset containing passenger information.
- `titanic_prediction.ipynb`: Jupyter Notebook containing the code for data analysis, preprocessing, model training, and evaluation.
- `requirements.txt`: List of Python dependencies required for this project.

## Approach

1. Data Loading and Exploration: Load the dataset and explore its structure, missing values, and statistics.
2. Data Preprocessing: Handle missing values, encode categorical variables, and split the data into training and testing sets.
3. Model Training: Use Logistic Regression to train a model on the training data.
4. Model Evaluation: Evaluate the model's performance on both training and testing data using accuracy score.

## Results

- Training Data Accuracy: 80.76%
- Testing Data Accuracy: 78.21%

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-improvement`).
6. Create a new Pull Request.

## Credits

- Initial dataset from [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- Code and analysis by [Himasri]

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
