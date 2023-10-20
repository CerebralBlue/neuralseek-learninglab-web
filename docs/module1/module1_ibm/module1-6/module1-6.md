---
title: Module 1.6
permalink: /module1/module1_ibm/module1-6/
parent: module1_ibm
order: 6
---

# Module 1.6: Change Default to Generative AI Responses

## Generative AI Reponses
Setup a NeuralSeek call action to use have generative AI respond to all queries, even questions not listed in Watsonx Assistant. 

* (a) On the left menu, select “Actions”.
* (b) Under All items, select “Set by assistant”.
* (c) Select “No action matches”.
  
*No action matches are cases when a user asks a question not listed in IBM Watsonx Assistant predefined responses*.

![image1.6.1](images/image1.6.1.png)

## Delete 2 No Action Matches Count
On the left menu, on step 2, click the “Trashcan” icon.

![image1.6.2](images/image1.6.2.png)

## Confirm Delete
Click “Delete”. Wait for the system to train.

![image1.6.3](images/image1.6.3.png)

## Delete Conditions
* (a) On the left menu, click 1.
* (b) Delete the condition, on the right side of conditions “if _ of this is true:_ and_” click the “x”.
 
![image1.6.4](images/image1.6.4.png)

## Open Preview
Click “Preview”.

![image1.6.5](images/image1.6.5.png)

## View Default Responses Before Setting Up NeuralSeek Call
* (a) Type a random question, in this example it is, “Why is the sky blue?”
* (b) Press “Enter”.
  
View the watsonx Assistant’s default response, “I’m afraid I don’t understand. Please rephrase your question.” This is to test that the fallback action is being triggered properly.

![image1.6.6](images/image1.6.6.png)

## Delete Default Response
In the assistant text box, delete “I’m afraid I don’t understand. Please rephrase your question.”.

![image1.6.7](images/image1.6.7.png)

## Add Subaction
* (a) Scroll to “And then”, click “End the action”.
* (b) Select “Go to a subaction”.

![image1.6.8](images/image1.6.8.png)

## Go to a Subaction
Select “NeuralSeek search".

![image1.6.9](images/image1.6.9.png)

## Check Action
* (a) Check “End this action after the other action is completed”.
* (b) Click “Apply”.

![image1.6.10](images/image1.6.10.png)

## Preview NeuralSeek Generative AI Response
* (a) In the lower right, click “Preview” and type a random question, in this example it is, “Why is the sky blue?”
* (b) Press “Enter”.

View the NeuralSeek generative AI response.

![image1.6.11](images/image1.6.11.png)
