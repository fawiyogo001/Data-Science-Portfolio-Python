# **Titanic Data Visualization**

## Overview
This visualization project uses data about Titanic tragedy, which happened on 14 April 1912, to explore the questions regarding the data.
https://www.kaggle.com/c/titanic/data

## Data Dictionary

| Variable | Definition | Key |
| --- | --- | --- |
| survival | Survival | 0 = No, 1 = Yes |
| pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex | Sex | |
| Age | Age in years|  |
| sibsp | number of siblings / spouses aboard the Titanic |  |
| parch | number of parents / children aboard the Titanic |  |
| ticket | Ticket number | |
| fare | Passenger fare	 | |
| cabin | Cabin number | |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton|

## Variable Notes
- class: A proxy for socio-economic status (SES)
    
    1st = Upper
    
    2nd = Middle
   
    3rd = Lower
    
    ---------------------

- age: Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5

    ---------------------
- sibsp: The dataset defines family relations in this way...

    Sibling = brother, sister, stepbrother, stepsister
    
    Spouse = husband, wife (mistresses and fiancés were ignored)
    
    ---------------------
 
- parch: The dataset defines family relations in this way...

    Parent = mother, father
    
    Child = daughter, son, stepdaughter, stepson
    Some children travelled only with a nanny, therefore parch=0 for them.