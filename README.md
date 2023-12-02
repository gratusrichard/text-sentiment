# Sentiment Analysis Model Generation

This Jupyter Notebook provides the code for training a sentiment analysis model using a SimpleRNN with Keras.

## Overview

The sentiment analysis model is trained on the IMDb dataset, a popular dataset for binary sentiment classification.

## Files

- `sentiment_analysis_model.ipynb`: Jupyter Notebook containing the code for training the sentiment analysis model using Keras.
- `model.h5`: Pre-trained sentiment analysis model saved in HDF5 format.

## Usage

### Running the Notebook

1. Open the `sentiment_analysis_model.ipynb` notebook.

2. Run the cells sequentially to train the sentiment analysis model.

3. The pre-trained model will be saved as `model.h5`.

## Model Details

- **Architecture:** SimpleRNN
- **Input:** Word sequences from the IMDb dataset
- **Output:** Binary sentiment prediction (Positive/Negative)

## Dependencies

Make sure to install the required dependencies before running the notebook:

```bash
pip install -r requirements.txt
```

##Images 
![image](https://github.com/gratusrichard/text-sentiment/assets/78464961/3e69583a-8427-4e2c-a0a9-bbbda32ab0c8)

### License
This project is licensed under the MIT License.
