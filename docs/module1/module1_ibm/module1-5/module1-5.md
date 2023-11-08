---
title: Module 1.5 - Starter Kit Actions
permalink: /module1/module1_ibm/module1-5/
parent: module1_ibm
order: 5
---

# Module 1.5: Add NeuralSeek Starter Kit Actions

## Open Actions

Open IBM Watsonx Assistant. 
- **(a)** On the left menu, select “Actions”.
- **(b)** Click “Created by you”.
- **(c)** Click “Create action”.

![image1.5.1](images/image1.5.1.png)

## Create an Action

Select “Quick Start with Template".

![image1.5.2](images/image1.5.2.png)

## Build at Hyperspeed

Select “Do more with starter kits”.

![image1.5.3](images/image1.5.3.png)

## Quick Start with Templates

Search and select “NeuralSeek”.

![image1.5.4](images/image1.5.4.png)

## NeuralSeek Starter Kit

Click “Select this starter kit”.

![image1.5.5](images/image1.5.5.png)

## Selected Templates

Click “Add templates".

![image1.5.6](images/image1.5.6.png)

## View Inactive Actions

- **(a)** On the left menu, select “Actions”.
- **(b)** Under All items, select “Created by you”. On the right side under status, view the red circle on “NeuralSeek search”. At this stage, the circle is red because the integrations are added, but not yet connected to the underlying extension.
- **(c)** Open the action, click “NeuralSeek search”.

![image1.5.7](images/image1.5.7.png)

## Customer Starts With

On the left menu, select option 3 highlighted in red “This step has no content.”

![image1.5.8](images/image1.5.8.png)

## Delete Assignment

On the right side of the set “Query_Context to Context” click “X.” 
The reason why we are deleting it is because sometimes the query context provided by watsonx Assistant can be huge and exceeds the size of the request body to the API.

![image1.5.9](images/image1.5.9.png)

## Edit Extension

Scroll down and click “Edit extension”. 

![image1.5.10](images/image1.5.10.png)

## Choose an Extension

Select NeuralSeek extension, in this example it is, “IBM Learning Lab: NeuralSeek with Watson”.

![image1.5.11](images/image1.5.11.png)

## Choose Operation

Select “Seek an answer from NeuralSeek".

![image1.5.12](images/image1.5.12.png)

## Set Extension Parameters

Select “Session Variables".

![image1.5.13](images/image1.5.13.png)

## Choose Parameters

Select “query_text” from the list options.

![image1.5.14](images/image1.5.14.png)

## Extension Setup

Click “Apply".

![image1.5.15](images/image1.5.15.png)

## Save Extension

In the top right corner, click the "Save" icon.

![image1.5.16](images/image1.5.16.png) 

## Close Extension

In the top right corner, click "x" to close. 

![image1.5.17](images/image1.5.17.png)

## Confirm Status

On the right side, view the green circle with a check mark next to NeuralSeek search. The circle is now green because the integrations are properly connected to the extension and ready to use. 

![image1.5.18](images/image1.5.18.png)
