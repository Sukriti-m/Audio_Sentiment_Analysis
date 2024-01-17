# Audio_Sentiment_Analysis
This project aims to determine the emotions from an audio input directly through speech. Mel-frequency cepstral coefficients (MFCC) characteristic is determined using the feature extraction process. 

It involves the creation of a Long Short-Term Memory (LSTM) model. LSTMs are a type of recurrent neural network (RNN) well-suited for sequence-based tasks, making them ideal for capturing the temporal dynamics of speech signals. It has one LSTM layer comprising 256 units, dropout layers
(20% rate) for regularization, and densely connected layers for final classification. Compiled the model
using categorical cross-entropy loss and the Adam optimizer, enabling
automatic learning rate adjustment. Trained the model over 50 epochs
with a batch size of 64, closely monitoring its performance.

The 7 emotions that this project can determine are given below:
1. Anger
2. Disgust
3. Fear,
4. Happiness
5. Pleasant surprise
6. Sadness
7. Neutral
   
**Kaggle Link:** https://www.kaggle.com/code/sukritima/audio-sentiment-analysis

## Dataset Used
**Toronto emotional speech set (TESS):**
A set of
200 target words were spoken in the carrier phrase "Say the word _' by
two actresses (aged 26 and 64 years) and recordings were made of the set
portraying each of seven emotions. There are 2800 data points (audio
files) in total.

**Link:** https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

## Libraries
1. tensorflow
2.  librosa
3.  pandas
4.  matplotlib
5.  keras

## Model Used
LSTM (Long short-term memory) Model

## Future Scope
To enhance the audio emotion detector tailored to
amplify the capabilities of mental health support hotlines. This strategic
shift underscores a commitment to precision and effectiveness in
leveraging technology to automatically assess the emotional states of
callers. By enhancing the mental health support hotline experience, this
project aims to empower operators with timely insights, enabling them to
offer more empathetic and targeted assistance.

![Screenshot 2023-12-13 220137](https://github.com/Sukriti-m/Audio_Sentiment_Analysis/assets/93239528/4143262d-88b9-4e29-8dc3-cd3ca976c78e)
