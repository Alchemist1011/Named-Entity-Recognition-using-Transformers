# Named Entity Recognition using Transformers

### Introduction
Named Entity Recognition (NER) is the process of identifying named entities in text. Example of named entities are: "Person", "Location", "Organization", "Dates" etc. NER is essentially a token classification task where every token is classified into one or more predetermined categories.  
In this exercise, we will train a simple Transformer based model to perform NER. We will be using the data from CoNLL 2003 shared task. For more information about the dataset, please visit the dataset website. However, since obtaining this data requires an additional step of getting a free license, we will be using HuggingFace's datasets library which contains a processed version of this dataset.

### Model
Transformer-based architecture  
Pre-trained model: DistilBERT

### Future Enhancements
Experiment with different pre-trained models: Try using other pre-trained models like BERT, RoBERTa, or XLNet to compare performance.  
Custom entity recognition: Add support for custom entity types and train the model on a specific domain.  
Active learning: Implement active learning strategies to selectively annotate samples for better performance.  
Real-time NER: Develop a real-time NER system using this model and integrate it with applications.  
Multilingual support: Extend the model to support multiple languages and evaluate its performance.
