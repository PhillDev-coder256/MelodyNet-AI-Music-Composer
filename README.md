# MelodyNet: AI Music Composer

## Description
MelodyNet is a Python-based machine learning project that generates music using LSTM (Long Short-Term Memory) networks. The project leverages MIDI data from the LoFi genre to train a neural network, which can then generate new musical sequences based on the patterns learned from the dataset.

This repository includes code for:

- **Data Preparation:** Loading and processing MIDI files into a sequence of notes and chords.
- **Model Training:** Configuring and training an LSTM network to predict musical sequences.
- **Music Generation:** Using the trained model to generate new music and convert it back to MIDI format.
- **Evaluation:** Analyzing the output and improving the model through various techniques.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
  - [Install Dependencies](#install-dependencies)
- [Data Preparation](#data-preparation)
  - [Loading MIDI Files](#loading-midi-files)
  - [Processing Notes and Chords](#processing-notes-and-chords)
  - [Saving and Loading Processed Data](#saving-and-loading-processed-data)
- [Model Training](#model-training)
  - [Preparing Sequences](#preparing-sequences)
  - [Building the LSTM Model](#building-the-lstm-model)
  - [Training the Model](#training-the-model)
- [Music Generation](#music-generation)
  - [Generating Notes](#generating-notes)
  - [Creating MIDI Files](#creating-midi-files)
- [Evaluation and Fine-Tuning](#evaluation-and-fine-tuning)
  - [Optional: Weight Analysis](#optional-weight-analysis)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction
Ever wondered how to create music with Python and Machine Learning? MelodyNet provides a practical implementation of AI-generated music by training a sequence model on MIDI files from the LoFi genre. The model learns patterns and generates new musical sequences that can be converted back into MIDI for playback.

Data Preparation
Loading MIDI Files
Load your MIDI files into the project directory and specify the path in the script.

Processing Notes and Chords
Convert the MIDI files into a list of sequences of notes and chords using the music21 library.

Saving and Loading Processed Data
Use pickle to save and load processed data for future runs.

Model Training
Preparing Sequences
Transform the list of notes into sequences suitable for the LSTM model.

Building the LSTM Model
Define and compile the LSTM model for music generation.

Training the Model
Train the model on the prepared sequences and save the weights.

Music Generation
Generating Notes
Generate a sequence of notes using the trained model.

Creating MIDI Files
Convert the generated notes back into a MIDI file using music21.

Evaluation and Fine-Tuning
Analyze the model's performance and adjust parameters as needed to improve results.

Optional: Weight Analysis
Evaluate predictions from different saved weights to assess model performance.

Contributing
Feel free to contribute to the project by submitting pull requests or opening issues.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to the Holy Spirit for inspiration and guidance on generating music with machine learning.

## Setup

### Clone the Repository

```bash
mkdir MelodyNet
git clone https://github.com/PhillDev-coder256/MelodyNet-AI-Music-Composer.git
cd MelodyNet```

print('Happy Hacking.....')
