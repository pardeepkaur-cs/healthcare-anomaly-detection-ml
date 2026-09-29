# Healthcare Authentication Anomaly Detection

## Overview

This project explores suspicious login activity in a simulated healthcare environment.

The goal is to see how information such as login time, device, location, and download volume can be used to identify login activity that may need further review.

The dataset is simulated and does not contain real patient information.

## Approach

The project includes:

- Login behaviour analysis
- Data preparation
- Machine learning classification
- Simple risk scoring
- Example suspicious login detection
- Data visualization

## Machine Learning Model

A Decision Tree Classifier is used as a simple example of supervised machine learning for classifying login activity.

## Technologies

- Python
- Pandas
- Scikit-learn
- Google Colab

## Example

A login at an unusual time, using an unfamiliar device, or involving a large download may be considered a situation that requires further review.

## Limitations

This is a small proof-of-concept project using simulated data and example labels.

The project does not represent a real healthcare security system and does not establish real-world detection performance.

A larger dataset and more detailed evaluation would be needed for further research.

## Future Work

Possible future work could include:

- Larger datasets
- More login behaviour features
- Comparison of different machine learning methods
- More detailed anomaly detection
- Testing with realistic security scenarios
