# SpeechRecognition
SpeechRecognition


# How to train a an Audio model:
Note that we have already, made train and test json files. They include key-value pair representing the address of audio file as the key and the Speech2text version of audio file as the value. 

Run the following to train:

my paths : /Users/book/Desktop/WORK/AI/Pytorch-step-by-step/A-Hackers-AI-Voice-Assistant/VoiceAssistant/speechrecognition/scripts/train.json

/Users/book/Desktop/WORK/AI/Pytorch-step-by-step/A-Hackers-AI-Voice-Assistant/VoiceAssistant/speechrecognition/scripts/test.json

use your own paths for the two argument.

python3 train.py --train_file path/to/train.json --valid_file path/to/test.json --save_model_path path/to/save
