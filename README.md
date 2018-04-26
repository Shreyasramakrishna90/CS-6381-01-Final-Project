# Smart City Data Streaming and Analytics 

This project aims to provide an architecture to stream and analyse the data collected in smart city. Through this project we demonstrate some important concepts of data collection, streaming, data management and analytics. The overall aim of this work is to provide a reliable and robust infrastructure to build a smart community.

***Building Blocks***
a) Data Collection: Refers to the sensing stage, where sensors accumulate data. 

b) Data Streaming: Refers to the satge where, the sensed data is transported/ streamed to a data storage, which can be run on the local machine/ cloud.

c) Data Management: This refers to the database stage, where the streamed data is going to be stored.

d) Data Analytics: Performing query/ anomaly detection on the data to provide some data related feedback to the user.

e) Computing Paradigm: The main focus of this work is to focus of different computing paradigms of cloud/edge/Fog. 

***Architecture Challenges***
```
The architecture we propose should satisfy the following requirements:
(a)Location transparency: The servers running the instance of database, should be migratable and available at any location.
(b)Data protection: Data should be encrypted while being moved to the server.
(c)Reliability: Any part of the architecture can break down, we need to think about making the system reliable and available.
(d)Online Query: We should be able to perform some online query on the data using stream processing/ Complex Event Processing.
(e)Plug and play. The architecture should be modular. The system should be able to integrateany new component without much of a problem.
```
We have to think about adding distributed techniques into our architecture.

![architecture v1.0](https://github.com/Shreyasramakrishna90/CS-6381-01-Final-Project/blob/master/.png)

![architecture v1.0](https://github.com/Shreyasramakrishna90/CS-6381-01-Final-Project/blob/master/original_idea.png)
