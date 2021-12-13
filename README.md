# LogisticRegression

Our task is to explore our Bank's Marketing campaign and create meaningful insights from the data

The step one should be accessing the data

Our data has been curated by UCI Machine Learning Repository which is an excellent datahouse of various real world problems!

The data can also be downloaded from the Tech I.S. Github Repository


# Section I : Data Loading

Part I : Load the dataset into the notebook

Part II : Explore and make note of Attribute Information from UCI

Part III : What is the significance of the y column in the dataset and what are the value counts of the y column?

Part IV : What is the ratio of the two classes ? Are they balanced ?

# Section II : Data Cleaning

Since this is real world data , A good practice is to make sure the dataset is devoid of any nuances

Part I : Get the dtypes of all the columns of our dataset

Part II : Refering to the UCI data description , explore the data in your columns and check if there are any errors

Part III : Using Data Cleaning principles you learned from Pandas Tutorial) figure out the best ways to get rid of the dirty data Part V : Print the cleaned data

# Section III : Exploring data with Group by

In this section , we must create some primitive EDA

Use the groupby function on the mean of the following columns :

I : y

II : job

III : marital

IV : education


# Section III : Exploratory Data Analysis

Let us put Matplotlib to use !

Part I : Create bar graphs to the frequency of purchase with respect to the job , martial etc

Part II : Also create stacked bars to same data columns with respect to

Part III : Explore the age column using a histogram and note down your observations

# Section IV : Categorical Variable Encoding

Part I : Create dummy variables for your categorial variables

part II : Explore your new dataset with these new dummy variables !

# Section V : Preliminary Training

Part I : Import your Logisitc Regression libraries

Part II : Split your train and test dataset and train on the data

Part III : Make note of the classification report and other metrics

# Section VI : Let's Improve the performance !


Part I : Make note of the performance from the last training

Part II : Try implementing SMOTE to balance the two class labels

Part III : Make note of the y label data now , what are the rations now ?


# Section VII : Training time !

Now that we have found the best columns for this problem

Part I : Now train the model with the new data you have created after the RFE

Part II : Create the prediction system to get the metrics such as accuracy

# Section VIII : Additional Metrics

Accuracy is not always the best metric

Part I : Explore what Confusion Matrix means

Part II : Create the confusion matrix for the predictions and make note of the outputs

Part III : Create a classification report and make note of various outputs
