# Neural_Network_Charity_Analysis

## Overview
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## What You're Creating
- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model
- Deliverable 4: A Written Report on the Neural Network Model (README.md)

## Resources
- Charity_Data.csv, Alphabet Soup Charity starter code, Jupyter Notebook

## Results

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- binned APPLICATION_TYPE, and categorized any value less then 500 as other
- IS_SUCCESSFUL was our target variable

What variable(s) are considered to be the features for your model?
- After the data preprocessing step, our data was left with 43 remaining vairables as the features (such as STATUS, ASK_AMOUNT, APPLICATION TYPE, etc)

What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME columns were removed - no value to these columns
 
### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?

What steps did you take to try and increase model performance?
 

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

### Evaluate Model 1 - Original Model

<img width="600" alt="1 evaluate module" src="https://user-images.githubusercontent.com/104927745/197099896-3176bee0-3be1-45e5-b5cd-72f1138b4be6.PNG">

### Optimizer #1

<img width="600" alt="optimizer 1" src="https://user-images.githubusercontent.com/104927745/197099899-d5847463-f997-47b1-9c84-36214e4fda7e.PNG">

### Optimizer #2

<img width="600" alt="optimizer 2" src="https://user-images.githubusercontent.com/104927745/197099901-7f62df87-0d06-4796-b07b-acd9621c1fc1.PNG">

### Optimizer #3

<img width="600" alt="optimizer 3" src="https://user-images.githubusercontent.com/104927745/197099903-052837f1-779f-44a3-b649-4233185976f4.PNG">

### Comparing Optimization Options

<img width="600" alt="comparing optimization options" src="https://user-images.githubusercontent.com/104927745/197099905-0456e154-dfa8-4819-a510-970bf505a138.PNG">
