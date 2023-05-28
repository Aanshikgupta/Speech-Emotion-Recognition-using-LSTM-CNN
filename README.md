# Speech-Emotion-Recognition-using-LSTM-CNN

This project is an implementation of a Speech Emotion Recognition system using Python, Jupyter Notebook, and Anaconda. The goal of this project is to analyze speech recordings and classify them into different emotional states such as happiness, sadness, anger, etc.

## Table of Contents

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)

## Overview

Speech Emotion Recognition (SER) is a field of study that focuses on recognizing the emotional state of a speaker from their speech recordings. This project uses machine learning techniques to build a SER system. The system takes an audio file as input and predicts the corresponding emotional state.

## Dependencies

To run this project, you need to have the following dependencies installed:

- Python (version 3.6 or later)
- Jupyter Notebook
- Anaconda

The necessary Python libraries and packages will be installed during the installation process.

## Installation

1. Clone this repository to your local machine: [https://github.com/Aanshikgupta/Speech-Emotion-Recognition-using-LSTM-CNN](https://github.com/Aanshikgupta/Speech-Emotion-Recognition-using-LSTM-CNN)

2. Navigate to the project directory:
*cd speech-emotion-recognition*
3. Create a new Anaconda environment:
*conda create --name ser-env python=3.8*
4. Activate the environment:
*conda activate ser-env*

5. Install the required dependencies:
- tensorflow==2.6.0
- keras==2.6.0
- librosa==0.8.1
- numpy==1.21.4
- pandas==1.3.5
- matplotlib==3.5.1
- scikit-learn==0.24.2
- soundfile==0.10.3.post1
- pydub==0.25.1
- pyaudio==0.2.11

6. Launch Jupyter Notebook: 
 *jupyter notebook*


7. Open the `speech-emotion-recognition.ipynb` file in your browser.

## Dataset

This project uses the following datasets :
- [EMO-DB](http://emodb.bilderbar.info/docu/)
- [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)
- [RAVDESS](https://zenodo.org/record/1188976#.YZOQPmBBxPY)
- [CREMA-D](https://paperswithcode.com/dataset/crema-d)
- [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/Download.html)

Datasets are provided with this project if you don't want to download directly.

## Usage

1. Make sure you have activated the Anaconda environment: *conda activate ser-env*

2. Open the `speech-emotion-recognition.ipynb` Jupyter Notebook file.

3. Follow the instructions in the notebook to preprocess the dataset, train the SER model, and evaluate its performance.

4. You can also use the trained model to predict the emotional state of new speech recordings.

## Results
- A HTML file is provided with this project to see the result including the whole program flow with comments.
- After training the model on the above dataset, the performance of the SER system is evaluated using various metrics such as accuracy, precision, etc. The results are presented in the Jupyter Notebook.

---




