# Neural-Networks
Neural network method to analyze peptides data from a mass spectrometer system and build a model to predict lab outcomes. 
Perform the following activities in R:
1.	Load data in input data files, i.e., “Peptide.csv”, into a data frame in R.
2.	Delete variables that are irrelevant to this lab, i.e., variables not listed above. Keep “#Spec” as the output variable.
3.	Replace the 1/K0 Range column with 3 columns described above.
4.	Normalize all columns corresponding to the input variables and scale the values to range [0-1]. Do not normalize the output variable.
5.	Sample 75% of the data as the training dataset and the remaining 25% as the testing dataset.
6.	Use the neuralnet() function in package “neuralnet” to train the model, using the training dataset. Set the number of hidden nodes to 1.
7.	Using the model to test the data in the testing dataset and predict the “#Spec” values for the testing dataset. 
8.	Compute the correlation coefficient and the MAE between the predicted values and the real values.
9.	Use the plot() function to visualize the neural network model. 
10.	Create a scatterplot to display the predicted values and the real values, using geom_smooth() to show two curves with different colors, and using “peptide” values (strings) on X-axis.
11.	Repeat steps 5-9, but set the number of hidden nodes to 5.
