# Speech-Recognition

Repozitorij tima Speech-Recognition (Petra, Petra, Karmen, Siniša)

[TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge#description)

# Projekt - pokretanje 

Dataset downloadati sa sljedece stranice: https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data

Train dataset raspakirati unutar data/raw/train/audio a test dataset unutar data/raw/test/audio.

U libs/classification se nalaze sve skripte za treniranje.

U notebooks se nalaze skripte LSTM L.ipynb za treniranje modela i Predict.ipynb za testiranje. Skripte možemo redom izvršavati u Jupyter bilježnici.
Nakon izvršavanja Predict.ipynb u mapi predictions/lstm_prediction se nalazi prediction.csv datoteka sa predviđenim oznakama. 

Svaka skripta može se pokrenuti i sa ./script/execute_notebook.py u scripts/execute_notebook.py gdje je script ime skripte.

U mapi analiza dataseta nalazi se notebook koji istražuje i vizualizira dataset i neke metode za odabir značajki.

# Potrebno:

Tensorflow 1.4

librosa

scikit-learn

Python 3.x

# Dataset

Warden P. Speech Commands: A public dataset for single-word speech recognition, 2017. Available from [http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz]

[http://download.tensorflow.org/data/speech_commands_v0.02.tar.gz]

