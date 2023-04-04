---
title: How Satellite Imagery and ‘Light at Night’ Helps Development Practitioners
  Estimate GDP
date: 2021-06-03 08:00:00 -04:00
categories:
- Data
- Data Analysis
- Innovation
tags:
- GIS
- Satellite
- Imagery
- Imagery Analysis
Author: Trevor Olexy
social-image: "/uploads/712130main_8246931247_e60f3c09fb_o.jpg"
thumbnail: "/uploads/712130main_8246931247_e60f3c09fb_o.jpg"
---

I am sure many of you have come across a map like the one below. I find that images of our planet are always awe-inspiring and this image is certainly not an exception. I can easily get lost in satellite imagery for hours if I am not careful. Most of those images are based on visual spectrum optical technology (LandSAT, Sentinel, etc.), thus requiring daylight for the powerful digital cameras to “see.” Remote sensing satellites such as [VIIRS](https://ncc.nesdis.noaa.gov/VIIRS/)—which DAI uses for its analysis—are equipped with special infrared equipment and able to capture beautiful images of the earth at night!

![712130main_8246931247_e60f3c09fb_o-df5bef.jpg](/uploads/712130main_8246931247_e60f3c09fb_o-df5bef.jpg)`Source: NASA and DMSP.`

<!--more-->

While these images pique visual curiosity, there is a hidden power lurking just beneath the lightly dotted landscapes. It is plain to see that the images in the photo above highlight locations where there is concentrated human activity after the sun sets. This is important because this nightly activity corresponds to areas of increased population density (naturally) and increased economic activity or gross domestic product (GDP) output.

For several years now, researchers (myself included) have been using various spatial and statistical methods paired with night lights data to enable reasonably accurate estimates of subnational GDP. This is especially useful in regions or environments where data is scarce, non-existent, too dangerous to collect, or too inaccurate to be of much analytic use.

Additionally, GDP data is often only available at a national scale ([gross regional product](https://unstats.un.org/unsd/economic_stat/China/background_paper_on_GRP.pdf) availability aside), providing little to no context or statistics for economic output at a subnational level. With this data, we are able to estimate the economic output of subnational areas by combining a wide array of open-source data and spatial data processing techniques. Briefly and at a high level, one method we can use is to take the national GDP broken down by sector in the United Nations International Standard Industrial Classification registry and distribute the total value across all locations coded as a particular industry or sector. These values are weighted based on their location in terms of the intensity of satellite recorded night lights, which we are using as a proxy for the intensity of overall economic activity. Subnational agricultural production can be estimated by including land-use layers in combination with normalized difference vegetation index (NDVI) or other appropriate vegetation index values during peak crop production season as a means to weight agricultural output based on vegetation health. Values can then be aggregated by subnational region, city, or even to a grid according to a custom analytic resolution, allowing for the display of subnational GDP.

![north_korea.png](/uploads/north_korea.png)`Source: NASA & DMSP.`

One example can be seen above. I bet it is not difficult to pick out where North Korea is, and inside North Korea, which blips of light are coming from Pyongyang. The overall darkness in North Korea stands in stark contrast to neighboring South Korea and Japan, both of which have industrialized economies with high GDP output. From a purely visual analysis, we can confidently surmise that the GDP output of North Korea is rather low, and we would be correct.

There is a caveat here in that this technology does not directly account for economies that are more heavily based in agriculture or those not as widely electrified. These economies will have far greater land areas where little to no light will be emitted, potentially skewing results if analysts don't take key information like this into account. Take a look at the rainforests in Africa and South America and any areas with wide swaths of desert (or ice). You will not find much light coming from these places, but this does not by any means indicate there is no economic output at all, simply less than locations where tens, hundreds, thousands, or millions of people concentrate and subsequently interact and trade heavily beyond sunset. This dataset has a wide range of values for the light it captures and this is where visual analysis in a vacuum becomes limited. While the human eye cannot perceive a difference in this map, the infrared sensor on VIIRS is more discerning and this variability shows up in the dataset. Those dark areas you see can actually still be quite active!

![africa_night.png](/uploads/africa_night.png)`Source: NASA & DMSP.`

There exist numerous methodologies designed and tested in academia that calculate estimated GDP or economic activity based on night lights that I won't get into in this article, but it is important to note that these methods are to be taken as reasonably accurate proxies for economic activity. We are always talking estimates here and no analysis is perfect, but the value of this data to increase awareness of human activity and aid in decision-making cannot be understated. I believe these data provide maximum benefit and are best used when combined with other data sources and analytic methods to add clarity to hypotheses and robustness and insight to analytic results.

DAI’s Center for Digital Acceleration is using this type of data whose use-case and applicability is almost endless. I am excited to be part of the team integrating this satellite imagery into our ongoing sub-national analysis to help inform DAI’s projects on key areas to target interventions and development activities.