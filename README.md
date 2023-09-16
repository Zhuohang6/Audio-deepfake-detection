# Audio Deepfake Detect

A machine learning project exploring basic methods to detect audio deepfakes.


## About

Audio deepfakes, AI-generated fake audio recordings. This project will be exploring the effectiveness of machine learning models, specifically neural networks and support vector machines, in detecting these audio deepfakes. A part of this exploration is the comparison of input features: Mel Frequency Cepstral Coefficients (MFCC) and log-mel spectrogram, to understand their impact on the detection models.


### Datasets

This project uses the following datasets:

- **ASVspoof 2019 LA Dataset**: A comprehensive dataset that captures various spoofing attacks.
- **ASVspoof 2017 Dataset**: An earlier version providing mainly replay attacks.

## Prerequisites

- Python 3.8+
- Libraries: 
  - torchaudio
  - numpy
  - matplotlib
  - librosa
  - torch
  - scikit-learn
  - scipy

### Installation

Clone the repository:
```bash
git clone https://github.com/Zhuohang6/Audio-deepfake-detection.git

Install the required packages:
pip install -r requirements.txt

