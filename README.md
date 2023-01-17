# Tweet_emotion_recognition

Objective:
  Emotions are expressed in nuanced ways, which varies by collective or individual experiences, knowledge, and beliefs. Therefore, to understand emotion, as conveyed through text, a robust mechanism capable of capturing and modeling different linguistic nuances and phenomena is needed. 
  
Dataset:https://github.com/dair-ai/emotion_dataset

Data preproccesing:
  1)Tokenizer
  2)Padding and Truncating Sequence
  3)Preparing the labels
  
Model used:
  Recurrent Neural Network(RNN), got an accuracy of 89%
    1)Model consist of 4 layers(1 i/p,2 hidden,1 o/p)
    2)It has 2 hidden LSTM layers
