# English_to_Hindi_NMT_Encoder_Decoder_Model_with_attention

# Objective
This project aims to build a hindi to english language traslation model based on Encoder-Decoder Architecture with attention 

# About the data
The code requires the following dataset from : https://www.kaggle.com/datasets/aiswaryaramachandran/hindienglish-corpora
The dataset contains : 127,607 sentences of English to Hindi from sources tides, ted and indic2012    

# Methodology
The code consists of 3 main parts:
- Data loading and exploration: invloves loading the data from Kaggle, checking the split of data sources
- Preprocessing: Involves getting rid on null, NAN, duplicates,quotes, special charecters, numbers followed by reshaping, lower casing 
- Model building and training: Post tokenizing using tensorflow to build encoder with GRU model followed by Decoder with GRU model and a atention layer with softmax activation.
- Training and prediction : using rmsprop(adapts the learning rate during training to speed up convergence and handle different gradients effectively) as optimizer and  Gradienta as loss function Accuracy as model perfomance metric, follwed by fitting the model, saving wieghts and making predictions.


#  Requirements
To run the code, you need to install the following libraries:
- matplotlib
- digits
- Scikitlearn
- keras
- Pandas, Numpy, digits, time
- Tensorflow

# Algorithm 
- Encoder - GRU model 
- Decoder- GRU model
- Attention model

# Procedure
You can install them using pip or conda commands.
To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and view the text and explore the data 
3. Define the layers of the Encoder-Decoder model with Attention layer
4. Building and fitting the model with tf package
5. Predicting the response in Hindi


The code is commented and documented for better understanding and readability.