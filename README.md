# titanic survival prediction project

## project overview
this project aims to predict the survival of passengers aboard the titanic, utilizing machine learning models. the dataset includes various features like passenger class, sex, age, and fare, which are analyzed and used to train models to predict survival outcomes.

## dataset
the dataset used in this project is split into two parts:
- `train.csv`: contains the details of a subset of the passengers on board (891 passengers) and importantly, will reveal whether they survived or not, making this the training set.
- `test.csv`: contains a similar set of information but does not disclose the 'survived' information for 418 passengers. this set is used to test the performance of the trained models.

## installation
to set up your environment to run this code, you will need python 3.6+ and the packages listed in `requirements.txt`.

you can install them using:
pip install -r requirements.txt

## usage
1. start by exploring the `eda.ipynb` notebook to understand the dataset and preprocessing steps.
2. proceed to `modeling.ipynb` for the modeling process, including training and evaluation of various models.
3. you can run the flask api (if implemented) for the model deployment by executing:
flask run

*note: adjust the command based on your flask application setup.*

## models and evaluation
this project explores several machine learning models, including logistic regression, random forest, and support vector machines. models are evaluated based on their accuracy and the ability to predict survival on the titanic.

the best-performing model is then serialized and saved in the `models/` directory, ready for deployment.

## contributing
contributions to this project are welcome! please fork the repository and submit a pull request with your proposed changes.

## license
[mit license](LICENSE.txt)

