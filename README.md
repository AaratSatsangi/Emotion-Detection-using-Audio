# EMOTION DETECTION USING AUDIO

### OVERVIEW:

In this project, I show the superiority of a Deep Learning model consisting of a Convolutional Neural Network (CNN) and a Multi Layer Perceptron (MLP)
over another model consisting of a Long Short Term Memory Network (LSTM) and a Multi Layer Perceptron on the problem of Emotion Detection with Audio data.
Even though CNNs were only made to be used on images, we found that CNN-MLP works comparatively better than LSTM-MLP.
In this project I used the Mel-Frequency Cepstrum Coefficients (MFCCs) to reduce the number of features to a good extent 
and capture the timbre of the audio data and sent these coefficients as a representation of the audio clip into the Neural Networks for training and testing. 

### DATASETS USED:
1. Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)
2. Crowd Sourced Emotional Multimodal Actors Dataset (CREMA-D)
3. Surrey Audio-Visual Expressed Emotion (SAVEE)  
4. Toronto emotional speech set (TESS)

### RESULT:

The CNN-MLP model achieved 71% accuracy and the LSTM-MLP model achieved 66% accuracy on the testing set. 
