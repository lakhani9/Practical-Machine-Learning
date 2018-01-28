## Practical Machine Learning - Prediction 

### Background


Using devices such as JawboneUp, NikeFuelBand, and Fitbit, it is now possible to collect a large amount of data about personal activity
relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements
about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that 
people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it.

In this project, the goal is to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. The data records 
inputs to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website (see the section
on the Weight Lifting Exercise Dataset).

### Data ###  

The training data for this project are available here. The test data are available here.

training data: (https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv)  

testing data: (https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv)


### Project's rubric ###  

The goal of the project is to predict the manner in which they did the exercise. This is the classe variable in the training set. Use 
any of the other variables to predict with.


Create a report describing how to build the model, how to use cross validation, what the expected out of sample error is, and why make
the choices. Then use the prediction model to predict 20 different test cases.

### Approach to select model used in project ###  

The project explores Random Forest, Forest of Trees and GBM models to arrive at the best model to predict 'classe' - thus predicting the manner 
in which they did the exercise. The models are trained on the training data, validated using the validated data and finally tested on 20
observations.

### HTML output

The output can be found at this link


Link to github html output: (https://github.com/lakhani9/Practical-Machine-Learning/blob/master/Practical_Machine_Learning_-_Prediction_Project.html )




