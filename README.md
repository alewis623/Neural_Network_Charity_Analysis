# Neural_Network_Charity_Analysis
## Overview of the Analysis
Using deep learning neural networks create a binary classifier that is capable of predicting if applicates will be successful if funded by an organization. The csv contains 34K organizations and there funding history. 

## Resources
Jupyter Notebook with Python, Pandas, Sklearn, and Tensorflow. 

## Results

### Deliverable 1
The csv was successfully imported. Density plots created

![image](https://user-images.githubusercontent.com/90878901/152909263-efe37105-894b-4c2e-b4a6-fa3a84722b13.png)

The data frame was transformed. 

![image](https://user-images.githubusercontent.com/90878901/152909355-ce85f75f-42f5-433a-901a-090ac9d2d005.png)

### Deliverable 2
Deliverable 2 was to build a neural network or deep learning movle that can predict the success of a funded applicant. 
Here the structure of the model is demonstrated. 

![image](https://user-images.githubusercontent.com/90878901/152909540-3dd514d2-097d-4d37-b1da-b7a837b63203.png)

The accuracy of the model can be shown here:

![image](https://user-images.githubusercontent.com/90878901/152909601-0ba3f3a2-7cc2-40cd-8add-f05c015f81fe.png)

Per feedback from "Ask BCS" saving the model every epoch was appropriate

### Deliverable 3

In deliverable 3 the goal is to build up to 3 additional models with the goal of obtaining a 75% accuracy rate. After 8 models none of the models acheived a 75% accuracy. The number of Epochs were increased up to 500, the number of layers were as high as 4 and optimizers of Adam, Adamax, and FTRL were attempted to impove the model accuracy. The highest accuracy is shown below:

![image](https://user-images.githubusercontent.com/90878901/152909996-3389bdd1-aa5f-4aa0-b64c-8c246e559f27.png)

## Summary. 
This was a challenging code. Unfortunately the goal of 75% was not achieved. Adding additional features to the learning model, additional epochs and additional combinations of hidden layers would be best next steps. 

