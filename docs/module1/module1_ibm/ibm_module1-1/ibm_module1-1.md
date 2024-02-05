---
title: 1.1 - Setup NeuralSeek
permalink: /module1/module1_ibm/ibm_module1-1/
parent: module1_ibm
order: 1
---

# Module 1.1 - Setup NeuralSeek

## Add NeuralSeek

Log in to [IBM Cloud](https://cloud.ibm.com/login?cm_sp=ibmdev-_-developer-_-trial&_gl=1*1odtrhw*_ga*NTM2NzU0MTk0LjE2OTY1MjE4NDQ.*_ga_FYECCCS21D*MTY5Njg2NzU0Ni41LjEuMTY5Njg2ODg5OS4wLjAuMA..). Search and select [NeuralSeek](https://cloud.ibm.com/catalog/services/neuralseek?cm_sp=ibmdev-_-developer-_-trial) from Catalog. 
- **(a)** Select the **Pay-per-answer** plan type. 
- **(b)** To agree to the third-party terms, in the bottom right, open and read the terms then check, “I have read and agree to the following third-party terms”. 
- **(c)** To provision, click “Create”.

> Please note that users are responsible for all incurred costs.

![image1.1.1](images/image1.1.1_updated.png)

## Launch NeuralSeek

Click “Launch NeuralSeek”.

![image1.1.2](images/image1.1.2.png)

## Basics - Getting Started

Complete required form. 
- **(a)** Enter the company name or organization display name.
- **(b)** Select output language. For the purpose of this lab we recommend English. 
- **(c)** Start training NeuralSeek AI by checking the purpose of the virtual agent. Choose “Internal” or “External”.
- **(d)** Click “Next”.

  ![image1.1.3](images/image1.1.3.png)

## Data - Connect to your KnowledgeBase

- **(a)** Select KnowledgeBase. In this example “watsonx Discovery”.
- **(b)** Select language. In this example "English".
- **(c)** Enter the watsonx Discovery Endpoint URL, Private API Key, and Index name. In this example, use the credentials provided by your instructor. 
- **(d)** Click “Next”. If this is your first time setting up NeuralSeek you will be prompted to complete the Curation Tour at this time.

![image1.1.4](images/image1.1.4_updated.png)

## Organize - Outputs and Categories
### Categorization
Categorize your intents for easier reporting and management. 

> If following the live lab, skip this step! 

- **(a)** Click the light bulb icon to add a new row. 
- **(b)** Enter in a unique category name, a corresponding URL, and a detailed description of the category with intents that do not match any other category.

![image](images/ibm_002.png)

### Virtual Agent Framework
- **(a)** Select "Virtual Agent Type" from the drop down menu. In this example, select "**Watson Assistant Actions**".

- **(b)** Select preferred choice of enabling or disabling embedding links into returned responses. In this example, select "**Disable**". 

![image](images/ibm_001.png)

Click "Next" to save reported categories and selected Virtual Agent. 

## Tune - Tune for your Data

Let's tune NeuralSeek for your data.

- **(a)** Select preferred option for "Which of these looks more like your data?". For this example, select "**Important phrases are surrounded by many lines of text that explain them.**". 
    - The option "*Important phrases are surrounded by many lines of text that explain them*", describes data with more elaborate explanations with more extensive passages of text for a better understanding.  
    - The option "*Important phrases are surrounded by only a line or two of relevant information*", describes data with concise coverage of key phrases with just a line or two of necessary context. 
- **(b)** Select preferred option that best describes your data requirements. For this example, select "**I want give lots of information to the LLM, and give it leeway to decide the answer.**"
- **(c)** Select preferred option that best describes your data currency. For this example, select "**All of my documents are current and relevant.**". 
    - The option "*All of my documents are current and relevant*", describes data that is up-to-date.
    - The option "*I have lots of old documents or blog posts, some with conflicting information. I need NeuralSeek to help with date prioritization*", describes data that may have there are conflicting or irrelevant details across different sources or documents.

Click "Next" to save reported tuning configurations. 

![image](images/aws_007.png)

## Ready

NeuralSeek is ready to seek.

![image1.1.7](images/aws_008.png)

> NeuralSeek is now set up and ready to use. 