# deep-learning-challenge
###### Alphabet Soup Foundation Funding Outcome Predictor using hyper-tuned Neural Networks.


## Report on the Neural Network Model

## 1. *Overview*
With the attached tool - Neural network, Alphabet Soup Foundation can predict, which applicants would be able to fund thier ventures and have a higher rate of success.  The tool will create a binary classification from the given data set and will predict whether the applicants will be successful if funded by Alphabet Soup Foundation.  

## 2. *Results*
- **Data Processing**

Target Variable for the model:

<sub>IS_SUCCESSFUL</sub>

Feature Variables for the model:

<sub>APPLICATION_TYPE</sub>

<sub>AFFILIATION</sub>

<sub>CLASSIFICATION</sub>

<sub>USE_CASE</sub>

<sub>RGANIZATION</sub>

<sub>TATUS</sub>

<sub>INCOME_AMT</sub>

<sub>SPECIAL_CONSIDERATIONS</sub>

<sub>ASK_AMT</sub>

- **Compiling, Training, and Evaluating the Model**

f hidden layers - 80, 30 neurons split and node feature was 43. First Layer - 80 (this is almost double the input feature). 
With an hidden layer activation function of relu as this our go to for first model.
Output node is 1 as it was binary classifier model with only one output: was the funding application succesfull yes or no. And an output layer activation of sigmoid as the model output is binary classification between 0 and 1.
Then hidden layers were increased to 3 and set the third hidden layer at 30 as the model prediction accuracy was below 75%:
![Screenshot 2023-01-11 212912](https://user-images.githubusercontent.com/110227464/211783279-b22940e5-e5f5-4641-b19a-dd7f2c5ccef8.png)


## 3. *Summary* ##
*The final optimized neural network trained model from the keras tuner method achieved 80% prediction accuracy with a 0.45 loss, using a sigmoid activation function with input node of 76; 5 hidden layers at a 16, 21, 26, 11, 21, neurons split and 50 training epochs. Performing better than the non automized model. Keeping the Name column was crucial in achieving and and going beyond the target. This shows the importance of the shape of your datasets before you preprocess it.*
