# Audio-Emotion-Detection
In this project, I tried to detect the emotion of a wave voice using feature extraction techniques, MFCC in particular. MFCC stands for Mel-frequency cepstral coefficients. <a href="https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio">Here is the link to MFCCs' Wikipedia page</a>.
Before starting the project, I search for a dataset and found the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) dataset. This dataset contains a number of voice files that are emotionally labeled. There are eight different classes in the dataset; however, I just picked samples from two categories. Accordingly, samples show either a happy or sad emotion. 
During the project, I extracted 128 features from every voice file using the MFCC technique and then employed a lightGBM model to classify the available data. The model achieved an accuracy of 81 in classifying wave files based on their emotion.


