# Introduction
 
Depression is now prevalent among people and depression is a concern because people who are going through depression are unaware of their condition. Due to this there is a delay in diagnosis which leads to a delay in treatment. So, it would be feasible if people can periodically examine themselves from their homes. There are some initiatives where a bot will ask questions and record the answers. Idea is to create models to evaluate the person and caution him/her about their state. This is to explore state of the art models and understand how it behaves on different hyper parameters.
 
Machine learning and natural language processing (NLP) techniques have shown promise in detecting depression from text data, such as social media posts, online forums, and clinical notes. In this project, we aim to develop a deep learning model to detect depression from multi modal data, using a dataset of clinical interviews from the DIAC-WOZ dataset. Specifically, we will explore the use of a neural network (CNN, LSTM) to classify the interviews as either positive for depression or negative for depression. The goal of this project is to demonstrate the potential of machine learning techniques for detecting depression from data, and to provide insights into the most important features and factors that contribute to accurate classification. The results of this project could have significant implications for the early detection and treatment of depression and could help to improve the quality of life for individuals affected by this disorder.
 
# Dataset Files 
 
Dataset is available in the drive , uploaded here - https://drive.google.com/drive/folders/1yMtZcL9tv5-g9XZdsJmB9N4eOOg-_sXx?usp=sharing . The .ipynb files in the repo should work if run in google colab with the dataset folder being accessible. The word dictionary used for LSTM model is available here - https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?resourcekey=0-wjGZdNAUop6WykTtMip30g . The dataset was never downloaded locally due to it's large size and other computational limitations. Thus the dataset has not been added to the submitted file.
 
# Files :  
    Data_Preprocessing.ipynb - Data preprocessing
    Depression_Detection_CNN_Text_Analysis.ipynb - CNN model based on text data
    Depression_Detection_CNN_Audio_Analysis.ipynb - CNN model based on audio data
    Depression_Detection_LSTM_Word_Level.ipynb - LSTM model based on text (words)
    Depression_Detection_LSTM_Sentence_Level.ipynb - LSTM model based on text and audio data (sentence level)
    Depression_Detection_Transformer.ipynb - Transformer model on text data
    
    
