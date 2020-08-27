# charity_funding_neural_net
python, neural nets, tf


The charity funding dataset was analysed using python and tensor flow to create a deep neural net. Using parameter hypertuning, 3 layers with 16, 32,  and 4 neurons respectively were chosen. A performance accuracy of .734 was reached. A number of preprossing steps were taken to improve accracy. The data was explored, and columns were removed if they didn't have atleast .1% variability in the data. For categorical data, columns with more that 10 categories were binned using a density plot, and hypertuning. Finally, the categorical data was encoded using OneHotEncoder, then the entire dataset was normalized. Further exploration would inclue a random forest model as it performs well with large amounts of categorical data. 

