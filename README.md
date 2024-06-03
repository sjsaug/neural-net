## Digit Recognizer Neural Net

### About
Neural Network made using ONLY Linear Algebra + Numpy.
<br/>Uses the Digit Recognizer dataset (https://www.kaggle.com/competitions/digit-recognizer).
<br/>Trains a Neural Network to recognize digits.

### Usage
1. Make sure the following dependancies are installed with `pip install` :
    - numpy
    - pandas
    - matplotlib
2. Specify your desired training iterations and alpha (default is **(1000, 0.001)**).
    - *NOTE : Recommended to only change iterations. Higher iterations will equal higher accuracy*.
3. To start training, run `python3 main.py` in your project directory.
4. Done! Project will auto test after training is complete.


### Contribution Opportunities
Here are just a few things that can be contributed to improve the project :
1. Configuration Support : Add config system that can retrieve data such as iteration amount & alpha from a desired config file, loaded on start.
2. Separate Training & Testing : Add option to choose between training the model and testing it.
