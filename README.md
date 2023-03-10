# Customer-Churn-Prediction-Using-Artificial-Neural-Network
Customer churn is the rate at which customers quit a company. Churn prediction predicts if consumers will leave an organisation. Hence, if a client subscribes to a service, we must assess the chance of cancellation.Many organisations depend on it since getting new customers is more expensive than keeping old ones. Customer churn measures why and how customers leave the firm.

The dataset consists of 7043 rows and 21 columns, where rows represent the number of customers in the dataset and the columns represent each customer’s attribute. The attributes are used to predict the churn of a particular customer.

TensorFlow and Keras were used for artificial neural nets.
The sequential model has one input layer with all 19 columns as input, two hidden layers with 15, 10 hidden neurons, and a RelU activation function. Our final layer, the output layer, uses the sigmoid activation function since our output is 1 and 0.
