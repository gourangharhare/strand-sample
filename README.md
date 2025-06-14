This lab can be used with **Bedrock agent workshop** : https://catalog.workshops.aws/agents-for-amazon-bedrock/en-US **in AWS Event**.

The objective of this instructions is to make other strand agent workshop lab on restaurant booking use case to be able to run in accounts provisioned for above workshop.

Follow below small steps:

**Step 1 :  Enable access to following models in Bedrock console:**
* Amazon
    * Titan Embeddings G1 - Text
    * Titan Text Embeddings V2
    * Nova Micro

**Step 2 : Perform Git Clone on Jupyter Lab Terminal :**

Start with > 
	Searching Sagemaker AI in console 
	> select studio option from left corner 
	> click on Open Studio 
	> Click on Jupyter Lab
	> click on File menu
	> click on New Terminal option

Run below command on the terminal : 

git clone https://github.com/gourangharhare/strand-sample.git

This should create folder “strand-sample”. You can navigate to it in left hand side file explorer in Jupyter lab UI.

**Step 3 : Open JupyterLab notebook at this path:**

strand-sample/restaurant-booking/connecting-with-aws-services.ipynb

Note:  After you have reached to “Setup agent configuration” cell in the notebook. Please follow the instruction to copy knowledge base id and past as value for variable kb_id.

You are now can follow the instructions in Jupyter notebook.

**Participant can practice other strand labs in their own AWS accounts or in AWS event using the instructions given in below workshop URL**
https://catalog.us-east-1.prod.workshops.aws/workshops/33f099a6-45a2-47d7-9e3c-a23a6568821e/en-US/01-fundamentals/13-connecting-with-aws-services
