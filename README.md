# Neural_Network_Charity_Analysis

1.	Overview of the analysis: 
In this project we use our knowledge of machine learning and neural networks to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

2.	Results: 
o	Data Preprocessing
	What variable(s) are considered the target(s) for your model?
The target for the model is IS_SUCCESSFUL.
	What variable(s) are considered to be the features for your model?
Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop.
	What variable(s) are neither targets nor features, and should be removed from the input data?
EIN, NAME
o	Compiling, Training, and Evaluating the Model
	How many neurons, layers, and activation functions did you select for your neural network model, and why?
At the first attempt at model, two layers, with 80 and 30 neurons respectively (both "relu" type) were used. The activation feature of "sigmoid" was used. This was presented by the client as the starting point for model creation, allowing the analyst to further adjust in order to increase optimization.

	Were you able to achieve the target model performance?
The best model’s performance was set at 75%. The best accuracy model I got from this project was 73% at the third attempt (adding additional hidden layer + changing the activation function + changing # of nodes) However on epochs 96 and 99 we saw 74% as well.
