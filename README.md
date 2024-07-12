# Low-resource-SER

This repository contains code to reproduce the results from my thesis on _Speech Emotion Recognition for low-Resource Languages_.

| Contents                                     | Notebook                                                                                                                                                                                                            |
|------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Main results notebook | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18DiGSut_kUQjf5N97L0oElmXZ-ag0lAG?usp=sharing) |
| Fine-tuning wav2vec 2.0 for Danish SER | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18DiGSut_kUQjf5N97L0oElmXZ-ag0lAG?usp=sharing)   |

The first notebook contains the main results from my three research questions. The Emo-DB, Urdu, and AESDD datasets are loaded from Google Drive, however, DES and EmoTale are not released for public use. Dimensional labels and Features extracted from all five datasets are loaded into the notebook to reproduce the most important plots and results tables. In RQ1, the function to train an SVC with LOSO cross-validation was adapted from [w2v2-how-to
/notebook.ipynb](https://github.com/audeering/w2v2-how-to/blob/main/notebook.ipynb).

The second notebook contains the code for fine-tuning a pre-trained wav2vec 2.0 model for Danish SER. The code was adapted from [Emotion_recognition_in_Greek_speech_using_Wav2Vec2.ipynb](https://github.com/m3hrdadfi/soxan/blob/main/notebooks/Emotion_recognition_in_Greek_speech_using_Wav2Vec2.ipynb).
