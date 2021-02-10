# Mechanism of Actions (MoA) prediction
*By Océane Salmeron, Nathan Lancman, Charles Mabbyalas, Baptise Lafay (ING5, BDA 2)*

## Project

This project was done for this [kaggle competition](https://www.kaggle.com/c/lish-moa).

**How do we determine the MoAs of a new drug?**

One approach is to treat a sample of human cells with the drug and then analyze the cellular responses with algorithms that search for similarity to known patterns in large genomic databases, such as libraries of gene expression or cell viability patterns of drugs with known MoAs.

In this competition, you will have access to a unique dataset that combines gene expression and cell viability data. The data is based on a new technology that measures simultaneously (within the same samples) human cells’ responses to drugs in a pool of 100 different cell types (thus solving the problem of identifying ex-ante, which cell types are better suited for a given drug). In addition, you will have access to MoA annotations for more than 5,000 drugs in this dataset.

As is customary, the dataset has been split into testing and training subsets. Hence, your task is to use the training dataset to develop an algorithm that automatically labels each case in the test set as one or more MoA classes. Note that since drugs can have multiple MoA annotations, the task is formally a multi-label classification problem.

**Data**

Data was provided by the competition. You can access it [here](https://www.kaggle.com/c/lish-moa/data)
