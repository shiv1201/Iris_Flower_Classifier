"# Iris_Flower_Classifier Web App" 


##pip install streamlit

##pip install pandas

##pip install -U scikit-learn


Front end: -The sidebar found on the left will accept input parameters pertaining to features 
			(i.e. petal length, petal width, sepal length and sepal width) of Iris flowers. 
			
			-These features will be relayed to the back-end where the trained model will predict the class labels as a function of the input parameters.
			
			-Prediction results are sent back to the front-end for display.


Back end:	- The user input parameters will be saved into a dataframe that will be used as test data. 

			- A classification model will be built using the random forest algorithm from the scikit-learn library. 
		
			- Finally, the model will be applied to make predictions on the user input data and return the predicted class labels as being one of three flower type: setosa, versicolor or virginica. 
		
			-Additionally, the prediction probability will also be provided that will allow us to discern the relative confidence in the predicted class labels.


