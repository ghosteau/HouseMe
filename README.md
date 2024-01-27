I will try to be brief about the current capabilities of this model and why I did certain things with it.

Right now, the model is being fed data from the California market specifically, and there is a reason why I wanted to start with this. California's housing market is notoriously very polarized and complex, and getting a machine learning model to predict the median house value based on different metrics is a great first step for this model.
The California housing market median house value has a standard deviation of around 115395.6 dollars, which is very high and ultimately makes this hard to predict, but it's a challenge this model is actively attempting to predict. The model is currently within one standard deviation of predicting house cost in California based on the mean absolute error
output we have observed. We've got ourselves a start folks.

This model is currently made in R with a Python environment (using Keras), but expect it to be transferred to Python eventually. I am just currently more confident with R in terms of deep learning, hence my choice of R. 

Thanks for reading, much love.
