# Titanic Survival Prediction Project

## Project Overview
This project aims to predict the survival of passengers aboard the Titanic, utilizing machine learning models. The dataset includes various features like passenger class, sex, age, and fare, which are analyzed and used to train models to predict survival outcomes.

## Dataset
The dataset used in this project is split into two parts:
- `train.csv`: Contains the details of a subset of the passengers on board (891 passengers) and importantly, will reveal whether they survived or not, making this the training set.
- `test.csv`: Contains a similar set of information but does not disclose the 'Survived' information for 418 passengers. This set is used to test the performance of the trained models.

## Installation
To set up your environment to run this code, you will need Python 3.6+ and the packages listed in `requirements.txt`.

You can install them using:
pip install -r requirements.txt

## Usage
1. Start by exploring the `EDA.ipynb` notebook to understand the dataset and preprocessing steps.
2. Proceed to `Modeling.ipynb` for the modeling process, including training and evaluation of various models.
3. You can run the Flask API (if implemented) for the model deployment by executing:
flask run


*Note: Adjust the command based on your Flask application setup.*

## Models and Evaluation
This project explores several machine learning models, including Logistic Regression, Random Forest, and Support Vector Machines. Models are evaluated based on their accuracy and the ability to predict survival on the Titanic.

The best-performing model is then serialized and saved in the `models/` directory, ready for deployment.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License
[MIT License](LICENSE.txt)
