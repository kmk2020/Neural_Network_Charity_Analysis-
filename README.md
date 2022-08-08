# Neural_Network_Charity_Analysis-

![image](https://user-images.githubusercontent.com/89704371/182719427-17936567-9374-47b5-b6b0-d0b35d8e892d.png)

# Overview of the project

Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

## Deliverables

1. Deliverable 1: Preprocessing Data for a Neural Network Model
2. Deliverable 2: Compile, Train, and Evaluate the Model
3. Deliverable 3: Optimize the Model
4. Deliverable 4: A Written Report on the Analysis README.md

### DELIVERABLE RESULTS:
#### Data Preprocessing
For this analysis and model, the target is held in IS_SUCCESSFUL field.

![image](https://user-images.githubusercontent.com/89704371/183323261-bd3ef6a8-1419-41f9-ac7a-ea4c2367dad9.png)


The following variable(s) should be considered on features model
* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE

The following variable(s) should be removed from input and data.
* NAME
* EIN

![image](https://user-images.githubusercontent.com/89704371/183323141-56dc04fa-576f-4d75-b4f1-45819fe06124.png)


## Compiling, Training, and Evaluating the Model
Model Configuration:

* hidden_nodes_layer1 = 80
* hidden_nodes_layer2 = 30
* number_input_features = 43
* This model acheived 63.8% accuracy with several attempts to incraese the accuracy including:
* Increasing the number of hidden nodes in layer 1 (3 X number of input features)
* Increasing the number of hidden layers to include a 3rd
* Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer

![image](https://user-images.githubusercontent.com/89704371/183323472-49459f3f-d01b-4487-bab4-57884b8d5c31.png)


## SUMMARY
Our Analysis and Deep Learning Model Results include a recommendation for how a different model could solve this classification and results.

