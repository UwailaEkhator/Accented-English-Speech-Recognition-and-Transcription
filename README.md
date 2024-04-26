# Accented-English-Speech-Recognition-and-Transcription

## About The Project
The aim of this project is to evaluate the performance of two Automatic Speech Recognition Models: Whisper and Speech2Text, on various accents, and then fine-tune these models to see if that improves their performance on selected accents.

## Contributors
- Tapiwa Mwila
- Sharadha Kasiviswanathan
- Uwaila Ekhator


## Built With
- Hugging Face
- Python programming language
- Whisper ASR model
- Speech2Text ASR model

## Requirements
- Install datasets
- Install torch
- Install transformers
- Import openai-whisper
- Import WhisperProcessor
- Import WhisperTokenizer
- Import evaluate
- Import WhisperForConditionalGeneration
- Import Seq2SeqTrainingArguments
- Import Seq2SeqTrainer
- Import Jiwer
- Import Pipeline
- Import Librosa
- Import Speech2TextProcessor
- Import Speech2TextForConditionalGeneration

## Datasets
- The Speech Accent Archive dataset available on [Kaggle](https://www.kaggle.com/datasets/rtatman/speech-accent-archive?select=speakers_all.csv)
- The Mozilla Common Voice, the version we used is available on [Kaggle](https://www.kaggle.com/datasets/mozillaorg/common-voice/data)

## Description of each Notebook
- Performance Analysis of Whisper & Speech2Text models.ipynb: This notebook contains the code for the evaluation of the Whisper and Speech2text models on the Speech Accent Archive dataset. It includes visualizations of our results that indicate how each of the models performed on 102 native languages.
- Finetuning Whisper on Philippines Accent.ipynb: This notebook further illustrates the Whisper finetuning process on the Philippines accents from the Common Voice dataset and compares the performance of our Finetuned model against the original Whisper model.
- Finetuning Whisper on Indian Accent.ipynb: This notebook further illustrates the Whisper finetuning process on the Indian accents from the Common Voice dataset and compares the performance of our Finetuned model against the original Whisper model.

A step-by-step finetuning guide is available here [link](https://huggingface.co/blog/fine-tune-whisper#fine-tune-whisper-for-multilingual-asr-with-%EF%BF%BD%EF%BF%BD-transformers).

## Acknowledgements
We would like to acknowledge George Mason University's Speech Accent Archive (Link) from where we obtained our initial dataset and Mozilla Common Voice where we obtained our Indian and Philippines Accents fine-tuning datasets. Additionally, we extend our thanks to all the contributors, libraries, datasets, and tools that were instrumental in the success of this project.









