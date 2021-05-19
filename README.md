# Welcome 👋

### HERE ARE ALL THE NOTES TAKEN FROM THE GOOGLE MACHINE LEARNING CRASH COURSE THAT YOU CAN FIND [here](https://developers.google.com/machine-learning/crash-course)

The ML changes how you write an algorithm, it changes the common way to write a long code, to just write a simpler code with lots of examples

# [Framing](https://developers.google.com/machine-learning/crash-course/framing/ml-terminology)

Supervised Machine Learning:

-   The ML system learn how to combine an input and produce useful predictions on newer datas
-   We use **labels**, where labels are the variables that we want to predict (represented by _y_)
-   We also use **features**, where features are the variables that describes our data (represented by _x_{x1, x2, x3...})
-   A **model** is examples to predic labels

## Regression vs Classification

-   In regression, the ml model will predict continuous values like (0, 100, 200, 10000, ...)
-   In classification, the ml model will predict concrete data, like (dog, paper, true or false, ...)

# [Descending into ML](https://developers.google.com/machine-learning/crash-course/descending-into-ml/linear-regression)

-   Lots of complex ways to learn from data
-   Training a model, means learning good values for all the weights and the bias from label examples.
-   In supervised learning, the ml algorithm builds a model that attempt to find a model that minimizes the loss. (**Empirical Risk Minimization**)
-   The loss is the penality for bad predictions. That is, **loss** is a number that indicates how bad the model is on a single example.
    -   Perfect prediction: loss = 0
    -   Otherwise: loss > 0
-   The goal here, is to find a set of weights and biases that have the lowest loss (closer to 0).
    ![Loss Graph](./README-imgs/LossGraph.png "Loss Graph")
