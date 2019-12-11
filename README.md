# Machine Learning and Statistics Assessment

by Luisa Timothy

There are three parts which will be addressed:

#### 1. Describe: 
Create a git repository and make it available online for the lecturer to clone. The repository should contain all your work for this assessment. 
Within the repository, create a jupyter notebook that uses descriptive statistics and plots to describe the Boston House Prices dataset. This part is worth 20% of your overall mark. 

- short explanation what the dataset is and which attributes are recorded in the dataset
- the first thing I am doing here is importing the libraries necessary
- importing the dataset using pandas
- print the dataset
- to print the descriptions of the keys I am using sklearn, I cannot figure out how to manipulate the dataset as needed with sklearn for this section so I changed to using pandas
- show correlations between the tax and crime variables in the dataset
- use some graphs to visualise these correlations
-Display a heatmap of the correlations between all of the variables
-Brief discussion of findings

#### 2. Infer: 
- Splitting the dataset so that the variables CHAS and MEDV are used
- CHAS is the dummy variable for Charles River and MEDV is the median value for owner-occupied homes
- Calculating the minimum, maximum, mean, median, and standard deviation for the properties along the Charles River and the properties of the rest of the dataset
- Summary of statistical information, where the t and p values are the most important
- Histogram displaying the data
- One-way ANOVA results
- Brief discussion of the results 

#### 3. Predict: 
- Importing Keras, split the data, and display it
- Calculating the means for test and training data
- Build and compile the neural network
- Defining the data and starting the neural network
- Displaying the scores and also the mean of all scores
- Display the mean squared error as well as the mean absolute error for the neural network
- Brief discussion of findings