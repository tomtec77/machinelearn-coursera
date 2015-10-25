# Coursera Practical Machine Learning - Prediction Assignment
### Tomas E. Tecce


## Summary

In this project I use accelerometer data collected from several users
doing barbell lifts in different ways to build a predictive model which
identifies how the exercise is being done. The original data includes 159
variables. By eliminating columns which mostly consist of empty values,
and then using principal component analysis, I obtain 25 features which
are then used to build a random forest model. The model obtained,
evaluated on a sample separated for calibration from the training set, has
an out of sample error of at least 5.53 per cent.

## Data

The training data for this project are available here: 

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here: 

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The data for this project come from this source:
http://groupware.les.inf.puc-rio.br/har.

## Files

- `weight_lifting_prediction.Rmd`: R Markdown source file. The code in
this file will download the data files if it does not find them in a
subdirectory called 'data/' in the working directory. The model
predictions on the test data set will be stored in text files in a
subdirectory called 'output/' which will be created if it does not exist.
- `weight_lifting_prediction.html`: compiled HTML page. This project has a
`gh-pages` branch so you can access the page directly at this URL:
http://tomtec77.github.io/machinelearn-coursera/weight_lifting_prediction.html.
- README.md: this file.
