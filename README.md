# Welcome to NeuralSeek Learning Lab

## IBM related lab information
### IBM Watson Discovery
Use the following Discovery related connection information to be used during the learning lab when configuring NeuralSeek's KnowledgeBase.
- URL: `https://api.us-south.discovery.watson.cloud.ibm.com/instances/e9e735c1-59cd-495f-a24d-ad211c5f2699`
- API Key: `T1t02CfjKbKcd9KW7MMD5cm-HlPZ7Ii28eCV2EYwGut2`
- Project ID: `c8925a42-718d-407b-a0d7-dd707a246289`

The above project contains the web crawled collection of documentation found in https://documentation.neuralseek.com.

## AWS related lab information
### AWS Kendra
During the AWS learning lab, lab participants are required to setup NeuralSeek with a knowledgebase. Creating their own Knowledgebase and adding documents to use it during the lab is impossible, as those would take close to hours. Therefore, When using learning lab, we do provide access to a Kendra Index which is pre-populated with information.

These information are crawled website information of https://documentation.neuralseek.com.

#### Kendra User and Index
Kendra Index is maintained in the AWS account id: `o-p6ngjotm9i`, which is tied to ths following account ID: `633375292905` (converlistics.com).

As for the Kendra Index itself, here are the details:
- Name: neuralseek-lab
- Index ID: `c953a14b-161b-4210-9804-9de81172da43`
- Region: `us-west-2`

As for the user, we are using `neuralseek-lab-user` in the IAM which is included into `neuralseek-lab-group`. In this group, is a policy `Kendra-neuralseek-lab-readonly` that provides read-only access *ONLY* to the Kendra index mentioned above.

#### Access Key info
The following API key and Secret Access key is configured with the above mentioned user, to be used during the learning lab to setup the KnowledgeBase.
- Access Key ID: `AKIAZG6A37XUT4YO744P`
- Secret Access Key: `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`

> ⚠️ DO not publicly share these information externally. These keys are only going to be shared during the learning lab. The key is going to be `INACTIVATED` during the non-lab period so that any usages outside of learning lab session will not be permitted.