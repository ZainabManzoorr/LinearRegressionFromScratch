)#LinearRegressionFromScratch
1. Understand the Linear Regression Model
   -Linear regression predicts a target 𝑦 as a linear combination of features:
  y = w1x1 + w2x2 + ... wnxn

where:
w: Weights (parameters) to be learned.
b: Bias term.
x: Input features.
The goal is to minimize the error between the predicted y' and the actual y.
2. Define the Dataset
3. Implement the Hypothesis
   The hypothesis (or model) for linear regression is:
    y' = w⋅x+b
4. Define the Loss Function
Use Mean Squared Error (MSE) as the loss function:

MSE= 1/N ∑(y'-y)^2

5. Implement Gradient Descent
Gradient Descent is used to minimize the loss by updating w and 𝑏:
w←w−α . ∂Loss/∂w
b←b−α ⋅ ∂Loss/∂b

The gradients:

∂Loss/∂w = 2/N ∑ (y'-y).xi
∂Loss/∂b = 2/N ∑ (y'-y).xi

6. Train the Model
Combine everything to iteratively update 𝑤 and b
7. Evaluate the Model
Test the model on new data and visualize results




​
  




  

​
  


