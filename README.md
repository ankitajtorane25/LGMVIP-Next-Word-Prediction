# LGMVIP-Next-Word-Prediction

Task 4: Next Word Prediction

(Advance Level)

Most of the keyboards on smartphones give next word prediction features; google also uses next word prediction based on our browsing history. So a preloaded data is also stored in the keyboard function of our smartphones to predict the next word correctly. In this task, I trained a Deep Learning model for next word prediction using Python. And for that purpose, I used the Tensorflow and Keras library in Python.

STEPS

1) Import all required libraries.

2) Load the downloaded provided dataset

3) Split the dataset into each word in order, but without the presence of some special characters.


4) Perform the feature engineering, For this purpose, create a dictionary with each word in the data within the list of unique words as the key,
And it’s significant portions as value.


5) Define a Word length, which will represent the number of previous words that will determine our next word.
I will define Prev words to keep five previous words, and their corresponding next words in the list of the next words.


6) Create two NUMPY arrays x for storing the features and y for storing its corresponding label. x and y will iterate if the word is available so that the corresponding position becomes 1


7) Look at a single sequence of words.


8) Build Recurrent Neural network using LSTM model, which is a very powerful RNN.


9) Train the next word prediction model with 20 epochs.


10) Save this model for future use.


11) Look at how our model is behaving based on its accuracy and loss changes while training.

![image](https://user-images.githubusercontent.com/77010675/144002313-80ff596b-8b92-460a-ae33-08c88322c5c7.png)     


![image](https://user-images.githubusercontent.com/77010675/144002351-621130ce-9b86-4446-925c-b959ed4adb52.png)




12) Build a python program or functions to predict the next word using training model.


14) Declare some sequence of quotes that is used as a base for predictions.


16) Finally, use the model to predict the next word.



![image](https://user-images.githubusercontent.com/77010675/144002602-f5f456e0-dbb7-4e24-8a45-3d0a61448154.png)


  
  As you can see Figure the sequence “attitude is a little thing that makes a big difference” is generated with the WORD_LENGTH of 5 after which next predicted words are given as: [‘and’, ‘said’, ‘to’, ‘in’, ‘for’]. This repeats for every sequence declared previously
  
  
Github: https://github.com/HadiqaMaqsood2000/LGMVIP-DataScience/tree/main/Next%20Word%20Prediction%20TASK_3

