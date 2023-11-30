NER problem for mountains

This folder contains my solution for NER problem for mountain entities.
The solution uses pre-trained BERT model from Transformer library, small dataset created with chatGPT and augmented using some simple techniks (more on that in according notebook) and tiny part of Kaggle NER dataset.
The model was fine-tuned on mentioned dataset, achieving high scores on NER problem:
precision:0.98    recall:0.98  f1-score:0.98   support:692
The weights can be downloaded from https://huggingface.co/Worpl/BERT-finetuned-ner-mountains/tree/main

The demo is accessible in this repo contains details of model architecture and how it was trained. To run it locally you also need to have dataset_mountains_NER.csv in the same folder and satisfy requirements from requirements.txt

The repo also contains Python script (.py) for model training (you also need to have dataset_mountains_NER.csv in tha same folder) and Python script (.py) for model inference. 

Notebook named "dataset_creation-fin.ipynb" contains detailed explanation of the process of the dataset creation.