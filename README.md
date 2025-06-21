# Covid-19 Binary classification training model using MobileNetV2 

## Prerequisites

``Python v3.11.7``

``Pip v21.2.4``

## Core technologies used:

TensorFlow/Keras - Primary ML framework

HDF5 - Efficient Data storage format

NumPy - Numerical computing and array operations

Pandas - Data manipulation

OpenCV - Image preprocessing 

PIL - Image loading and basic processing

scikit-learn - ML utilities and metrics

Matplotlib - Plotting and visualisation

Seaborn - Statistical data visualisation

Tabulate - Pretty table formatting

## Information

Please run all code blocks in order, this will ensure that all dependencies are installed.

Please note before training the model the training data wil need to generated locally by running the appropriate code block in the Jupyter notebook

This will generate a ``covid_19_training_data.h5`` file which can then be used to train the model.

Training time is approx. 3-4 hrs (based when running on a Apple Mac Airbook with 8Mb CPU Ram).

When training is complete this will generate a keras file in the format:

``covid_19_classifier_[timestamp].keras``