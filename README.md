<h2> Overview </h2>
This analysis classifies whether applicants will be successful or not succesfful if funded by Alphabet Soup. Using data from Alphabet Soup that includes 34,000 previous applicants, we train a model to predict whether an applicant will be succesfful if funded. 

<h2> Results </h2>
The model produced is able to predict whether an applicant will be successful with 0.73 accuracy and 0.55 loss. 
  
<h3> Data Preprocessing</h3>
The data we receive from Alphabet Soup has 34,299 samples and 12 features. The majority of the features are categorical leading us to convert most of them to dummies. 
We drop columns identification columns EIN and Name and covert outlier values for Application Type and Classification to other. These values are not relevant for analysis. We then tranform the remaining features into binary columns where applicable. This leaves us with 43 input features, again the majority of which are binary classification features. 

<h3> Compiling, Training, and Evaluating the Model</h3>
The model includes 2 hidden layers and 1 output layer for 3 layers todal. It has 80 neurons on the first hidden layer, 30 on the second hidden layer for 110 total. 
It uses two activation functions, simoid and relu. Sigmoid is used on the first and output layer. 

In the future, I would increase model performance by increasing the number of neurons in each layer. Or if I don't see a meaningful increase in model accuracy by increasing neurons, I would add another layer. 
I would also take another look at my data preprocessing methods and determine whether they are best for this data. 

<h2> Summary </h2>
This deep learning analysis classifies the success of applicants for funding from Alphabet Soup, using 34,000 previous applicants. The model achieved 0.73 accuracy with 0.55 loss, indicating room for improvement. It may be worth trying a logrithmic regression instead to explore whether there is a linear relationship between the features and an applicants success. 
