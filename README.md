# Titanic

## _Machine learning from disaster_

![image](https://github.com/g3rley/titanic/assets/96620547/2dd6bdac-46f6-4659-b7f0-7db242bd4ef5)

This repository contains the code and related files for the "Titanic: Machine Learning from Disaster" project on Kaggle. The goal of the project is to create a machine learning model that predicts whether a passenger survived the Titanic shipwreck or not.


### Competition Description

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew.  This sensational tragedy shocked the international community and led to better safety regulations for ships.

### Goal

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

### Data

We provide two datasets: a training set (`train.csv`) and a test set (`test.csv`).


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

### License

This project is licensed under the MIT License. See the LICENSE file for more information.
