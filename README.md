# anlp_rbert
Entity Relation Extraction using R-BERT




In the google colab notebook, entity relations are extracted from medical data about diseases.
Bert is customized for the task, using methods from the following paper:

Enriching Pre-trained Language Model with Entity Information for Relation Classification https://arxiv.org/abs/1905.08284.

The code for the implementation was borrowed from: https://github.com/wang-h/bert-relation-classification

This custom R-Bert model is then fine tuned for our data and used to predict what kind of relationships hold between entities in our test set.


Data: https://www.kaggle.com/kmader/figure-eight-medical-sentence-summary


