# BERT-XLNet-Irony
Evalution of Fine-tuning BERT and XLNet on Irony Detecion in English Tweets

For the task description, check two things:
1. [explanation on CodaLab](https://competitions.codalab.org/competitions/17468)
2. [SemEval-2018 Task 3: Irony Detection in English Tweets](https://www.aclweb.org/anthology/S18-1005/)


Check the papar DEIM2020_ZHANG_G1_4.pdf for detail explanantions.


## 1. Environment
```
python3.6
jupyterlab==1.2.4
matplotlib==3.1.1
nltk==3.4.5
numpy==1.17.4
pandas==0.25.3
scikit-learn==0.22
scipy==1.3.2
torch==1.1.0s
torchvision==0.3.0
transformers==2.3.0
```

## 2. Data Preprocessing
After setting the environment, we should process the tweets for training. Just run the `data_preprocess.ipynb` to get the `normalized_sents.pickle`

## 3. Word Embedding method
Check the `embedding_method` for details.

## 3. Fine-tuning method
Check the `finetuning_method` for details.
