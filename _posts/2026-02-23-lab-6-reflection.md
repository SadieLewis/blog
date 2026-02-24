---
layout: post
author: Sadie Lewis
---

***Lab 6 Reflection***

When I was creating the user stories for the given scenario in Lab 6, I assummed there would be the roles of store owner, customer, and admin. These 3 roles composed the personas within the user stories I created. They were as follows:


**5 User Stories**


1) As a Store Owner, I can list products, so that they can be sold to consumers.


2) As a Customer, I can register an account, so that I can purchase items. 


3) As a Store Owner, I can add product specifications, so that customers can see item specifications


4) As a Customer, I can specify order instructions, so that I can choose a time, date, and method. 


5) As an Admin, I can add the ability to register accounts, so that users can view and buy products.




Overall it wasn't difficult to concoct these stories, but it was hard to determine the overlap between them and estimate how long they'd take. This was especially evident in distinguishing story 2 and 5, since they both rely on the same functionality to be added to the web application. 
To go into more depth about these user stories:


- 1 is connected to both 2 and 3, it is a middle priority since it is a medium task. As such, it may take a while to create the ability to list products but it won't take forever. 
**Priority=3 Estimate=3 hours**
- 2 is connected to 5, it is a middle priority since it is a medium sized task as well. It may take a bit longer to accomplish than 1, but it still won't take forever. 
**Priority=4 Estimate=5 hours**
- 3 is connected to 1, it is a high priority because it is the easiest to accomplish. Due to the fact that it won't take too long it takes highest priority. 
**Priority=1 Estimate=1 hour**
- 4 is connected to 1, it is a higher priority since it will be easy to accomplish once products can be listed. As such, it also shouldn't take much time. 
**Priority=2 Estimate=2 hours**
- 5 is connected to 2, it is a low priority because it is a large task. It may take the longest, since the ability to create and register accounts may prove a longer task. Additionally 2 relies on this task to be complete, or else it cannot occur. 
**Priority=5 Estimate=5 hours**


The following is my LucidChart entity-relationship diagram that I modeled after this lab. I included 5 entities, the store owner, admin, customer, item, and order. All of them were connected in some way or another, for example, a store owner can list an item, an item can be added to an order, a customer can purchase an item, and the admin can create the ability for the owner to add items. Additionally these entities have attributes, like how order has type (pick-up or delivery), time, finalized (done or not), and a date. I also included the cardinalities for each relationship, to indicate the nature of them.
![LucidChart](BLOG/blog/Lab6_LucidChart.png)


This model is the results of my RedGate Data Modeling schema, where I made a table for each entity translated over from the entity-relationship diagram. The most complex entity is the order, which relies upon the foreign keys of both item and customer to register whose order it is and what's in it. After that is is assigned its own primary key in the order ID to keep it from being mixed up with others. The store owner and admin are included, but admitedly don't have many attributes relevant except for their names on their accounts permitting them to access and adjust things beyond customer access. 
![RedGate](BLOG/blog/Lab6_RedGate.png)