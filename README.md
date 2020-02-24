# Kaggle: Titanic - EDM and Feature Engineering v. 01
This is a jupyter notebook that does exploratory data analysis, feature engineering and tries to predict whether the passengers in the un-labeled testing set managed to survive the shipwreck or not.

## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Files
- `Titanic_ver_01.ipynb`: This is the main notebook to analyze the data using EDM to help inform the feature engineering process and then to seek to find the best supervise learning model that attains the highest accuracy on the testing set.
- `Titanic_ver_01.html`: HTML format of the notebook for viewing in browser
- `train.csv`: The labeled training dataset
- `test.csv`: The un-labeled testing dataset
- `test_census.csv`: The test dataset to evaluate the learning algorithms

## Run

In a terminal or command window, navigate to the top-level project directory that contains this README and run one of the following commands:

```bash
ipython notebook Titanic_ver_01.ipynb
```  
or
```bash
jupyter notebook Titanic_ver_01.ipynb
```

This will open the iPython Notebook software and project file in your browser.

## Data

Training dataset has 891 entries.
Testing dataset has 418 entries.

The original features are:
-  Survived: 0 = No, 1 = Yes
-  Pclass: Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd
-  Sex: Male or Female
-  Age: Age in years
-  SibSp: Number of siblings/spouses abroad the Titanic
-  Parch: Number of parents/children abroad the Titanic
-  Ticket: Ticket Number
-  Fare: Passenger fare in pounds
-  Cabin: Cabin number
-  Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Notes
This notebook is solely for self learning purpose.
