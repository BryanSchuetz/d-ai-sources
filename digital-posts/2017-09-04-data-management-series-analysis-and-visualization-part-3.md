---
title: 'Data Management Series Part 3: Painting a Vivid Picture with Data'
date: 2017-09-04 12:15:00 -04:00
tags:
- Data Visualization
- Data
- Data Management Series
Author: "[Karim Bin-Humam](https://www.dai.com/who-we-are/our-team/karim-bin-humam);
  [Ben Mann](https://www.dai.com/who-we-are/our-team/ben-mann)"
social-image: "/uploads/160939707%20data%20visualisation-f66a64.jpg"
thumbnail: "/uploads/160939707%20data%20visualisation-f66a64.jpg"
---

Welcome back! After reading the [previous two posts in this series](https://dai-global-digital.com/tags/?tag=data-management-series), you’ve come a long way: you’ve devised a brilliant monitoring, evaluation, and learning plan, set up your data storage and management infrastructure, and conducted your baseline data collection. It’s finally time to get to the good stuff and dive into the data to make sense of it all—with eye-popping graphics worth of downtown billboards!

![160939707 data visualisation-ab2ed4.jpg](/uploads/160939707%20data%20visualisation-ab2ed4.jpg)

<!--more-->

To begin, have a solid understanding of what type of data you have to analyze. Is it quantitative or qualitative? Do you have georeferenced data sets? Are you measuring integers, percentages, or scores? What units of measure are related to your various data points and are they easily related? This knowledge will make it simpler to select the appropriate method of analysis and how to present your results.

There are many different approaches to data analysis. Each of these approaches lends themselves to specific applications and contexts that define why you are collecting data and what you want to use it for:

* **Descriptive:** Summarizing quantitatively the main features of a collected dataset. This approach is typically employed across just about any data analysis application and is often the first kind of data analysis performed on large datasets such as census data.

* **Exploratory:** An approach that seeks to utilize collected data to find embedded relationships hidden within the data. Exploratory analysis results in insights into correlations between data points (remember, correlation doesn’t mean causation!)

* **Inferential:** This approach tests theories by inferring conclusions about a broad population or other subject matter based on relatively small samples thereof. This is typically the goal of statistical models and brings with it additional analytical rigor required to calculate the uncertainty of inferences.

* **Predictive:** The predictive approach combines historical data with current data to identify trends and make forecasts about the future.

* **Causal:** A causal analysis takes the exploratory approach a step beyond identifying correlation between data points, and examining causation between them, and figuring out what happens to one variable when another is changed.

Your data analysis could use any of these approaches or a mix of approaches, but the distinction is important because the different data types and tools for analysis at our disposal tend to lend themselves better to one or the other approach. At DAI we focus on using a mixture of versatile tools and platforms that can help us do more than one type of analysis. This mixture of tools tends to incorporate:

* **Geospatial analysis:** ranging from simple heat maps to complex point-source-network analysis using [ArcGIS](http://www.arcgis.com/features/index.html) or [QGIS](https://dai-global-digital.com/open-source-series-spatial-analysis-with-qgis.html)

* **Statistical models:** basic summary statistics, weighted averages, or Bayesian models using [SPSS](https://www.ibm.com/analytics/us/en/technology/spss/) or [R-Studio](https://www.rstudio.com/)

* **Machine learning:** predictive analytics, natural language learning, or neural network trend analysis using [TensorFlow](https://www.tensorflow.org/) or \[IBM Watson Knowledge Studio(https://www.ibm.com/watson/)

* **Network analysis:** for force-directed graphs, node-network clustering, and social network mapping using [Gephi](https://gephi.org/) or [Centrifuge](http://centrifugesystems.com/)

## Five Key Reminders for Data Visualization

Data visualization can be considered the art to data analysis’ science. This is where you get to be really creative in finding ways to communicate the secrets hidden within your raw data. The field of data visualization continues to explode, flooding that market with all strata of platforms from the simple (infogram) to the highly complex (power BI, Tableau). Artistry has a role in your data presentation, which can be strengthened by SVG tools such as [RAWGraphs](http://rawgraphs.io/).

Data can be represented in an infinite number of ways and the number is only increasing. From time-series data to geospatial data, scatter plots to nominal comparisons, bubble charts to spider charts, hierarchical tree diagrams to network maps and relational visualizations, you won’t lack for options. But among all the choices, we at DAI recognize that when creating a compelling visual narrative, it is important to make sure we take into account the following:

1. **Have a purpose for each visual.** Having a visual for the sake of having a visual doesn’t contribute to a narrative that you are trying to communicate about the data.

2. **Choose an appropriate chart.** If you decide to use a chart or graph, pick one that is a good fit for your data. Showing change over time? Don’t use a pie chart. Are different variables influencing your results? Maybe select a spider-gram.

3. **Keep it simple.** A user shouldn’t have to spend more than a few seconds looking at a visual to quickly draw out its key message.

4. **Let the user explore.** When working with digital platforms as opposed to static .pdfs, we like to make our visuals interactive to allow the user to explore the data in depth drawing out the specific insights he or she is looking for.

5. **Compare figures.** Simply providing aggregates can say something about your data, but providing a yardstick by which to measure summary data gives a sense of significance to each insight.

## What is Successful Data Management?

So we’ve covered all links in the data management chain that we introduced in the [first post in this series](https://dai-global-digital.com/data-management-series-planning-and-collecting-part-1.html). From establishing a clear data management plan, through collection and storage all the way to analysis and visualization, what we are trying to communicate with this series of posts is that taking a holistic approach to the chain is the way to ensure your organization will make the most of its data. With this approach, two things should happen:

1. **Every person directly involved in the chain understands how the system works:** Monitoring and evaluation specialists, data collectors/enumerators, chiefs of party, and others will know what types of data need to be collected, how to ensure collected data is clean and where it has to be stored for analysts to access and analyze it.

2. **Everyone else in the organization knows how to find the data they need:** Communications specialists, new business specialists, project backstoppers, and others have quick and easy access to a variety of data across departments and geographies. Need to know how many grants your company has administered to private businesses across Latin America? No problem, this should take just a few minutes!

As this year’s [MERLTech conference](http://merltech.org/) takes place, we will undoubtedly consistently be reminded of all the potential that data holds for improving development outcomes. But for all of the hype, one thing will remain unchanged: Data is just data—it is what we do with the data that defines its impact, and designing a management system that leverages it effectively is the difference between a bucket of crude and high octane jet fuel.