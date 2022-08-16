# Space X Falcon 9 First Stage Landing Prediction

## About
The main objective is to predict if the Falcon 9 First Stage land successfully. Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a rocket launch. In this lab, you will create a machine learning pipeline to predict if the first stage will land given the data from the preceding labs.

## Objectives
#### Notebook 1
- Request to the SpaceX API
- Clean the requested data
#### Notebook 2
-  Extract a Falcon 9 launch records HTML table from Wikipedia
- Parse the table and convert it into a Pandas data frame
#### Notebook 3
- Exploratory Data Analysis
- Determine Training Labels
#### Notebook 4
- Understand the Spacex DataSet
- Execute SQL queries to answer questions using SQLite
#### Notebook 5
- Exploratory Data Analysis
- Preparing Data Feature Engineering
#### Notebook 6
- Mark all launch sites on a map
- Mark the success/failed launches for each site on the map
- Calculate the distances between a launch site to its proximities
#### Notebook 8
- create a column for the class
- Standardize the data
- Split into training data and test data
- Find best Hyperparameter for SVM, Classification Trees and Logistic Regression
  - Find the method performs best using test data
