# Common ML steps
Underneath is a list of common steps that we can consider implementing in our work. Feel free to add useful links and notes in the relevant chapters, or add completely new chapters :)

## Import data

## Parse and combine data
- Make a Pandas DataFrame
- Can possibly be a part of the previous step

## Data Cleaning
- Fill missing values
- Handle "bad data"

## Exploratory Data Analysis

## Feature Engineering
- Log-transform
- Signal-analysis (derivatives, Fourier transform, power, etc)
- Temporal features (day, month, holiday, etc)
- Sequencing
- Onehhot encoding of categorical features

## Split data into train-validate-test
- NB! Time-series data should normally _not_ be split randomly!

## Scaling
- Normalization using StandardScaler og MinMaxScaler
- Depends on the model

## Train Model
- Autoencoder with LSTM RNN
- [Isolation Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)

## Cross Validation
- [Special methods for time-series data](https://medium.com/@soumyachess1496/cross-validation-in-time-series-566ae4981ce4)

## Hyperparameter tuning
- [Sklearn](https://scikit-learn.org/stable/modules/grid_search.html)
- [Nevergrad](https://facebookresearch.github.io/nevergrad/)
- [Keras Tuner](https://www.tensorflow.org/tutorials/keras/keras_tuner)

## Predict and score
- Good metrics for temporal data?
- Depends on competition metric

## Model explanation
- Explainable model ([interpretml](https://github.com/interpretml/interpret))
- Certainty score
- [LIME](https://github.com/marcotcr/lime)
- [SHAP](https://github.com/slundberg/shap)

## Deployment
- Pipeline for deploying model
- Host model in e.g. Azure
