---
title:  "SQL vs NoSQL database"
tags: database SQL NoSQL
---

## Overview


|         					|SQL           |NoSQL  |
| Data storage      		| Stored in a relational model, with rows and columns. Rows contain all of the information about one specific entry/entity, and columns are all the separate data points; for example, you might have a row about a specific car, in which the columns are ‘Make’, ‘Model’, ‘Colour’ and so on. | The term “NoSQL” encompasses a host of databases, each with different data storage models. The main ones are: document, graph, key-value and columnar. More on the distinctions between them below. |
| Schemas and Flexibility	| Each record conforms to fixed schema, meaning the columns must be decided and locked before data entry and each row must contain data for each column. This can be amended, but it involves altering the whole database and going offline.      |  Schemas are dynamic. Information can be added on the fly, and each ‘row’ (or equivalent) doesn’t have to contain data for each ‘column’. |
| Scalability 				| Scaling is vertical. In essence, more data means a bigger server, which can get very expensive. It is possible to scale an RDBMS across multiple servers, but this is a difficult and time-consuming process.     |    Scaling is horizontal, meaning across servers. These multiple servers can be cheap commodity hardware or cloud instances, making it alot more cost-effective than vertical scaling. Many NoSQL technologies also distribute data across servers automatically. |
|ACID Compliancy (Atomicity, Consistency, Isolation, Durability)|The vast majority of relational databases are ACID compliant.|Varies between technologies, but many NoSQL solutions sacrifice ACID compliancy for performance and scalability|

		
## The many faces of NoSQL

- Document Databases
- Key-Value Stores
- Graph Databases
- Columnar (or Wide-Column) Databases

## Which to use?

The idea that SQL and NoSQL are in direct opposition and competition with each other is flawed one, not in the least because many companies opt to use them concurrently. As with all of the technologies I’ve previously discussed, there really isn’t a ‘one-system-fits-all’ approach; choosing the right technology hinges on the use case. If your data needs are changing rapidly, you need high throughput to handle viral growth, or your data is growing fast and you need to be able to scale out quickly and efficiently, maybe NoSQL is for you. But if the data you have isn’t changing in structure and you’re experiencing moderate, manageable growth, your needs may be best met by SQL technologies. Certainly, SQL is not dead yet.