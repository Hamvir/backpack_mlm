# Backpack - MLM
This the project repo of backpack_mlm. Here we want to train the backpack model using MLM and compare the results of the both in a variety of task including a downstream task.
We have the following ipynb files that test the various aspects of our idea. Till now we have reproduced the baselines and tested the lm model on one downstream task:
1. Control
2. Verb similarity
3. Sense vectors
4. Downstream task (sentiment analysis and question answering)
## Control
We have testes the control the sense vector has on the model. For further info refer the file named control.ipynb in corresponding model folder
## Verb similarity
We have tested how the backpack models performs on 2 datasets. For datasets refer similarity_dataset folder and for code refer verb_similarity.ipynb in corresponding model folder
## Sense vectors
We have also tested what a particular sense vector represents for a word. For further info refer the ipynb file sense_vectors.ipynb in corresponding model folder
## Downstream task
We also found accuracy and f1-score on a downstream task (sentiment analysis). For more information refer Task1_sentiment_analysis.ipynb file
