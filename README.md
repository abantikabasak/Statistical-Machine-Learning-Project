# Statistical Machine Learning Project
 CSE 575 Music Genre Recognition
 
 					Read Me!
Music-Genre-Recognition-GTZAN
A Machine Learning project to predict the genre of the specific song snippet.
Problem:
Given a segment of a song, the task is to classify the genre of the song into one of these classes:
Blues
Classical
Country
Disco
HipHop
Jazz
Metal
Pop
Reggae
Rock
Dataset:
GTZAN Genre Collection: The dataset consists of 1000 audio tracks each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.
Link: GTZAN_Dataset
Dataset Splitting:
The original GTZAN dataset contains 1k 30-seconds .wav files.
Each class has 100 30-seconds snippets from songs
Used 90% of the data for training (900 sample).
Used 10% for testing (100 sample)
Each class has the same number of samples in training and testing (90 and 10 respectively)
Preprocessing:
Extracted features using:
Mel Spectrogram
Used Librosa library for feature extraction Link: Librosa_features
Training Methods & Results:
CNN+CNNLSTM :
Go to the CNN+CNNLSTM folder.
Run the Mel Spectrogram Image Generation Code.py. This generates the mel spectrogram images for every audio file.
Upload the mel spectrogram images directly to google drive.
Then, execute CNN+CNNLSTM.ipynb on Google Colab.













