### NewsPulse: Stock Trend Predictor 

This project leverages the power of BERT (Bidirectional Encoder Representations from Transformers) for predicting stock price direction based on news articles and viral tweets. The model is fine-tuned to classify whether stock prices will go up or down, using a combination of Natural Language Processing (NLP) techniques and financial datasets.

### Features
- BERT Model: Fine-tuned for stock price movement prediction.
- NLP Techniques: Utilizes tokenization and feature extraction (TF-IDF, Word2Vec).
- Performance: Achieved ~72.5% accuracy in prediction.

### CODE
1. ``` trainer.py ``` contains the train helper function for the BERT.
2. ``` summary.py ``` contains the code to summarize the text.
3. ``` plot.py ``` contains code to get plots for BERT
4. ``` model.py ``` contains the code for defining the model architecture
5. ``` inference.py ``` contains the code for running the inference engine for BERT
6. ``` main.py ``` contains the base code for BERT
7. ``` bert_preprocess.py ``` contains code to pre-process the text for BERT

### Steps to run the project
1. Open the file main.py
2. To run the main.py file use the command ``` python main.py --data_dir <dataset-dir> --model <model_name> --token_len <token_length> --folds <K_fold>```
