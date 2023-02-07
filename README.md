# EMOTION DETECTION USING AUDIO

## OVERVIEW

This project aims to show the superiority of a Deep Learning model consisting of a Convolutional Neural Network (CNN) and a Multi Layer Perceptron (MLP)
over another model consisting of a Long Short Term Memory Network (LSTM) and a Multi Layer Perceptron on the problem of Emotion Detection with Audio data.
Even though CNNs were only made to be used on images, it was found that CNN-MLP works comparatively better than LSTM-MLP.
In this project, Mel-Frequency Cepstrum Coefficients (MFCCs) were used to reduce the number of features to a good extent 
and capture the timbre of the audio data and sent these coefficients as a representation of the audio clip into the Neural Networks for training and testing. 

## DATASETS USED
1. Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)
2. Crowd Sourced Emotional Multimodal Actors Dataset (CREMA-D)
3. Surrey Audio-Visual Expressed Emotion (SAVEE)  
4. Toronto emotional speech set (TESS)

## Model Architectures
<p align="center">
<img width="300" height="300" src="https://user-images.githubusercontent.com/56449109/217324306-102f4847-6b90-400a-b7f1-8a6ac3fa336e.png">  
<img width="300" height="300" src="https://user-images.githubusercontent.com/56449109/217324332-76e461c5-c0ae-481f-a0b5-7cd1fb1852ee.png">
<br>LSTM-MLP and CNN-MLP 
</p> 
<br>

## RESULT
The CNN-MLP model achieved 71% accuracy and the LSTM-MLP model achieved 66% accuracy on the testing set. The theoretical explanation of this project is described in this 
<a href="https://drive.google.com/file/d/19TJEjdsp3Q4wlNVs8R6CJurg89uqgywo/view?usp=sharing">paper</a> authored by me.
