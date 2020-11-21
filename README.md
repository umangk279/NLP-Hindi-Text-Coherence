# NLP-Hindi-Text-Coherence

This repository contains code for CS565 course project on Text Coherence Analysis for Hindi Language.

The code is organized as Data, ExternalDependencies, Preprocessing, RawData, Scrapers and CNNCohenrenceModel python Notebook.

Step by step description is as follows:

Scrapers folder contains the python notebook for scraping DD news articles. the scraped news articles are stored in RawData Folder. RawData also contains the wikipedia articles downloaded from Kaggle(https://www.kaggle.com/disisbig/hindi-wikipedia-articles-55k).

Preprocessing folder contains 'coherent_incoherent_creator' python notebook. Using this notebook, coherent and incoherent data is created and stored in Data folder in folders DD and Wiki. Preprocessing folder also contains 'corpus_analysis' notebook which is used to analyze the data set generated. This folder also contains 'dataset_creator' notebook which generated the 'dataset_balanced' or 'dataset_unbalaced' csv file contained in Data folder which contains labelled data which will be used for training.

ExternalDependencies folder contains indic nlp resources required for tokenization and other operations on Hindi data. We have used pre-trained fasttext embeddings. Embeddings file can be generated using 'embeddings_generator' notebook in this folder.

Finally, 'CNN Coherence Model' is the notebook used for training the model using the generated dataset csv and embeddings file.

Note: Some paths might need to be changed as the training was done using Google Colab Notebooks.

Results and detailed architecture of the CNN model can be seen in the enclosed report.

Embeddings file and dataset_unbalanced.csv can be found at: \
https://drive.google.com/file/d/15lUv7NHuhL4scl5Tryc-RUHJ4FxnLPR7/view?usp=sharing \
https://drive.google.com/file/d/162SYasCMZra7_3ekyodQSzxIeoLUddVA/view?usp=sharing
