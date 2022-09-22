# Venture Funding with Deep Learning

This application pulls data from the file applicants_data.csv from the resource folder and uses TensorFlow and Keras to build, fit, and evaluate a deel neural network model. The model aims to use 9 features to predict whether or not a venture will become successful.

---

## Technologies

Using Python 3.7

* [pandas](https://github.com/google/pandas) - For data analysis

* [Scikit-Learn](https://github.com/scikit-learn) - For data analysis using train_test_split, StandardScaler, and OneHotEncoder

* [Tensorflow](https://github.com/tensorflow/tensorflow) - For building, fitting and evaluating deep neural network models. Also includes the Keras package to assist.

---

## Installation Guide

```python
  pip install pandas
  pip install -U scikit-learn
  pip install tensorflow
```

---

## Usage

Upload data of the venture applicant's application type, affiliation, classification, use_case, organization, status, income amount, special considerations, and asking amount for the model to fit and evaluate 3 different neural network models. The first using 2 hidden layers, the second using 1 hidden layer, and the third using 3 hidden layers. Depending on the complexity of the data, 1 may be a better fit than others. In the data used to develop this program, it was found that relu may not be the best activation, and that further testing needs to be done. With 2 hidden layers, and sequentially half as many neurons, the accuracy was 73.3%. However, when removing a layer and using 2/3 neurons of number of features, the accuracy was only 72.9%. The aforementioned models also only ran 50 epochs, maybe one could've excelled with more epochs. The third model was more thorough, with 3 hidden layers and sequentially 4/5 as many neurons as input features and 200 epochs; however, the accuracy went down again to just under 72.9%. Thus, better models probably exist, and further development is needed.

---

## Contributors

Sole Contributor - Josh Thompkins

---

## License

Everyone is free to view and work with this project, you may not alter text unless given explicit permission.
