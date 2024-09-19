# Document Analysis using OpenShift AI and Azure
The objective of this demo is to showcase how OpenShift AI and Azure components can be effectively integrated to implement a GenAI use case for document classification and analysis. By following the step-by-step guide, users will learn how to deploy an Azure Red Hat OpenShift (ARO) cluster and configure AI resources. This demo highlights the seamless collaboration between OpenShift AI’s orchestration capabilities and Azure's powerful AI tools to create a scalable and secure solution for real-world AI applications.

Involving - 
1. Data Exploration - Explore data used in this repo.
2. Get Embeddings - Generate embeddings from documents using DISTILBERT model deployed on Openshift AI (https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english).
3. Classify Documents - Use DISTILBERT to classify documents into different categories.
4. Extract Key Information - Identify key information in documents using DISTILBERT.
5. Extract Key Words - Extract important words from documents using DISTILBERT.

## BBC News Articles Analysis
This project is a data analysis of the BBC news dataset. The goal of this project is to explore the data and classify documents into categories.

## Dataset
The dataset used in this project is the BBC News Archive available from kaggle. It contains 2225 articles from the BBC news website with 5 different categories: business, entertainment, politics, sport and tech. Each article has a category, filename, title and text.

## Language Model
Examples in this repo uses DISTILBERT model (https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english) which is deployed on Openshift AI.

## Notebooks
This project consists of notebooks that perform the following tasks:

[00-explore-data.ipynb](https://github.com/RHEcosystemAppEng/genai-document-analysis/blob/main/notebooks/00-explore-data.ipynb) - This notebook explores the data by looking at the distribution of classes, number of words per document, etc.

[01-get-embeddings.ipynb](https://github.com/RHEcosystemAppEng/genai-document-analysis/blob/main/notebooks/01-get-embeddings.ipynb) - This notebook uses pre-trained word embeddings to create vector representations for each document.

[02-classify-documents.ipynb](https://github.com/RHEcosystemAppEng/genai-document-analysis/blob/main/notebooks/02-classify-documents.ipynb) - This notebook builds classification models using DISTILBERT to classify each document and to predict the class of each document.

[03-extract-key-information.ipynb](https://github.com/RHEcosystemAppEng/genai-document-analysis/blob/main/notebooks/03-extract-key-information.ipynb) - This notebook extracts key information from each document such as people, organizations, locations, etc.

[04-extract-key-words.ipynb](https://github.com/RHEcosystemAppEng/genai-document-analysis/blob/main/notebooks/04-extract-key-words.ipynb) - This notebook extracts important keywords from each document.

## Documentation to deploy the demo
https://docs.google.com/document/d/17KSADGvrNx64LAp1hmvejmkrabDA2XcMvhFXc23MVHU/edit?usp=sharing

## References
OpenAI repo: https://github.com/openai/openai-cookbook/

Azure Document Analysis reference repository - https://github.com/Azure/azure-openai-samples/tree/main/use_cases/archive/document_analysis
