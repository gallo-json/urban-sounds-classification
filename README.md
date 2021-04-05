# Urban Sounds Classification

## Date

Final project for the Machine Learning and AI ID tech camp.

## High Level Overview

There are 8732 .wav files of 10 different urban sounds like dog barks, car horns, gun shots, etc. The dataset is divided in 10 folds (folders) to make the train and test easier. I used fold 1-9 to train the model, and fold 10 to test it. A custom CNN is used to classify the sounds.

The sound features used in the CNN are:

- MFCC: Mel-frequency cepstral coefficients that use a quasi-logarithmic spaced frequency scale, which is more similar to how the human auditory system processes sounds.
- Melspectrogram: Compute a Mel-scaled power spectrogram. Based on human ear.
- chroma-stft: Compute a chromagram from a waveform or power spectrogram. Uses pitches.
- chroma_cq: Constant-Q chromogram. Uses pitches.
- chroma_cens: Chroma Energy Normalized CENS. Uses pitches.

## Tech Stack

- Python 3
- Keras
- Pandas
- Librosa

## Results

Test accuracy: 70%

Validation accurarcy: 90%

## Reflection

As seen in the above results, the model is clearly overfitting. See more in my [reflection](docs/Reflection.md) on this project.

## Useful Links

[Dataset](https://urbansounddataset.weebly.com/urbansound8k.html)

[Vlog I used as reference and inspiration](http://aqibsaeed.github.io/2016-09-03-urban-sound-classification-part-1/)