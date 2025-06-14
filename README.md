# datafun-07-ml

In this final module, I'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. I'll employ a type of supervised learning, simple linear regression, to train a model and use the resulting model (a "best-fit" straight line) to make predictions. Python makes it easy! 

In this project, I'll:

Build a model
Make predictions
Visualize the model
Publish your insights

# Steps

Step 1
- Created a new repo datafun-07-ml
- Cloned the remote project into vscode
- Added a .gitignore and requirements.txt files to add what couldn't be tracked in repo and also external packages to be installed respectively

Step 2
- Created a project virtual environment file process for references
- Created virtual environment
- Activate virtual environment
- Installed external dependencies
- Update README.md file
- Set VSCode Python Interpreter



Create a new notebook in your repository named yourname_ml.ipynb.
In a Markdown cell at the top of the notebook, add:
The Notebook Title
Your Name as Author
A Clickable Link to your GitHub project repository.
In a Python cell just after, add all your import statements, organized following standard conventions. 
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 
Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 
 

CC 7.5:  Chart a Straight Line (Part 1)
Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. 
Chart a Straight Line

Add a Markdown cell with a second-level heading named Part 1 - Chart a Straight Line
Follow the instructions from 10.16 (starting page 414).
Use Markdown cells to create section headings as you work. 
Use pandas DataFrames to plot Celsius vs Fahrenheit 
Refresh your understanding of the equation for a line (y = mx + b) and be familiar with the use of:
m = the slope of the line (rise over run or delta y over delta x)
b = the y-intercept of the line (where the straight line crosses the y axis). 
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 
Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 
 

 

CC 7.6:  Predict Avg High Temp in NYC in January (Part 2)
Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. 
Use Linear Regression on Average High Temperatures in NYC in January. Read these notes before you start:

Continue following the instructions from 10.16 (starting page 416).
The data is for the average high temperature in January over many years.
For example, in 1895, the average high temperature in January was 34.2.
We only care about this one series of data: the "average high temp in Jan".
There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
We'll use all of the data available to build a best-fit line (supervised learning). 
We'll use the slope and intercept of the best-fit line to predict a point in the future.
Add to your notebook as you work through the process. Add a Markdown cell with a second-level heading named Part 2 - Prediction. Use third-level Markdown headings for each section listed below. Copy and paste the section heading if you like, and add a ### space before each. 

Section 1 - Data Acquisition
Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
Recommended: Rather than nyc, name the dataframe nyc_df to reinforce the DataFrame operations.
Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 
Section 2 - Data Inspection
Follow the instructions to view head and tail of the file. 
Section 3 - Data Cleaning
Follow the instructions to clean the data. Improve the column names and clean up the date series. 
Section 4 - Descriptive Statistics
 Set the display precision to 2 decimal places. Use 'display.precision' instead of 'precision' as shown in the text.
Use describe() to calculate basic descriptive statistics for the dataset. 
Section 5 - Build the Model
Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 
Section 6 - Predict
Use your model to predict the "average high temp in Jan" for the year 2024 (just like they did for 2019).
Section 7 - Visualizations
Follow the instructions and use Seaborn to generate a scatter plot with a best fit line.
Set the axes and the y scale as directed
Customize your chart and notebook as you like to make your work clear and compelling. 
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 
Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 
 

 

CC 7.7: Predict Avg High Temp in NYC in January (Part 3)
Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. 
Use Linear Regression on Average High Temperatures in NYC in January using a different approach. Read these notes before you start:

Continue the project by following the steps in 15.4 (staring page 620 in your textbook). 
This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values). 
Follow the instructions all the way though charting it again with the specified axes.
Add to your notebook as you work through the process. Add a Markdown cell with a second-level heading named Part 3 - Prediction.  

This work is already done - you do not need to repeat it: 

Section 1 - Data Acquisition
Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
Recommended: Rather than nyc, name the dataframe df to reinforce the DataFrame operations.
Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 
Section 2 - Data Inspection
Follow the instructions to view head and tail of the file. 
Section 3 - Data Cleaning
Follow the instructions to clean the data. Improve the column names and clean up the date series. Set the precision.
Section 4 - Descriptive Statistics
Use describe() to calculate basic descriptive statistics for the dataset. 
These sections are new - add these numbered sections to Part 3. Use third-level Markdown headings for each section listed below. Copy and paste the section heading if you like, and add a ### space before each.

Section 1 - Build the Model
Use test_train_split to split the data into parts for training and testing.
Recommended: Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 
Check the shape of each data set.
Train the model using Linear Regression Fit. 
View the returned coef_ and intercept_  attributes need for the line equation (y = mx + b)
Section 2 - Test the Model
Test the model as directed.
Section 3 - Predict 
Use your model to predict the "average high temp in Jan" for the year 2024 (like they did for 2019).
Section 3 - Visualizations
Follow the instructions and use Seaborn to generate a scatter plot with a best fit line.
Set the axes and the y scale as directed
Customize your chart and notebook as you like to make your work clear and compelling. 
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 
Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 
 

CC 7.8: Add Your Insights (Part 4)
Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. 
At the end of your notebook, add a second-level Markdown Heading for Part 4 with some remarks comparing the two methods.

Excellent analytical skills need professional communication skills to be of maximum benefit. 
Your narrative and the way you present your work is key. 
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 
Optional - if you have any issues, ask your favorite AI or your team members in the associated discussion. Use screenshots and paste error messages so we can help. 


Optional Bonus
Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. 
Showcase your Skills With the California Housing Dataset

