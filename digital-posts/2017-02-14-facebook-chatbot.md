---
title: I Made a Facebook Chatbot (And You Can, Too)
date: 2017-02-14 14:46:00 -05:00
tags:
- Innovation
- Think Piece
Author: Adam Fivenson
thumbnail: "/uploads/pixabey.PNG"
---

When I first heard that [Facebook Messenger was introducing](https://techcrunch.com/2016/04/12/agents-on-messenger/) chatbots, I immediately thought back to junior high summers. Back then I was spending a lot of time in my parents' basement on the computer--safe from harmful things like sunshine and other people--getting into flame wars with people on [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) that (more often than not) turned out to be chatbots. Not my greatest summer. Fast forward some 20 years, and chatbots are back with a vengence, this time with a significantly improved value proposition: (near) last mile access to native language information and services. 

![pixabey.PNG](/uploads/pixabey.PNG)

> [Primer: What is a Facebook chatbot?](https://blog.hubspot.com/marketing/facebook-bots-guide)

Our [Digital Insights](https://dai-global-digital.com/tags/?tag=digital-insights) research in [Indonesia](https://dai-global-digital.com/where-whatsapp-is-just-another-bbm-clone-digital-insights-indonesia.html), [Honduras](https://dai-global-digital.com/mobiles-in-central-america-digital-insights-honduras-part-2.html), and [Palestine](https://dai-global-digital.com/consumer-insights-palestine-e-governance-readiness.html) emphasized the popularity of Facebook and FB Messenger in the marginalized communities where DAI and other development implementers work. In Indonesia, 77 percent of the people we interviewed said they use Facebook on their phones; in Palestine that number was **95 percent**. In Honduras, 80 percent of our respondents across urban and rural areas said they use Facebook. If development projects want to reach people with information and services, we must meet them on the platforms where they already spend time: in more and more cases, as access to the internet, smartphones, and social media grow, that means on Facebook. (No, not exclusively and not in all instances. read our [Indonesia post](https://dai-global-digital.com/where-whatsapp-is-just-another-bbm-clone-digital-insights-indonesia.html), and see which social media messaging app is king there.) 

<!--more-->

## Why Chatbots?

A chatbot presents some distinct advantages as an outreach and engagement tool:

1. As users move [from traditional broadcast social media to private messaging apps](http://www.businessinsider.com/the-messaging-app-report-2015-11), the challenge for the Facebooks of the world (OK, there's only one) is how to stay relevant in a Snapchat world. Facebook's answer, as of April 2014, was to grandfather Messenger in as a replacement to the traditional Facebook private messaging function on mobile phones, pushing users to download Messenger. The result is that **a lot** of people have Messenger on their phones: somewhere around a billion, in fact. Only Facebook's other messaging app, WhatsApp, rivals Messenger in terms of global uptake.

2. The need to download and install apps is a barrier to entry for many people. Many phones come pre-loaded with Facebook and WhatsApp, many users only have spotty access to mobile data and WiFi, and many have limited on-board memory, making it difficult to introduce and install an entirely new app. As [The Economist duly notes,](http://www.economist.com/news/business-and-finance/21696477-market-apps-maturing-now-one-text-based-services-or-chatbots-looks-poised) "Building apps and promoting them is getting more costly. Meanwhile, users’ enthusiasm is waning, as they find downloading apps and navigating between them a hassle. A quarter of all downloaded apps are abandoned after a single use." As an app designer myself (see the [municipal budget transparency app](https://dai-global-digital.com/citizen-centered-design-guatemala.html) we just launched in Guatemala), my experience has been that there are instances where it does make sense to develop an app, but often times it's easier to introduce a new service through a familiar interface and platform (i.e., FB Messenger) than trying to introduce an entirely new app or web site. 

3. Chatbots generally require less bandwidth than loading a web page or downloading an app to your phone, and mobile data is expensive! According to [A4AI's 2015 Internet Affordability Report](http://a4ai.org/affordability-report/report/2015/#the_affordability_drivers_index_(adi)), people in some countries pay upwards of 40 percent of their income for mobile access. In that context, every kilobyte counts! Lighter data usage lowers the cost of [ordering food](https://www.facebook.com/messages/t/pizzahutus), [checking the weather](https://www.facebook.com/messages/t/hiponcho), or [diagnosing an illness](https://www.facebook.com/HealthTap/). 

4. I don't know about you, but any time I have to spend more than 2 minutes on an IVR or automated call-in line, I mash the 0 key until I get a human on the line. Similarly, if they're well designed, chatbots can be a more intuitive form of interaction than a web page or app for a user (or call-in line). From the perspective of the average concerned citizen, it's probably easier to open up Facebook Messenger and have a conversation with a municipal "representative" (chatbot) to report a downed telephone pole than it is to use even even the best-designed SeeClickFix-style system. 

5. From a management perspective, a chatbot is essentially a nearly-free way to take the burden off staff for answering clients'/citizens' questions, take orders, and provide information, freeing up staff time to focus on other work. 

## Building a Bot

[Chatfuel](http://www.chatfuel.com), [Botsify](https://botsify.com/), and [OnSequal](https://www.onsequel.com/) (among others) all make the process of creating a chatbot simple enough even for a code dunce like myself, as a recent posting in Social Media Examiner--[How to Create Facebook Messenger Chatbots--](http://www.socialmediaexaminer.com/how-to-create-facebook-messenger-chatbot/)showed. I chose Chatfuel because the tutorial in Social Media Examiner gave detailed instructions on the platform and it seemed easy enough to follow.

## Siti, Job Search Bot for Indonesia

What did I build? My chatbot uses natural language (yeah, it's in English; my Bahasa game is weak) to make it quick and easy for Indonesians to scan three popular job web sites: 1) [JobStreet](http://www.jobstreet.co.in), 2) [Jobs in Jakarta](http://www.jobsinjakarta), and 3) [JobRank](http://www.jobrank.org/id/) for jobs in their town. It asks the user to enter a location and job interest, which it turns into a Google query. The bot presents the results as a gallery of clickable sliders, which take the user directly to the job listing. Check it out: [https://www.youtube.com/watch?v=LS32bAUT1CM](https://www.youtube.com/watch?v=LS32bAUT1CM)

<iframe width="560" height="315" src="https://www.youtube.com/embed/LS32bAUT1CM" frameborder="0" allowfullscreen></iframe>

## Now, Try Siti Live

[![blue-button-hi2.png](/uploads/blue-button-hi2.png)](https://www.messenger.com/t/1276881939061378)

*Click the button or search for Siti in Messenger*

How did I make this bot? It was surprisingly easy.

1. I made a [Chatfuel](http://www.chatfuel.com) account and linked it to my Facebook account.

2. I made a [Facebook page](https://www.facebook.com/Siti-1276881939061378) for my chatbot. Frankly, it's not a landing page, and few people will ever see it, so I didn't worry about what it would look like.

3. I learned how to design a simple chatbot by setting up a few choose-your-own-adventure style bots and testing them. I won't embarrass myself (or the platform) by sharing them, but Chatfuel's GUI is excellent, very intuitive, and they have [tutorials](https://help.chatfuel.com/facebook-messenger/) that walk you through the process step-by-step. It's a relatively easy system to learn once you start to play around a bit. 

4. I checked Google to figure out which job sites were most popular in Indonesia and built them into my search engine (see step 7).

5. I looked through those job sites, categorized the jobs, selected the most popular locations and put them into the app's workflow as lists of choices (the app also allows the user to type in their location and preferred job if either is not on the list). I also wanted to ensure that the list options' syntax was consistent to what the job pages I included used, as the list options are what the bot uses to design the Google search string. 

6. The most difficult part was setting up the Google search function within the chatbot. But, once again Chatfuel provided an [excellent tutorial](https://help.chatfuel.com/facebook-messenger/plugins/google-search/) on how to handle it.

7. Lots of user testing! I spent a lot of time running through the app to make sure that its responses actually made sense throughout the conversation. I also reviewed the job results provided and removed a few of the pages I had initially included for the search engine because they provided poor results. Finally, I finagled a few friends into trying it out, helping me suss out typos and non-natural language, and general errors in flow. 

8. There are many more features and plugins that I haven't even tried yet in the Chatfuel platform, including an option to include natural language processing and machine learning. I haven't incorporated those features yet, but I'll be looking to do so with my next bot. 

## Relevance to ICT4D

Chatbots are a rapidly growing medium as businesses, governments, civil society organizations, and businesses come to understand the their potential. Meanwhile, citizens/customers/constituents are becoming more comfortable communicating with the concept of chatbots through Facebook's active efforts to promote successful bots. This rapid confluence of interest and opportunity is the reason why big companies like Barclays are [taking risks and developing chatbots](http://www.bankingtech.com/483822/barclays-africa-to-trial-first-bank-chatbot-in-africa/) for their overseas audiences.

While Siti is simplistic, it's a useful minimum viable product for the type of innovations--grounded in local tech usage patterns and easy to design and update--that will likely dominate the nexus of technology and international development during the coming years.

## Chatbot Live
ICTworks is re-publishing this post, so I thought it would be interesting to track usage of Siti. Each time someone completes a job search, the bot pulls data on the job and location of the search as well as the user's gender, location, and timezone. No name or personally identifying information is collected. See the graphic below, updated every 5 minutes. 

<script id="infogram_0_8a7b2bcc-3012-4ed1-afd3-ccd9ff2fef29" title="Chatbot" src="//e.infogram.com/js/dist/embed.js?LoO" type="text/javascript"></script>

*Do you have an idea for a cool chatbot for international development? Have you seen a good chatbot in action? Let us know on [Twitter](http://www.twitter.com/DAIGlobal) or [Facebook](https://www.facebook.com/DAIGlobal/).*