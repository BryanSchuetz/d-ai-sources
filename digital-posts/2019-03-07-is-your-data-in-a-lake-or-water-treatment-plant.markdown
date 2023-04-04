---
title: Is Your Data in a Lake or Water Treatment Plant?
date: 2019-03-07 09:00:00 -05:00
tags:
- Data
Author: "[Ben Mann](https://www.linkedin.com/in/ben-mann-13012513/)"
social-image: "/uploads/1_KiGsfO6WD6_sn1Qx70w3vA.png"
thumbnail: "/uploads/1_KiGsfO6WD6_sn1Qx70w3vA.png"
---

They say to write about what you know. For the first part of my career and through my formal education, my work was all based in the world of water and sanitation. Glamorous stuff—pipes and pumps, fecal coli-forms and treatment options, toilets and activated sludge. It made for great dinner conversation (or so says my wife). At some point, I made the transition from a water guy who worked with a lot of data to a data scientist who knows about water. And as I dive deeper into the analogies and lingo of modern data systems and tools, I lean on my engineering training to make sense of it all.

<!--more-->

The *hilarious* (read:cringe-worthy) jokes in the board room by executives about “let’s just send divers into the data lake” really misrepresent what a data lake is—and more broadly, the entire process of churning raw data into meaningful insights. And as we strive to improve data literacy for everyone we work with, we really need to find a better analogy.

To start, our data is like water. It brings sustenance to our businesses and the life blood of our organizations. But our water can be full of sh\*t and bacteria hidden to the naked eye. Lakes are ecosystems with tributaries and streams that feed into them. They can be used for fishing, water skiing, drinking supply or just a nice thing to look at. Which is true of a lot of our data.

Maybe your data lake is the reservoir where things are cold-stored. However, lakes don’t deliver water to users. They don’t deal with water quality. They can be a single part of the larger delivery network. But what if your data comes from groundwater? What if it’s a rainwater collection system as data drops from the sky into your business? We need to embrace the entire system that takes our raw resource and delivers it through pipes and systems to end users.

## Data Lakes Are Actually Water Treatment Plants

The boardroom picture of a scuba diver in a lake does no justice to the complexities of making a data lake functional in today’s business intelligence and machine learning world. As [@OneAngryPenguin ](https://twitter.com/oneangrypenguin)explained during a recent overview of the Azure Data Lake Store, it’s really three components/parts under the hood: raw data storage, data cleaning and transformation (ETL), and processed data. Just like a multi-stage water treatment plant. We take in whatever raw data we can, clean it up, and send it out for consumption by households, businesses, or the public. Primary, secondary, tertiary treatment—we scrub out personally identifiable information, filter for nulls and missing values, and bring together data from different sources to meet the supply demands downstream.

![1_KiGsfO6WD6_sn1Qx70w3vA.png](/uploads/1_KiGsfO6WD6_sn1Qx70w3vA.png)`Image: Ben Mann`

Data architects and system engineers are the designers and city planners who help draw up the infrastructure and route water to new neighborhoods. DBAs, SysAdmins, and developers are the O&M utility crew who maintain the pipes and keep the water flowing. Data scientists are the water quality team, helping clean and pull insights out that customers drink. Everyone has a role to play in keeping data flowing from source to tap.

Tools like Hadoop, SalesForces, or MongoDB may seem complicated to anyone who doesn’t work with them daily, but our data systems really are eerily similar to other municipal infrastructure we’ve dealt with for decades and know all too well. And just like when we don’t plan/govern/regulate water systems, our data systems can end up with price-gouging private wells and data-hogs who tap aquifers dry. Data governance teams make sure we are consistent in how we treat the water and ensure equity in access for all. They keep the rest of the process in check. Like the Environmental Protection Agency and city inspectors, our data needs quality assurance checks and periodic audits to make sure no one will get sick from our insights and that our businesses won’t die of waterborne diseases.

Ultimately, no one wants to drink raw sewage, right? End users want clean water, in their kitchen, available at a moment’s notice from the tap. They don’t need access to the main trunk line—they need fit-for-purpose data and insights that are accessible and usable. The effectiveness of the water treatment plant is judged by those at the end of the line—be it a vice president, project manager, client, or major distribution hub data warehouse. Some of our data will be used for cooking or for putting out fires. The route it takes may vary. But the principles to get raw data through the system to safely meet demand are almost always the same.

Because in the end, our data is just like water.

*[Ben Mann](https://www.dai.com/who-we-are/our-team/ben-mann) is a Global Practice Lead for Development Results at DAI.*