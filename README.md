# Titanic

## _Machine learning from disaster_

![image](https://github.com/g3rley/titanic/assets/96620547/2dd6bdac-46f6-4659-b7f0-7db242bd4ef5)

This repository contains the code and related files for the "Titanic: Machine Learning from Disaster" project on Kaggle. The goal of the project is to create a machine learning model that predicts whether a passenger survived the Titanic shipwreck or not.

### Competition Description

The sinking of the RMS Titanic remains an indelible mark on maritime history, standing as one of the most notorious shipwrecks to date. On the fateful day of April 15, 1912, during its inaugural journey, the Titanic met its demise when it struck an iceberg, leading to the devastating loss of 1502 lives out of the 2224 passengers and crew aboard. This heartrending incident reverberated across the globe, prompting the international community to enforce stringent safety measures for all future vessels.

### Goal

The challenge is to analyze the characteristics of the passengers and develop a machine learning model that can predict the likelihood of survival. By applying the tools of machine learning, we aim to predict which passengers survived the tragedy.

### Data

The repository provides two datasets: a training set (train.csv) and a test set (test.csv).

### Variable Notes

**pclass**: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

**parch**: The dataset defines family relations in this way...

Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

**Embarked**: Port of Embarkation
C = Cherbourg, Q = Queenstown, S = Southampton

**Survival**: 0 = No, 1 = Yes

### Evaluation

The evaluation metric for this competition is accuracy, which measures the percentage of correctly predicted passengers.

### Submission File Format

You should submit a CSV file with exactly 418 entries plus a header row. Your submission will show an error if you have extra columns (beyond PassengerId and Survived) or rows.

The file should have exactly 2 columns:

* PassengerId (sorted in any order)
* Survived (contains your binary predictions: 1 for survived, 0 for deceased)

``` sh
PassengerId,Survived
 892,0
 893,1
 894,0
```

### Usage

Clone the repository to your local environment:
    
```sh
git clone https://github.com/g3rley/titanic.git
```

Install the project dependencies:

    
```sh
pip install -r requirements.txt
```

Run the **titanic.ipynb** Jupyter Notebook to explore the data, create and evaluate the model.

Export the final model predictions to the **submission.csv** file.

### Built With

* [Python](https://www.python.org/) - Programming language
* [Jupyter Notebook](https://jupyter.org/) - Web application for creating and sharing documents that contain live code, equations, visualizations and narrative text
* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation tool
* [NumPy](https://numpy.org/) - Library for working with arrays
* [Matplotlib](https://matplotlib.org/) - Library for creating static, animated, and interactive visualizations
* [Seaborn](https://seaborn.pydata.org/) - Data visualization library based on matplotlib
* [Scikit-learn](https://scikit-learn.org/stable/) - Machine learning library for the Python programming language


### Authors

* **Gerley Adriano** - [g3rley](https://github.com/g3rley)

### Acknowledgments

* [Kaggle](https://www.kaggle.com/c/titanic/overview)


### License

This project is licensed under the MIT License. See the LICENSE file for more information.
