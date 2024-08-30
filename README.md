Written Report

The purpose of this analysis was to create a model that accurately predicts whether or not a charitable organization will be "successful". 

We began by removing the charity's name and identification number, as those were not necessary for the analysis, and may actually create a lower accuracy score than we ultimately received. The target variable is what we are trying to use the model to predict. In this case, the target variable is "IS SUCCESSFUL". The feature variables are all the other variables in the scenario, except for the ones we removed. In this case, the feature variables are everything except "IS SUCCESSFUL" "EIN" & "NAME". 

Initially, I tested the model with two hidden layers. The first layer, firing 80 neurons, the second layer firing 30 neurons, and these layers coming together in one output. That yielded an accuracy of 72%, which is not ideal. 
For my next attempt, I wanted to see the effects of adding another hidden layer to the model. I added a third hidden layer, this time with layer 1 firing 80 neurons, layer 2 firing 50 neurons, and layer 3 firing 30 neurons. The accuracy did not change. 
For my next attempt, I wanted to see if changing the number of neurons in the hidden layers would affect the outcome. I increased the number of neurons in the third hidden layer to 50 instead of 30. The accuracy did not change. 
Finally, I thought about compiling my strategies together. What if i increased the number of hidden layers, while simultaneously increasing the number of neurons in each layer. I increased the first hidden layer to 100 neurons, the second and third hidden layers to 80 neurons, and added a fourth hidden layer with 50 neurons. Unfortunetely that still did not bring the accuracy up to a high enough score to deem this model effective. 

In summation, increasing the hidden layers, and neurons did not affect to accuracy of the model, so I would recommend looking closer at the data, and seeing if there are some features that were originally included in the model that are hindering the most accurate results. Once those features are found, I recommend removing them, as we did with "EIN" & "NAME" and seeing if the accuracy improves.
