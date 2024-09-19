# Document Analysis using OpenShift AI and Azure
The objective of this demo is to showcase how OpenShift AI and Azure components can be effectively integrated to implement a GenAI use case for document classification and analysis. By following the step-by-step guide, users will learn how to deploy an Azure Red Hat OpenShift (ARO) cluster, configure AI resources, and utilize Azure AI services like OpenAI and Microsoft Entra ID. This demo highlights the seamless collaboration between OpenShift AI’s orchestration capabilities and Azure's powerful AI tools to create a scalable and secure solution for real-world AI applications.

Involving - 
1. Data Exploration - Explore data used in this repo.
2. Get Embeddings - Generate embeddings from documents using gpt-35-turbo.
3. Classify Documents - Use gpt-35-turbo to classify documents into different categories.

## BBC News Articles Analysis
This project is a data analysis of the BBC news dataset. The goal of this project is to explore the data and classify documents into categories.

## Dataset
The dataset used in this project is the BBC News Archive available from kaggle. It contains 2225 articles from the BBC news website with 5 different categories: business, entertainment, politics, sport and tech. Each article has a category, filename, title and text.

## Language Model
Examples in this repo uses gpt-35-turbo.

## Notebooks
This project consists of notebooks that perform the following tasks:

00-explore-data.ipynb - This notebook explores the data by looking at the distribution of classes, number of words per document, etc.

01-get-embeddings.ipynb - This notebook uses pre-trained word embeddings to create vector representations for each document.

02-classify-documents.ipynb - This notebook builds classification models using gpt-35-turbo to classify each document and to predict the class of each document.

## References
OpenAI repo: https://github.com/openai/openai-cookbook/

Azure Document Analysis reference repository - https://github.com/Azure/azure-openai-samples/tree/main/use_cases/archive/document_analysis
