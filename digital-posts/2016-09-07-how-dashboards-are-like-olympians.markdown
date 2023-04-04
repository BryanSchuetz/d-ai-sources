---
title: How Dashboards are like Olympians
date: 2016-09-07 11:36:00 -04:00
tags:
- Data
Author: John DeRiggi
---

The Olympic Games in Rio are over! It’s too bad. We all had fun watching the world’s greatest athletes come together to compete. At these Olympic Games we saw several displays of dominance from competitors such as Usain Bolt, Katie Ledecky, and Michael Phelps. Watching their races, it struck me how easy they made it look, with Bolt laughing in his prelims, Ledecky winning by 11 seconds, and Phelps winning by over a body length in a race that was only two laps in the pool.

<!--more-->

The skill of making it look easy, which comes with learning to relax while exerting maximum effort, is one that takes a lifetime to master, and is a technique athletes work to perfect over years of focused repetition during practice. In an article titled [“Why Joggers Labor and Olympians Fly”](http://www.nytimes.com/2004/08/10/health/why-joggers-labor-and-olympians-fly-the-science-of-the-long-distance-runner.html), exercise physiologist Dr. Robert Fitts says a “good runner should almost be able to run with an apple on their head.” That is hard to do when you’re running as fast as you can.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">13 photos of Andre De Grasse and Usain Bolt having the time of their lives <a href="https://t.co/EHgdq02Ipr">https://t.co/EHgdq02Ipr</a> <a href="https://t.co/8wm6DSUlpQ">pic.twitter.com/8wm6DSUlpQ</a></p>— BuzzFeed (@BuzzFeed) <a href="https://twitter.com/BuzzFeed/status/766451247326953472">August 19, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

This easy-going appearance is an act of deception. Not the nefarious kind of deception, just a benign unintentional ruse. Witnessing awe-inspiring grace in Olympic-level performances distracts us spectators from the years of grueling twice-a-day workouts during which athletes prepare mentally and physically to reach the heights of their ability, sometimes just for a chance to compete in a very short race scheduled years away.

It reminds me of another phenomenon that appears a lot in international development work: data-driven dashboards. Wait, what is the connection? Seem like an analogy stretched a bit too far? Well limber up because here we go: dashboards look amazing, smooth, and effortless. Just click a link and voila, there is every geotagged and timestamped participant in your program on a map, with perfect donut charts and time-series plots informing us about what is relevant and what is happening right now. They are visually stunning. They lull us into a hypnotized face-melting feeling of satisfaction delivered with real-time information supply, bolstering a feeling of awareness, propelling clarity to the forefront where before it was only fog and uncertainty.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">AdminBSB - A free dashboard web template, based on Bootstrap 3.x with Material Design <a href="https://t.co/U72upk9vNa">https://t.co/U72upk9vNa</a> <a href="https://t.co/Ii8OuuEoQc">pic.twitter.com/Ii8OuuEoQc</a></p>— Speckyboy (@speckyboy) <a href="https://twitter.com/speckyboy/status/768916166710558720">August 25, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Deception again! This time in the form of web widgets. Dashboards shield us from the arduous production process we’ll call the **dashboard supply chain**. Following the path of data from the field to the dashboard is a long storied trail of hard work and data transformation involving effort by teams of people. At times it seems to take the shape of a [Rube-Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine) designed to deliver a marble a short distance in the most complex method possible. There are data collectors, survey designers, monitoring and evaluation managers, weather-sensor managers, coders, drivers, and vehicles to transport all these people. And that is just the data collection. Then comes data preparation and cleaning, which is one of the most challenging pieces of the process and one where data scientists say they spend between 60 and 80 percent of their time. Then it’s transformation time: data must be shaped into a format that the dashboarding system understands, or exposed as a web service from which the system can request it. The presentation of the data needs a reliable back-end that serves data to a mobile-ready front-end with crystal clear presentation, one that meets the high standards of digital design we have today.

It is 2016 mind you, and parts of the **dashboard supply chain** are much better than they were only a few years ago. There are great dashboard templates and better data-processing libraries in Python and R. Even new versions of Excel have great visualization features. However, like expanding an already busy interstate only to see it clog up again, sometimes more room for throughput leads to more demand for dashboards that serve powerful information displays quickly and accurately.

Dashboards are hardly insurmountable mountains that no one should attempt to summit. They are incredibly useful for informing decisions. However, taking a closer look at your **dashboard supply chain** before building one is recommended. Starting small with a manageable data flow is a good way to begin. Tools like R Shiny, Google Data Studio, Tableau, PowerBI, Bootstrap, and D3 are great for making your data display run fast while balancing apples on its head.