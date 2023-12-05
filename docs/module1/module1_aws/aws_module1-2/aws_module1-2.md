---
title: 1.2 - Configure KnoweldgeBase
permalink: /module1/module1_aws/aws_module1-2/
parent: module1_aws
order: 2
---

# Module 1.2 - Configure KnowledgeBase with NeuralSeek

## Configure

Navigate to the “Configure” tab in NeuralSeek.

![image1.4.1](images/image1.4.1.png)

## Corporate KnowledgeBase Details

Click the “Corporate KnowledgeBase Details” drop down menu. 

![image1.4.2](images/image1.4.2.png)

## Select KnowledgeBase

- **(a)** Select desired KnowledgeBase from the drop down menu. For the purpose of this lab, we recommend the AWS KnowledgeBase "**Kendra Index**." 
- **(b)** Select desired language. For the purpose of this lab, click "**English**." 
  
![image1.4.3](images/image1.4.3_updated2.png)

![image1.4.4](images/image1.4.4_updated2.png)

## Add KnowledgeBase Information

User is responsible for providing selected KnowledgeBase detail information. Since it takes time to set these up for yourself, we are going to be using the one that is already prepared for the learning lab, with read-only access. The actual values below will be provided during the course of this lab by the lab instructor.

> ⚠️ **To understand how to create and locate the AWS access keys, refer to this section: [AWS Access Keys]({{site.baseurl}}{% link module1/module1_aws/aws_module1-2/kendra_keys/kendra_keys.md %}).**

Please enter the following:

- **(a)** Add "Kendra Index ID".
- **(b)** Add "AWS Role Access Key".
- **(c)** Add "AWS Region".
- **(d)** Add "AWS Role Secret Access Key".

![image1.4.5](images/image1.4.5_updated.png)
 
Click "Save" button at the bottom.

![image1.4.6](images/image1.4.6.png)

> NeuralSeek is now set up with a KnowledgeBase, in this case: **Kendra Index**, and ready to seek. 

## ⚠️ For creating your own Kendra index to do the lab

With the interest of time, the lab will use an already built-in Kendra index that is pre-filled with the data. That is because of the fact that creating Kendra index and populating the data would take from 40 minutes to even over an hour to complete. However, in case you are interest to later perform the lab using your own Kendra index and keys, you can follow the below instruction.

🔗 <a href="{% link module1/module1_aws/aws_module1-2/kendra_keys/kendra_keys.md %}">Setting up AWS Kendra Index and Access Keys</a>.