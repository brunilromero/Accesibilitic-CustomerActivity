ACCESSIBILITIC-CustomerActivity is a network of ontologies that supports inference process and provides answers to the following Competency Questions (CQ): 

CQ1: What customer actions are related to specific customer activity? 
CQ2: What customer operations belong to a specific customer action? 
CQ3: What actions are related to a specific customer operation?
CQ4: What operations can be performed by customers in terms of their activities and participation in the information society?

This work was conducted using Protégé 5.0.0 and Hermit 1.8.3.413 
Authors: Brunil D. Romero, María J. Rodríguez , María V. Hurtado, Hisham Haddad (2019)

In order to visualize how ACCESIBILITIC-CustomerActivity ontology works the following steps should be taken into account:
1.	Creating a folder and downloading these two owl files: CustomerActivity.owl, and ACCESIBILITIC-CustomerActivity.owl
2.	Opening ACCESIBILITIC-CustomerActivity.owl in Protégé. 
3.	Choosing "Reasoner" from the menu bar, from the pull-down menu first select "Hermit 1.3.8.413" and finally “Start reasoner”.
4.	Observe the following table to understand with an example of how each CQ is solved. It is conformed by the class name, the defined classes, and the respective CQ. In the class hierarchy of the proposed ontology locate each class, defined class and watch their inferred instances.

Class	               -            Defined Class	              -             CQ
-----------------------------------------------------------------------------------------------
CustomerAction            	PurchaseCustomerAction	         CQ1 - Customer Activity “Purchase”
                            EvaluatingCustomerAction	       CQ3- Customer Operation “Evaluating”
                            
CustomerOperation	          FullfilmentCustomerOperation	   CQ2- Customer Action “Fullfilment”
                            Customer08Operation	             CQ4- Customer Operation of Customer08

