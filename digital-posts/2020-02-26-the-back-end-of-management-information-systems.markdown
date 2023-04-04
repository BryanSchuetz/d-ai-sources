---
title: What's the Best Architecture for a Management Information System?
date: 2020-02-26 06:30:00 -05:00
tags:
- Data
- Interoperability
Author: Trevor Olexy
social-image: "/uploads/CLOUD.jpg"
thumbnail: "/uploads/CLOUD.jpg"
---

What is the best architecture for a management information system? I hate to say it, but it depends. Generally though, I do have an opinion, and while your mileage may vary, I think one model might often better serve more use cases.

At first glance, you might think our products team only builds full-stack web applications. That is only half our story. We also spend a significant time providing technical advice to DAI project staff and their government counterparts on the technology solutions they are looking to procure. I call this *translating:* taking the needs and requirements of the project and explaining it in technical terms to developers and IT experts. One common area we help project staff understand, update, or integrate is a management information system (MIS) in disparate and un-harmonized contexts.

<!--more-->

## What is MIS?

MIS is a system that retrieves, transforms, and stores data from multiple sources, related or not. Generally, MIS is considered all of the hardware, software, databases, people, organizations, and even policies involved with data interoperability. This makes it available and usable by other contributing entities (labs, schools, agencies, organizations, etc). Each sector has its own context in which it exists and will thus have unique requirements for MIS. For example, a laboratory management information system (LMIS) will have different data and security requirements than a financial institution information system (FMIS) or a school district's information system (EMIS). For this post, I'll be focusing on the database layer.

Interoperability is key to designing successful MIS. Even though this is not the focus of this post, understanding how interoperability works is helpful for understanding the data base layer. So what is interoperability? It is the tools, software, or algorithms that allow data to be accessed, translated, and used in conjunction with other data or external data visualization tools. To achieve this, MIS will often involve the extensive use of application programming interfaces, or APIs.

## Types of MIS

First, we need to define what we are talking about in terms of high-level general types of MIS. I will focus on three system architecture types: a single database system, a centralized system, and a federated system.

A **single database** architecture is one in which all contributing entities use one single database and system to store all data. This is highly impractical from a technological and managerial point of view. First, because there can be huge variance in data types and security requirements across databases or sets. Entities collect data of different types, using different platforms, for different purposes, and at different frequencies. They will also certainly require varying levels of privacy or security. Creating or using one centralized information system (also known as a database) to store data can be both technologically and institutionally difficult, with functionality/security/network speed reduced to the least common denominator.

![singlesystem-d5cfa5.png](/uploads/singlesystem-d5cfa5.png)`This graphic represents a single system MIS.`

For example, once any organization stores GIS data, the database structure must account for that, even if only one organization requires it. As such, the database can become very large and difficult to manage, making data stewardship a possible concern if management is inadequate. Second, this MIS type also presents a single point of failure, meaning that if the system were to be compromised or damaged, all data would be at risk for deletion, manipulation, or damage. This is opposed to different models in which data is de-centralized, but still available for exchange.

A **centralized system** is one in which participating entities copy some or all of their data to a central repository where it is organized and stored based on a common data model. In this case, each independent system still maintains its own database but makes it available to a central and external database system. This might typically be managed by an independent organization or regulatory body.

![centralized-6cd747.png](/uploads/centralized-6cd747.png)This graphic represents a centralized system MIS.\`

In a centralized model, data is still owned and maintained by individual entities, and they relinquish that control once the data is shared with that centralized system, meaning that the institution managing the MIS then has control. In this model, adding new participants to the MIS requires updating the database, which can take a lot of time, be hazardous to data, and might not even be possible depending on technical considerations or limitations of the newly added organization.

A **federated system** is one where independent entities maintain control of their source data and permit participating groups on-demand access to some or all of their data via a central, user-facing application that utilizes interoperability layers. Compared to the other two models, a federated system is be easier to maintain, although there is always the potential of political roadblocks may make it difficult to implement (such as disagreements on memoranda of understandings and data-sharing agreements).

![federated-7de344.png](/uploads/federated-7de344.png)`This graphic represents a federated system MIS.`

In a federated system, data resides in independent databases owned and operated by the data owner. Each of these independent systems then permits external access to data authorized for sharing. In this configuration, organizations have full control over what, when, how, and with whom data is shared. To share the data, it must be transformed via the interoperability layer so that the data from multiple sources is readable by other data sets. Once all data is collected and transformed (either on demand or at specified intervals), the data can be accessed by any organization or user with permission to view the data via a data visualization layer of the MIS. This layer can be a custom web application or desktop software. A federated system also has several layers of security.

Lastly, in comparison to the centralized model, a federated system is much more flexible when it comes to adding data from new participating organizations. This is because only the interoperability and data visualization layers need to be modified.

## Final Thought

On the whole, each of these structures has advantages and disadvantages. Nothing is 100 percent secure or efficient. The right MIS model also depends on the environment or context in which it will be used. That said, in terms of flexibility and maintenance, a federated system comes out on top.