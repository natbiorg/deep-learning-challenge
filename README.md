<h2> Overview </h2>
This analysis classifies whether applicants will be successful or not succesfful if funded by Alphabet Soup. Using data from Alphabet Soup that includes 34,000 previous applicants, we train a model to predict whether an applicant will be succesfful if funded. 

<h2> Results </h2>
The model produced is able to predict whether an applicant will be successful with 0.73 accuracy and 0.55 loss. 
  
<h3> Data Preprocessing</h3>
The data we receive from Alphabet Soup has 34,299 samples and 12 features. The majority of the features are category freatures leading us to convert most of them to dummies. 

We are most interested in whether the application was susccessful, what type of application it was, and how the application was classified. 
We convert these category features into dummies so that the majority of columns (44) are now binary. 

What variable(s) are the target(s) for your model?
What variable(s) are the features for your model?
What variable(s) should be removed from the input data because they are neither targets nor features?

<h3> Compiling, Training, and Evaluating the Model</h3>
The model includes 2 hidden layers and 1 output layer for 3 layers todal. It has 80 neurons on the first hidden layer, 30 on the second hidden layer for 110 total. 
It uses two activation functions, simoid and relu. Sigmoid is used on the first and output layer. 

In the future, I would increase model performance by increasing the number of neurons in each layer. Or if I don't see a meaningful increase in model accuracy by increasing neurons, I would add another layer. 
I would also take another look at my data preprocessing methods and determine whether they are best for this data. 

<h2> Summary </h2>
