Train Dataset: 
We have to devise an Object Oriented solution for the problem, i.e. I create a CLASS, and solve the problem calling the class methods. 
The train dataset contains data regarding a train crash. It has ~891 records. However, all records are not complete, i.e. some have missing data. 
In this data set, our outcome of interest is the survived column, on whether an individual survived (1) or died (0) after the Train crash.  

Task completed for the solution: 
Clean the data and remove any unwanted records. How many records do you have now?  
The train picked most passengers from which station ? 
Do some basic data exploration (e.g. using commands as head( ), info( ), describe( ), nunique( ), etc). Which variables will you NOT select? 
Are there any outliers in the data? If yes, treat them. 
Partition the data into a training set (with 70% of the observations), and testing set (with 30% of the observations) using the random state of 12345 for cross validation.    
On the partitioned data, build the best KNN model. Show the accuracy numbers. (Hint: What is the best value of k? How do you decide the ‘best k’?) 
On the partitioned data, build the best logistic regression model. Show the accuracy numbers.
On the partitioned data, build the decision tree. Show the accuracy numbers. What tree depth did you choose, i.e. which one is ideal and why?  
Based on the results of k-nearest neighbor, and logistic regression, what is the best model to classify the data? Provide explanation to support your argument. 
Show some interesting graphs of the data, i.e., that can describe the original data.  
