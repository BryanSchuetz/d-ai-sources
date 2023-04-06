---
title: Open Source Versus Proprietary Data Management Stack—Which One is Best for
  Your Team?
date: 2019-07-18 08:00:00 -04:00
tags:
- Open Source Series
- Data Management Series
Author: Greg Maly
social-image: "/uploads/PhoneUse.JPG"
thumbnail: "/uploads/PhoneUse.JPG"
---

As a product development team, we spend a lot of time listening to the needs of users, particularly when it comes to their desire to collect and analyze data. And while projects have unique needs, they often ask for a common set of technology solutions. These include the ability to:

1. Digitally collect and manage data - offline or online as mobile bandwidth permits.

2. Learn as much as they can from their data, often through a series a dashboards or reports.

3. Upload products and share learnings with a public audience.

4. Maintain an internal system for data sharing, so that people only have access to certain information.

Most importantly, these tools should be easy to use, and ideally not too expensive to build or maintain.

All of these are reasonable requests. If prioritized, organizations should be able to develop and maintain highly functional data management and analysis solutions. So why do so many organizations struggle to maintain these kinds of systems?
In this article, I’d like to outline two very different routes that organizations can take when trying to build out their systems: 1) completely proprietary solutions v. 2) open source technologies.

<!--more-->

## Group A: Buy It

You’ve made the decision to buy the toolkit of your dreams. Maybe you purchased licenses to mobile data collection tools that run offline on both Android and iOS devices, and paid to have that data cleaned and migrated to a knowledge management system inside of Salesforce. Sure, Salesforce has built in dashboards, but you’re hoping to learn as much as you can from your data, so you’ve purchased Tableau licenses for your staff, and an ArcGIS license for your spatial analyst. And because you want to host your results online and share them with people, you’ve purchased a copy of Tableau Server.

### Pros

* You’ve just exponentially upped your potential data management game.

* You can build beautiful dashboards without having to keep a team of developers on staff.

* If something breaks, you can rely on one of your vendors to investigate the problem.

* Project management continues to be a priority over technology management.

### Cons

* There's a chance you just spent hundreds of thousands of dollars on technology, and now you and your staff need to learn how to use it.

* While you paid for license fees for your current staff, you may need to buy more if your organization grows.

* Even if software is easy to use, it still requires maintenance, and you may need to hire people just to manage these tools.

* With proprietary software, often what you see is what you get. While customizable, you’ll have to wait for the next software update to add that dual axis line chart to your report.

* It’s possible that your data is in a system that only really talks to itself, and you don’t have a lot of control over how to get it out later.

* If your project comes to an end, you can’t hand over aspects of the system without finding funding for annual licenses fees.

  ![PhoneUse.JPG](/uploads/PhoneUse.JPG)\`A farmer in Central America using the Coffee Cloud application developed by CDA.\`

## Group B: Build it

You’ve made the decision to build your own or leverage open source tools as much as possible. To get started, you’ve installed [Open Data Kit](https://dai-global-digital.com/data-collection-with-opendatakit.html) (ODK) on cloud servers, and are running [PostgreSQL](https://www.postgresql.org/) with a series of Python scripts to move data around. The ODK graphs aren’t very sophisticated, so you’ve decided to build your dashboards in a couple of different ways. Maybe you have a web developer on staff who is ready to learn [D3](https://d3js.org/), or you’ve learned or hired some [R developers](https://dai-global-digital.com/getting-started-with-rstudio.html) who can build you dashboards in [Shiny](https://shiny.rstudio.com/). Instead of ArcGIS, you’ve made use of [QGIS](https://qgis.org/en/site/) for spatial analysis and cartographic design. You have several servers running to host your dashboards, and are working your way through [Apache](https://httpd.apache.org/), [NGINX](https://www.nginx.com/), and [OAuth](https://oauth.net/), trying to get your dashboards shared discreetly across your users.

### Pros

* You’ve just exponentially upped your potential data management game.

* You’re not paying license fees and can give people access to your system without paying for additional users.

* You’ve hired seasoned analysts and developers to build your system, so your data analysis and reporting dashboards are put together by people trained in research methods and quantitative analysis.

* You’ve learned an absolute ton about technology, and there are no limitations to what your team can have (assuming you have enough time to work on it...).

### Cons

* You’ve just spent months of your life looking at documentation.

* Every time something goes wrong, you and your team need to figure out how to fix it.

* You’ve become reliant on a whole series of [dependent packages](https://en.wikipedia.org/wiki/Dependency_hell), which leaves you at risk for system failure if someone creates a package update without your knowledge.

* Technology keeps changing, so you often spend the weekend learning how to build something in a new way.

* You are now in a world where you manage technology as much as you manage your projects.

## Reflections

As we can see from these two case studies, both Group A and Group B have come a long way on their data management journey, and each group is going to experience different challenges along the way. It’s hard to say who spent more money, as the Buy It group spent both time and lots of money on their software, while the Built It group had to hire analysts and developers, each of whom spent quite a bit of time setting their systems up.

## Our Approach

As a team, we’ve chosen to live somewhere between these two worlds, with a strong leaning towards the Build It camp. We do our best to leverage open source tools as much as possible, and when it makes sense, we have a team of developers who work in common web development framework (Python/Django). The proliferation of powerful business intelligence solutions means that we do use proprietary software, but when given the time we build dashboards in JavaScript, or by using the amazing R/Shiny framework.

What we know is this – in data management, no matter how you approach the problem set, you’re either going to have to spend time and money on professional data management staff, or spend money on software. There’s no such thing as a free lunch.