# Sheet Music Transcription Using Machine Learning

## Overview 

This project was inspired by the problem of wanting to learn piano pieces that you hear without needing to buy sheet music. We used machine learning to convert audio files into the corresponding sheet music. The model we are using is a classifier using transfer learning based on the [ResNet-18](https://pytorch.org/hub/pytorch_vision_resnet/) model and was trained on approximately 10,000 inputs. Data for training and testing was collected from [Mutopia](https://www.mutopiaproject.org/), a free online library of sheet music.

## Technologies

- librosa 0.8.0
- matplotlib 3.2.2
- pretty_midi 0.2.9
- Pillow 7.1.2
- pydub 0.25.1
- PyTorch 1.9.0
- scipy 1.4.1
- selenium 3.141.0

## Usage 

To use this application you must download the website code from the google drive link provided and run the website locally. More detailed instructions are available in [this](https://youtu.be/JYp1YV_NHOM?t=603) video from 10:03 to 11:40. Please also note that the audio input must be a .m4a file.

## Contributors

- Andre Correia
- Harman Sihota
- Juliana Choi
