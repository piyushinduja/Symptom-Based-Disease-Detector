# Symptom-Based Disease Detection
This repository contains a natural language processing (NLP) project aimed at detecting a person's condition or disease based on their described symptoms. The project involves two different models for multiclass classification: LSTM and BERT.

## Models Used
### LSTM Model
Embedding: GloVe embeddings

Architecture: Long Short-Term Memory (LSTM)

### BERT Model
Tokenizer: BERT Tokenizer

Model: BERT Mini

## Model Evaluation
The models were evaluated using different batch sizes (32 and 64) and learning rates (0.1, 0.01, 0.001, 0.0001). The best results were achieved with a batch size of 64 and a learning rate of 0.001.

## Results on Batch size 64 and learning rate 0.001 (best ones)
![git_drug_results](https://github.com/piyushinduja/Symptom-Based-Disease-Detector/assets/74929365/552359d8-d45c-4d6e-b052-2e59e9f19319)

Maximum Label Accuracy: 0.0022 (indicating that the most occurring label does not overfit the model)

## Links
BERT Mini: [Link](https://huggingface.co/prajjwal1/bert-mini)

Dataset: [Link](https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018)

## Conclusion
This project demonstrates the application of NLP techniques in healthcare for preliminary diagnosis based on symptom descriptions. The use of both LSTM and BERT models provides insights into the performance of different architectures and embeddings in this domain.
