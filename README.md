# Module 13 - Venture Funding with Deep Learning
 
As a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.


### Technology used

import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

### Usage 

The process includes by preprocessing the data features and target as X and y set,  Train the model, fit, compile, evaluate and optimize model. To optimize the model to improve the model's accuracy used different methods on Model 1 and Model 2

original model has 2 hidden layers and epochs=100
Model 1 - increasing the nodes to hidden layer and epochs=50
Model 2 - increasing the hidden layers to 3 and epochs=20

## Contributors
Madhuri