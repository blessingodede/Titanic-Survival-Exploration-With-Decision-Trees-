# Titanic-Survival-Exploration-With-Decision-Trees-
# Lab: Titanic Survival Exploration With Decision Trees

### Getting Started

In this lab, you will see how decision trees work by implementing a decision tree in sklearn.

We'll start by loading the dataset and displaying some of its rows.
### Installation
This project requires **Python 3.7** and the following Python libraries installed:

- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [matplotlib](https://matplotlib.org/)

You are also required to have software installed to run and execute a [Jupyter Notebook](https://jupyter.org/) .

We recommend you install [Anaconda] (https://www.anaconda.com/distribution/), a pre-packaged Python distribution that contains all of the necessary software and libraries for this project.

### Features

Recall that these are the various features present for each passenger on the ship:
- `Survived`: Outcome of survival (0 = No; 1 = Yes)
- `Pclass`: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
- `Name`: Name of passenger
- `Sex`: Sex of the passenger
- `Age`: Age of the passenger (Some entries contain `NaN`)
- `SibSp`: Number of siblings and spouses of the passenger aboard
- `Parch`: Number of parents and children of the passenger aboard
- `Ticket`: Ticket number of the passenger
- `Fare`: Fare paid by the passenger
- `Cabin`: Cabin number of the passenger (Some entries contain `NaN`)
- `Embarked`: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

Since we're interested in the outcome of survival for each passenger or crew member, we can remove the **Survived** feature from this dataset and store it as its own separate variable `outcomes`. We will use these outcomes as our prediction targets. 

### Dataset
The dataset used in this project is included as titanic_data.csv.

### Code

Template code is provided in the titanic_survival_exploration.ipynb notebook file and and the titanic.csv dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory titanic_survival_exploration/ run one of the following commands:
```
ipython notebook titanic_survival_exploration.ipynb
```
Or

```
jupyter notebook titanic_survival_exploration.ipynb

```
### Target Variable

`survival` : Survival (0 = No; 1 = Yes)



