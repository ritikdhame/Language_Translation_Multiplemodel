# English_to_Hindi_NMT_Encoder_Decoder_Model

# Objective
This project aims to build a hindi to english language traslation model based on Encoder-Decoder Architecture 

# About the data
The code requires the following dataset from : https://www.kaggle.com/datasets/aiswaryaramachandran/hindienglish-corpora
The dataset contains : 127,607 sentences of English to Hindi from sources tides, ted and indic2012    
![image](https://github.com/ritikdhame/Language_Translation_Multiplemodel/assets/7029092/c5376a7d-f1fb-4c6d-990f-89e8a6515963)

# Methodology
The code consists of 4 main parts:
- Data loading and exploration: invloves loading the data from Kaggle, checking the split of data sources
- Preprocessing: Involves getting rid on null, NAN, duplicates,quotes, special charecters, numbers followed by reshaping, lower casing 
- Model building : Post tokenizing using tensorflow to build encoder with LSTM model followed by Decoder with LSTM model and a adding a dense layer with softmax activation.
- Training and prediction : using rmsprop(adapts the learning rate during training to speed up convergence and handle different gradients effectively) as optimizer and  categorical_crossentropy as loss function Accuracy as model perfomance metric, follwed by fitting the model, saving wieghts and making predictions.

![image](https://github.com/ritikdhame/Language_Translation_Multiplemodel/assets/7029092/9b9ed56c-4986-41e0-baf9-9218d0471472)
![image](https://github.com/ritikdhame/Language_Translation_Multiplemodel/assets/7029092/add51878-e896-4d60-9077-bbb388016bee)
![image](https://github.com/ritikdhame/Language_Translation_Multiplemodel/assets/7029092/205128b3-9391-4e73-8da9-391ae655f4ed)

#  Requirements
To run the code, you need to install the following libraries:
- matplotlib
- digits
- Scikitlearn
- keras
- Pandas
- Tensorflow

# Algorithm 
- Encoder - LSTM model 
- Decoder- LSTM model
- Dense layer - Softmax

# Procedure
You can install them using pip or conda commands.
To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and view the text and explore the data 
3. Define the layers of the Encoder-Decoder model
4. Building and fitting the model with tf package
5. Predicting the response in Hindi


The code is commented and documented for better understanding and readability.
