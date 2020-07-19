##Step 1: Converting images to text

#For this I used funtion which i made for my previous project #github_link="https://github.com/Ashutosh1520/Answer_checker/blob/master/Answer_checker.ipynb".
#In this I used os library to access folders.
#Tesseract to convert images to text. 
#Tesseract is an optical character recognition engine for various operating systems.
 
##Step 2: Getting datasets and Tokenizing data to feed to neural net

#The dataset i used is from:  https://www.kaggle.com/kazanova/sentiment140
#This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api .
#The tweets have been annotated (0 = negative, 4 = positive) and they can #be used to detect sentiment .

#This data is stored in training_cleaned.csv

##Step 3: Getting embeddings

#The embeddings that i used for transfer learn are from the GloVe, also known as Global Vectors for Word Representation, available at: https://nlp.stanford.edu/projects/glove/
#GloVe is an unsupervised learning algorithm for obtaining vector representations for words. Training is performed on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space.

#This is stored in glove.6B.100d.txt

##Step 4: Creating, compiling and fitting data to NeuralNet using Tensorflow library

#My neuralnet consist of 5 layers:
1. InputLayer
2. Covolution Layer
3. Pooling Layer
4. LSTM
5. Dense- Output layer

##Step 5: Plotting graphs

1. Training and Validation accuracy per epoch

2. Train and Validation loss per epoch 

##Step 6: Predicting Outputs

#For this we will apply model.predict() on the data values

##Step 7: reading data from CSV and Writing submission to CSV file

#I extracted data from Test.csv then dropped category column and then coverted to python list.
#Then creating lists to put in CSV file.
#Finally writing data to my_submission2.csv





















