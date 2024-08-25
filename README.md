Emotion Recognition Project
Overview
This project focuses on emotion recognition using machine learning techniques. The goal is to classify emotions based on input data audio in WAV or MP4 format. The project explores various models and methods to achieve high accuracy in emotion detection.

Project Structure
Notebook: Contains the code for training and evaluating the emotion recognition model.
Scripts: Modularized scripts for data preprocessing, model training, and evaluation.
Results: Outputs like accuracy plots, confusion matrices, and model predictions.
Data: Includes or links to the dataset used for training and testing.
Environment: List of dependencies and instructions for setting up the environment.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Ritvik-Girish/SpeechEmotionRecognition.git
cd SpeechEmotionRecognition

Set up a virtual environment (optional but recommended):
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required packages:
bash
Copy code
pip install -r requirements.txt

Or if using Conda:
bash
Copy code
conda env create -f environment.yml
conda activate emotion-recognition

Usage
Download the dataset from GoogleDrive(https://drive.google.com/drive/folders/1ytSAgn3qXb9wMbKngSuhhZB2NKl6MjpW?usp=sharing) and place it in the DataSets/ directory.

Open the Jupyter Notebook:
bash
Copy code
jupyter notebook emotion_recognition.ipynb
Follow the instructions in the notebook to run the code and train the model.
Check the results/ folder for the outputs.

Dataset
The dataset used for this project consists of audio. It includes pre-recorded audio files which are categorised based on the voice actors and the emotion.
Source: [The Google Drive Link :](https://drive.google.com/drive/folders/1ytSAgn3qXb9wMbKngSuhhZB2NKl6MjpW?usp=sharing)]

Results
Accuracy: [66%]
