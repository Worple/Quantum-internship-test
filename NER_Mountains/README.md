NER problem for mountains

This folder contains my solution to the NER problem for mountain entities. The solution utilizes a pre-trained BERT model from the Transformer library, a small dataset created with ChatGPT and augmented using simple techniques (detailed in the accompanying notebook), and a small portion of the Kaggle NER dataset. The model was fine-tuned on the mentioned dataset, achieving high scores for the NER problem: 
precision: 0.98, recall: 0.98, f1-score: 0.98, support: 692. 

The weights can be downloaded from https://huggingface.co/Worpl/BERT-finetuned-ner-mountains/tree/main.

The demo in this repo includes details of the model's architecture and training process. To run it locally, you will also need the dataset_mountains_NER.csv file in the same folder and must satisfy the requirements listed in requirements.txt.

The repository also contains a Python script (.py) for model training (dataset_mountains_NER.csv is required in the same folder) and a Python script (.py) for model inference.

The notebook named 'dataset_creation-fin.ipynb' provides a detailed explanation of the dataset creation process.