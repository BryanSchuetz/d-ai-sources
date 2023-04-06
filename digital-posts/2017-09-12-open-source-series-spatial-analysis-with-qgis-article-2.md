---
title: 'Open Source Series Part 3: Spatial Analysis with QGIS (Article 2/2)'
date: 2017-09-12 10:04:00 -04:00
tags:
- GIS
- Data
- Open Source Series
Author: Greg Maly
social-image: "/uploads/logo_evolution.png"
thumbnail: "/uploads/logo_evolution.png"
---

*In my [last post](https://dai-global-digital.com/open-source-series-spatial-analysis-with-qgis.html) I introduced QGIS, and previewed some of the basic functions in the upcoming release of Version 3.0. In this second of two articles, I’ll compare using QGIS in professional organizations to the use of proprietary software, and provide recommendations for organizations seeking to test the waters with spatial analysis. I’ve also reached out to three GIS professionals with experience integrating spatial analysis software into diplomatic and development work environments, and shared their perspectives in a Q&A section below.*

![logo_evolution.png](/uploads/logo_evolution.png)

<!--more-->

## Why QGIS? Strengths and Weaknesses

In the [introduction to this series](https://dai-global-digital.com/open-source-series-part-1-what-is-open-source.html), I briefly highlighted some of the benefits and drawbacks to working with open source technology. So, do these observations apply in the case of QGIS? In short, yes.

What QGIS provides users is a suite of analytical tools to conduct spatial analysis on a desktop. If you want to host your data online you can use the [QGIS cloud](http://qgiscloud.com/), and if you’d like to stay in the QGIS ecosystem to do data collection you could try [QMap](http://nathanw2.github.io/qmap/). There are many plug-ins and web services available to extend your QGIS usage, and developers are producing new tools all the time.

But it is not uncommon to find QGIS users straying from the branded ecosystem to manage data collection, run analysis, and create visualizations. If you want to do statistical analysis you may want to download a copy of [Geoda](http://geodacenter.github.io/). [Open Data Kit](https://opendatakit.org/) is a great way to build field data collection into your project. And web-mapping packages such as[ Leaflet.js](http://leafletjs.com/), [OpenLayers](https://openlayers.org/), and tools provided by [Mapbox](https://www.mapbox.com/) help bring your data alive on the web. Or you could of course use the free tier of [Carto](https://carto.com/), but now we’re getting outside of the open source realm.

Exhausted yet?

What we’ve just covered are a host of extremely powerful tools, but they require thinking about data interoperability, data storage methods, and may necessitate software development skills. If that doesn’t sound appealing to you, you can turn to proprietary software.

For organizations seeking a one-stop shop of desktop and web-mapping needs, you need look no further than [ArcMap](http://desktop.arcgis.com/en/arcmap/), [ArcGIS Pro](https://pro.arcgis.com/en/pro-app/), and [ArcGIS Online](http://www.esri.com/software/arcgis/arcgisonline). There isn’t a GIS stone unturned in the ESRI world, and you can go from data to the web without touching a line of code on day one. But this comes at an up-front financial cost, and it’s not hard to spend tens (if not hundreds) of thousands of dollars on software and web hosting to serve your organization’s needs. Every license, package extension, and click on websites adds to your cost. What organizations need to weigh in this case is where they want to incur their costs, and whether they’re ready to commit to such a large purchase.

Software developer time can be expensive, and it would not be hard to make the case that buying into the ESRI ecosystem may save time and money. But it all depends on your needs.

It’s also important to acknowledge the rise of business intelligence software such as [Tableau](https://www.tableau.com/), [PowerBI](https://powerbi.microsoft.com/en-us/), and [Qlik](http://www.qlik.com/us/). We’ll likely cover this ecosystem of software in another post, but business intelligence software increasingly enables the production of basic choropleth, or shaded, and point maps, and the integration of these visuals into interactive dashboards. Often this is all organizations seek to build, and deeper analytical functions provided by a fully fledged GIS may go unused.

## GIS and Your Organization—A Q&A with Professionals

To learn more about open source vs. proprietary GIS, I reached out to three geographers: [Dr. Joshua Campbell](https://twitter.com/disruptivegeo?lang=en), CEO of SandHill Geographic; [Dr. Susan Wolfinbarger](https://twitter.com/swolfinbarger?lang=en), geographer at the Bureau of Conflict and Stabilization Operations and former Director of the Office of Geospatial Technologies at the American Association for the Advancement of Science; and a professional GIS analyst at USAID. Each has experience building teams around spatial analysis needs, developing software, or providing training to others. I asked three questions. They provided very diverse answers, and I’ve quoted each of them below.

* JC – Dr. Joshua Campbell
* SW – Dr. Susan Wolfinbarger
* USAID – Unnamed USAID GIS Professional

**Question 1: In your experience, how many GIS professionals use QGIS vs ArcGIS?**

> **JC:** I don’t have hard numbers, but I would estimate that QGIS is still a small percentage (maybe 10 percent) of the overall GIS market (at least in the United States). That said, I’d also estimate that the growth rate is tremendous, with significant year-over-year growth. As QGIS matures, along with the rest of the open source geospatial ecosystem (mainly PostGIS), the interest and growth in its use is accelerating. I just attended the Free and Open Source Software for Geospatial (FOSS4G) conference in Boston (http://2017.foss4g.org/), and a couple of trends stuck out. First, the size of the conference was 1,100+ people, with roughly a third of attendees from outside of the United States. This is by far the largest in FOSS4G history; by comparison, my first one in 2007 had 600 attendees. Second, the conference dedicated a day to QGIS (http://2017.foss4g.org/program/), and many of the sessions were well attended. The State of QGIS talk, which outlines all the coming changes to QGIS 3.0 was particularly interesting as it is major refactoring with many performance improvements. QGIS is already near feature parity with proprietary desktop GIS applications, and the new version provides increased capabilities in the visualization and analysis functions where it is already strong.
>
> **SW:** I think the vast majority of GIS professionals use ArcMap over open source software options like QGIS. The open source GIS software products I’ve used, including QGIS, don’t work well on iOS computers. So my advice to the open source software development community is to focus as much on Apple as Windows and Linux operating systems. That being said—I do used QGIS regularly on a Windows machine, and would use it for all of my extracurricular projects if the Mac version worked well. Anecdotally, every time I’m at a geography conference, everyone is using a MacBook Pro!
>
> **USAID:** Most GIS professionals I know try to use both. Each platform has specific strengths and weaknesses that don’t necessarily overlap. However, for smaller organizations or where cost is a barrier, most GIS professionals will defer to QGIS.

**Question 2: Why do you think people continue to rely on proprietary software applications like ArcGIS and Tableau given free alternatives?**

> **JC:** For ArcGIS, I believe training/experience and existing availability of software are the two reasons people continue to use them. Cost matters very little to analysts who are not responsible for paying the maintenance fees, so it is essentially “free” to them. I will say the learning curve is not a trivial issue. When I first learned QGIS I had 10 years of ESRI experience and thoroughly understood the “button-ology” of how to execute a given task. Relearning a new user interface required time and effort, but now that I have, I choose to use QGIS.
>
> **SW:** Typically, I think there are a few reasons why the GIS community continues to rely on proprietary software applications:
>
> * It is what they learned in school.
>
> * It has a guarantee of support that you don’t receive via open source options.
>
> * There is typically a very large user community, backed by regular conferences and professional development.
>
> * Proprietary software fits into classic budgetary and technology approval processes.
>
> * The well thought-out integration between functions. ArcGIS provides everything within their architecture, so it’s easier to work with than cobbling together a variety of different solutions and having to deal with other structures, costs, and varied platforms. You just know how everything is going to work every time.
>
> **USAID:** Student licenses for the proprietary software are robust and widely available. The majority of higher ed institutions seem to instruct on the proprietary software, though this practice is changing. Most of the time a GIS professional will enter a position where proprietary licenses have already been purchased and thus do not need to seek out alternatives.

**Question 3: What advice to you have for organizations seeking to improve their use of spatial data from both an educational, staffing, and software perspective?**

> **SW:** I think that you have to have a champion in the organization who is willing to go the extra mile to demonstrate the power of spatial data and analysis. That’s true with most new initiatives. With so many options for online training, there are a lot of great options for those newer to GIS to improve their skills.
>
> In terms of software, I think starting with open source makes a lot of sense. It lets an organization test out the capabilities and determine if demand exists. I feel that once you start producing a fair amount of content that it makes sense to go proprietary if at all possible. There will be a lot more support for standing up a formal analysis workflow that can be used across multiple users over time. What may be most important is to communicate to leadership the investment required. Even if the organization is using all open source software, geospatial analysis takes a long time!
>
> **JC:** Look for easy wins and start with them. Try to find metrics that can be measured; this is often difficult, but look for proxies or even testimonials to demonstrate impact. A full-fledged “enterprise” adoption of anything is a scary proposition...but, a measured, intentional effort to switch out technologies, or include a new analytical method in a project, can be accomplished quickly, usually cheaply, and be used to demonstrate value.
>
> While the acquisition cost of open source software is often used to justify its adoption, don’t fall into the $0 price tag trap. As a friend said once, “Open source is free like a puppy.” There are care and feeding considerations you must include in your decision framework, and you must think in terms of “total cost of ownership.” This will benefit your efforts in two ways, first, it means you will think through all the implications of a change (which your leadership will appreciate), and second, with a thorough understanding of your workflow, you’ll likely uncover other ways that adopting open source will benefit your organization.
>
> Finally, don’t underestimate the value of participating in an open source community. The shared resource pool means that all benefit from the features funded and developed by a few. Additionally, developers often want to work on open source projects, and the ability to recruit and retain talent increases with developers want to work on your projects.
>
> **USAID:** Ensuring there is a clear business use case and defined analytical workflows that GIS can influence is key. The real power and value of GIS lies in it’s analytical applications so making sure there are established data pipelines and areas for enhanced decision-making is crucial.

## Our Recommendation

So, what do we recommend? It’s difficult to provide blanket guidance on software for institutions as complex as development organizations, but here are some general guidelines that we recommend you follow.

**Use QGIS If:**

* You need extended spatial analysis functionality on the desktop.
* You’re just getting started with spatial analysis and want to test the water before spending money.
* You’re comfortable mixing multiple software applications for your analytical needs.
* You have or are willing to invest in web development to publish your maps online.
* You will be working with a local organization that would like to learn the software, but may not have the resources to purchase licenses.

**Use Proprietary Software If:**

* You need extended spatial analysis functionality on the desktop.
* You were trained it in a specific software (like ArcGIS) and are most comfortable using it.
* You would rather purchase technical support outside of your office environment than hire dedicated internal staff.
* You want to build online tools without hiring a web developer.
* You have been asked to work in a specific proprietary software application by a client/customer.