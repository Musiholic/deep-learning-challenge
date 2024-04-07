### deep-learning-challenge###
#1. Overview of the analysis:#
The purpose of the analysis is to develop a prodictive model using neural networks to help the company Alphabet Soup identify successful applicants.
We aim to streamline the applicant selections to maximize Alphabe soup resources.

#2. Results: Using bulleted lists and images to support your answers, address the following questions:#

##Data Preprocessing##

#What variable(s) are the target(s) for your model?##
- The target variable for the model is "IS_SUCCESSFUL".
	
#What variable(s) are the features for your model?##
-The features are various metadata columns

#What variable(s) should be removed from the input data because they are neither targets nor features?#
	#Compiling, Training, and Evaluating the Model#
-We removed "EIN" and "NAME" columns from the input data due to not being relevant predictive modeling.

#How many neurons, layers, and activation functions did you select for your neural network model, and why?#
-Neurons:2, we ran these localy on our computers so we had limited resources
-layers: 50 and 30 then 90 and 40 layers, I honestly used a random number
-activation functions:"sigmoid" "relu" due to using these in class

#Were you able to achieve the target model performance?#
- We were looking for 75% accuracy in our model and only acchieved a low 72% thus not acchieving our goal

#What steps did you take in your attempts to increase model performance?#
-Looking to achieve model performance we looked into increasing total epochs and layers.

#3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.#
-We can look into KNN, logistic regression, and ensamble. I am not exactly sure what different models would be best due to lack of research.