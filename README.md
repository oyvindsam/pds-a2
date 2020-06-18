#COSC2670 Practical Data Science @ RMIT
### Assignment 2 
The assignment task was to select a dataset and explore it, 
using all the relevant steps in the data science process (goal, data retrieval,
preparation, exploration, modeling, and presentation). 


## Abstract
The aim of this project is to find which of the classifiers 
‘K-nearest neighbor’ or ‘Decision tree’ models activity data with the best 
accuracy. Data from a dataset of acceleration measurements of 7 activities 
was used. Features from a time-window of 1 second (52 Hz) were extracted. 
In the end, K-nearest neighbors was found to give the best accuracy with 84% 
correct classifications out of a test size of 20% of the available data, 
compared to decision tree with 67%. Further recommendations include looking 
into more and better features to extract from this frequency data, and to 
research using various window lengths.


#### Report
The rest of the report can be found in ```report.pdf```. 

#### Code
The code is in ```Assignment2.ipynb```, and can be viewed/run using a 
Jupyter environment.


#### Dataset
The activity dataset used can be found [here](https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+from+Single+Chest-Mounted+Accelerometer).
