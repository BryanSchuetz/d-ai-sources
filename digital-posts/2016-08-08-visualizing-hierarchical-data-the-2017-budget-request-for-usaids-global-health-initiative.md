---
title: 'Visualizing Hierarchical Data: USAID’s $8.5 Billion Global Health Initiative'
date: 2016-08-08 22:18:00 -04:00
tags:
- Global Health
- Data
Author: John DeRiggi
thumbnail: "/uploads/Capture.PNG"
---

![Sunburst](/uploads/Capture.PNG)

Budget data is notoriously difficult to analyze. The volume of data can be high, the long tables are unwieldy, and the structures are almost always multilayered, making it difficult to visualize. But with some of the advanced interactive visualization tools we use at DAI, we can analyze and present even complex data more clearly.
<!--more-->
In this example, we use a public data set from USAID’S 2017 budget request and we visualize it in a sunburst:

[A sunburst visualization for the Global Health Initiative’s 2017 Budget Request ](https://s3.amazonaws.com/daiblogviz/usaidghi/sunburst.html)
![sunburst_smaller.gif](/uploads/sunburst_smaller.gif)

`An interactive sunburst visualization of budget data`

Sunbursts are a great way to see hierarchical data all at once, and with a little JavaScript we can make them interactive, too. Thanks to [D3](https://d3js.org/) this is all easier (and free). The code for this visualization was derived from [Kerry Roden’s work](https://bl.ocks.org/kerryrodden/7090426).

The budget data came from the PDF files on [USAID’s website](https://www.usaid.gov/results-and-data/budget-spending). Specifically the data source is Table 13: Global Health Initiative-FY2017 Request on page 35 of the [Congressional Budget Justification for Foreign Assistance for FY2017](http://www.state.gov/documents/organization/252735.pdf).

Compare the interactive visualization with this table spread across four pages in a .pdf. Which is easier to understand?
![ghi budget](/uploads/page_one_budget.PNG)

`One of four pages from the USAID 2017 Global Health Initiative Budget Justification`

Other common methods for hierarchical data visualizations are dendograms and treemaps. You can read our previous post on dendograms [[here](http://dai-global-digital.com/data-mining-and-the-human-development-index.html)]. 

Data, especially large and hierarchical data sets, are notoriously difficult to understand, and often elicit either a disengaged or overly detailed reaction. Let’s hope that visualizations like these can help improve our understanding of complex data, and in turn, increase transparency and efficiency.