Practice more machine learning skills by working through 15.5 with the California Housing Dataset.
In the same notebook, add a Markdown heading for Part 5 - Bonus.
Follow the instructions all the way though loading the data, training and testing the data, visualizing the data, and choosing the best model from the 4 listed. 
Use appropriate Markdown Section headings to present your work. 
Customize your presentation and include helpful remarks to "tell a story with data".
Always

Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 



INSTRUCTIONS


P7: Predictive ML Project (Due THURS, no late work)
 null

 Assignment - Introduction to Machine Learning

No Late Work in Module 7
To be eligible for credit, a valid submission must be received by the deadline.

No late work is accepted in Module 7, regardless of reason. To reduce the risk of a zero due to internet problems or other last minute emergencies, submit a day or two early. 

 

Introduction to Machine Learning
In this final module, you'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a "best-fit" straight line) to make predictions. Python makes it easy! 

In this project, you'll:

Build a model
Make predictions
Visualize the model
Publish your insights
 

Build a Model
First, we'll use several tools to load our data into a pandas DataFrame and build a couple different types of models. 

Make Predictions
We'll use each model to make a prediction.  Using simple linear regression, we draw the best-fit line and use the line to extrapolate out to future values. We can say: for this x-value (out in the future), what would be the y-value on that straight line?  The answer will be our prediction. 

 

Visualize The Data
We'll use Seaborn and Matplotlib to create visualizations of both our data - and our best-fit line. 

 

Publish your Insights
Predictions may or may not match reality. The presentation of our work and our own insights into what we learned (or failed to learn) are valuable. Being able to assess and compare approaches is critical. No one knows the right model or approach for the new data problems you'll solve. You'll often try several approaches and the best ones for a specific problem will be the most valuable.  The ability to consistently try models, test them, improve our approach, and make better predictions is the goal. 

Textbook Chapters
Work through the book and examples from Chapter 10 refreshing especially your work on 10.16 on Time Series and Simple Linear Regression.
Read through the book and examples from Chapter 15 on Machine Learning, focusing on 15.4 Simple Linear Regression and Predictions.
Sample Data
Data files can be downloaded from: https://github.com/pdeitel/IntroToPythonLinks to an external site.
ACT: CC 7.1 Start a New Project
Follow the steps in our standard "Start New Project" workflow. Use your own notes from prior projects. There is no specification for this project - use datafun-07-ml for your project repository name. Ask questions and verify your work at:

CC7.1: Start a New Project

ACT: Work Through Chapter 10 
Read and work through Chapter 10 - Object-Oriented Programming - and understand the examples. A pandas DataFrame is a frequently used class. When you load data into a DataFrame, you use the attributes and methods (functions) available to all DataFrames to manage your specific instance of a DataFrame. Play special attention to  10.16 ★ Intro to Data Science: Time Series and Simple Linear Regression.

10.1 Introduction
10.2 Custom Class Account
10.3 Controlling Access to Attributes
10.4 Properties for Data Access
10.5 Simulating “Private” Attributes
10.6 Case Study: Card Shuffling and Dealing Simulation
10.7 Inheritance: Base Classes and Subclasses
10.8 Building an Inheritance Hierarchy; Introducing Polymorphism
10.9 Duck Typing and Polymorphism
10.10 Operator Overloading
10.11 Exception Class Hierarchy and Custom Exceptions
10.12 Named Tuples (interesting, but we don't do much with these)
10.13 A Brief Intro to Python 3.7’s New Data Classes
10.14 Unit Testing with Docstrings and doctest
10.15 Namespaces and Scopes
10.16 ★ Intro to Data Science: Time Series and Simple Linear Regression
You should now be able to run all the book examples on your machine. Add some of their example files to your Module 7 repository and run them. Install dependencies as needed. Ask questions and verify your work at:

CC7.2: Explore Object-Oriented Programming

 

ACT: Work Through Chapter 15
Read and work through Chapter 15 - Machine Learning - and understand the examples. 

15.1 Introduction to Machine Learning
15.1.1 ★ Scikit-Learn
15.1.2 ★ Types of Machine Learning
15.1.3 Datasets Bundled with Scikit-Learn
15.1.4 Steps in a Typical Data Science Study
15.2 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 1
15.3 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 2
15.4 ★ Case Study: Time Series and Simple Linear Regression
 

You should now be able to run all the book examples on your machine. Add some of their example files from Ch 15 to your Module 7 repository and run them. Install dependencies as needed. Ask questions and verify your work at:

CC7.3: Explore Machine Learning

EXPLORE: Learn and check your understanding
Take the skill drills / GUIDES and ask questions in the project discussion for this Module.

APPLY: Implement 10.16 and 15.4 
For Project 7, we'll implement the guided projects in 10.16 and 15.4.

I'll leave all the instructions together as they take you through all of Project 7. You are encouraged to post as you complete each step. If you run into issues, we'll be able to see what step you're on and how we can help. If everything is working well, just keep going - by the end, you'll be done with Project 7.   After this, you'll be ready for new Python data analytics projects of all kinds - projects using streaming data, continous intelligence and interactive analytics with dashboards, web mining and natural language processing, and more types of machine learning. Get comfortable with the basics - and leave yourself good notes in your README.md so you can apply these skills in future work. 

You should have already completed these steps:

CC7.1: Start a New Project
CC7.2: Explore Object-Oriented Programming
CC7.3: Explore Machine Learning
Now continue.

CC 7.4:  Start a New Jupyter Notebook
Add a notebook to your project repository and follow the process provided in the text. Generally, we recommend doing the following in VS Code.

Always

Open your project repository folder in VS Code. 
Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. (It's good practice to ALWAYS pull before starting work.)
Start a New Notebook


