
## Introduction

Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries


## Installations

Importing libraries

Python

Jupyter notebook (label: good first issue)

Jupyter interactive notebook

Pandas (label: good first issue) Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data. Frame objects, statistical functions, and much more.

numpy (label: good first issue)

pip install numpy
It is the core library for scientific computing, which contains a powerful n-dimensional array object.

Tensorflow is a Deep learning library for Python.

pip install Tensorflow





## Running the project

1. Ensure that you are in the project home directory. Create the machine learning model by running below command
python model.py

This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
python app.py

If everything goes well, you should be able to see the predcited salary vaule on the HTML page!

3. You can also send direct POST requests to FLask API using Python's inbuilt request module Run the below command to send the request with some pre-popuated values
python request.py
## Conclusion


 
In this project we learned to deploy simple flask deployment project.