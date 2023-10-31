---
title: Module 1.5
permalink: /module1/module1_aws/module1-5/
parent: module1_aws
order: 5
---

# Module 1.5 - Integrate Virtual Agent with NeuralSeek

## Integrate 
Navigate to the “Integrate” tab in NeuralSeek.

![image1.5.1](images/image1.5.1.png)

## Select Virtual Agent
Select choice of virtual agent on left side menu.
For this lab, we recommend "**LexV2 Lambda**".

![image1.5.2](images/image1.5.2.png)

## Download File
Download the Lambda Archive .zip file.

![image1.5.3](images/image1.5.3.png)

## Create a Function
Click the link to open the Functions page on the AWS Lambda console to create a function from scratch.
- **(a)** Select "Create Function".
- **(b)** Add a “Function Name”. For this lab, we recommend “learning-lab”.
- **(c)** Click “Create Function”.

![image1.5.4](images/image1.5.4.png)

![image1.5.5](images/image1.5.5.png)

## Upload File
Navigate to the Code Source pane in the AWS Lambda Function console. 
- **(a)** Click “Upload from”. Click “.zip file”.
- **(b)** Click “Upload” to select your Lambda Archive .zip file.
- **(c)** Click “Save”.

![image1.5.6](images/image1.5.6.png)

![image1.5.7](images/image1.5.7.png)

## Add API Key and Instance URL
On the NeuralSeek "Integrate" page, copy the provided API key and Instance URL.
Navigate to the Code Source pane in the AWS Lambda Function console. 
- **(a)** Click on the “index.mjs” file tab. 
- **(b)** Enter the copied API key and Instance URL into the code block:
{% raw %}
```
const neuralSeekURL = “enter url here” ; 
const apikey = “enter api key here” ; 
```
{% endraw %}
- The "Deploy" button will enable. Click "Deploy" to succesfully update the function.

![image1.5.8](images/image1.5.8.png)

## Update Timeout Setting
Navigate to "Configuration" tab in AWS Lambda Function Console.
- **(a)** In the "General Configuration" pane, click "Edit".
- **(b)** Update under “Timeout”: set min to be “1” and sec to be “0”.
- **(c)** Click "Save".

![image1.5.9](images/image1.5.9.png)

![image1.5.10](images/image1.5.10.png)

For detailed information on creating a LexV2 Lambda bot from scratch, refer to the documentation [here.]({{site.baseurl}}{% link module1_aws/module1-5/module1-5.md %}) 

## Assign Alias 
Open the [Amazon Lex console.](https://console.aws.amazon.com/lexv2/home#bots) From the list of bots, choose the name of the bot that you want to use.
- **(a)** On the left side bar menu, under “Deployment”, click “Aliases”.
- **(b)** From the list of alias names, choose the alias name that you want to use. For this lab, we recommend “TestBotAlias”

![images1.5.11](images/image1.5.11.png)

## Select Lanaguage
Open the [Amazon Lex console.](https://console.aws.amazon.com/lexv2/home#bots) From the list of bots, choose the name of the bot that you want to use. 
- **(a)** On the left side bar menu, click the “Languages” tab.
From the list of supported languages, click the language that the Lambda function is used for. For this lab, we recommend “English”.

## Optional Lambda Function Connection
Choose the name of the Lambda function to use, then choose the version or alias of the function. For this lab, we recommend “MyNeuralSeek”. Then, click “Save”.

## Fallback Activities
The default FallbackIntent allows for the Lambda function to be called when it is detected. To activate this intent, navigate to Amazon Lex in AWS Console
- **(a)** Click “MyNeuralSeek.”
- **(b)** Click “Intents” under “English (US)” on the left sidebar menu.
- **(c)** Click on the “FallbackIntent” link.

Under the "Fullfillment" section, click the "Activate" icon to turn on. 
- **(a)** Click "Advanced Options"
- **(b)** Select the “Use a Lambda Function for Fulfillment” option. 
- **(c)** Click "Update Options."
- **(d)** Click "Save Intent."

Build the chatbot and test the FallbackIntent routine with a question. For the purpose of this lab, we used "Why is the sky blue?". 
- **(a)** Click “Build.” This step may take a few moments.
- **(b)** Click “Test.” The Amazon Lex chatbot will be generated. 
- **(c)** Prompt the chatbot with a question. For the purpose of this lab, we used “Why is the sky blue?.”
