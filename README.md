![](_images/AI_Fraud_Logo.png)


# Fraud_Bot

About

This project utilizes a “Chat-Bot” to interact with the user (customer of a bank). The user reports a fraud transaction that occurred on his/her account. The Bot will then provide a recommendation/solution for the user to take. The banking institution will collect the data generated from users input to forecast and identify future fraudulent transactions. 

---

## Technologies

Project was developed using the following technologies, programming languages, libraries

Programs: 

* [Visual Studio](https://visualstudio.microsoft.com/) - Platform used to build code.

* [AWS Lambda](htts://aws.amazon.com/lambda/) - For building the function for the bot.


Language: Python


Libraries:

* [pandas](https://pandas.pydata.org/docs) - To build manupulate DataFrames.

* [tensorflow](https://www.tensorflow.org/) - The core open source library to help you develop and train ML models.

* [pydotplus](https://pypi.org/project/pydotplus/) - Provides a Python Interface to Graphviz’s Dot language.

* [pathlib](https://pypi.org/project/pathlib/) - Pathlib offers a set of classes to handle filesystem paths.

* [scikit-learn](https://scikit-learn.org/stable/) - Tools for predictive data analysis.

* [imblearn](https://imbalanced-learn.org/stable/) - Provides tools when dealing with classification with imbalanced classes.

* [IPython](https://ipython.org/) - Python programming language, that offers introspection, rich media, shell syntax, tab completion, and history.

* [Matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

Load libaries to the terminal as listed below:

```
import pandas as pd
import tensorflow as tf
import pydotplus
from pathlib import Path
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.svm import SVC
from sklearn.metrics import classification_report
from sklearn.ensemble import RandomForestClassifier
from imblearn.ensemble import BalancedRandomForestClassifier
from IPython.display import Image
%matplotlib inline
```

---

## Installation Guide

### For Chatbot: 
The platform used to operate the bot was AWS Lambda. You will need to follow the next step to acces AWS Lambda and the code.

1. Open the AWS Lambda Console
2. Sign in to the AWS Management Console with the administrator IAM user
3. Type Lambda on the Services search box.
4. In the resulting Services list, click Lambda this will open the AWS Lambda console.

The corresponding code is located in the _chat_bot folder,


### For Credit Card Fraud Prediction Model: 
The platform used to create and run the code was Visual Studio.
(https://visualstudio.microsoft.com/)

Once the program installed on your computer, open the file located in the predicting_fraud_transactions folder and run the code.


---

## Examples

The following is an example of how the program works.




---

## Contributors

Alissa Bolla, Andrew Mckay andArturo Garcidueñas

---

## License

MIT
