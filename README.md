# Domain adaptation of Large Language Models for Sparse Information Retrieval
This repository contains the code of our Final Project for the "Information Retrieval" course at Radboud University, Data Science Master. In this project, we tried to improve the performance of the existing NN-based retrieval approach on the dataset from a specific domain by first finetuning the backbone LLM on the data from the same domain. We integrated our finetuned model into the DeepCT framework and then assessed the performance on both in-domain and out-of-domain data.

![alt text](https://github.com/jeka-e/InformationRetrival/blob/main/scheme_IR_bigger.png)

We managed to achieve a considerable improvement of the scores in comparison to the results presented in [BEIR Benchmark]([www.google.com](https://github.com/beir-cellar/beir))

All the code except the last part of the evaluation can be directly done using the notebooks.

## Evaluation
The evaluation cannot be done completely in the notebook setup because it needs Docker. Therefore, for the last step it is necessary to setup Docker and evaluate the results on your own machine.
