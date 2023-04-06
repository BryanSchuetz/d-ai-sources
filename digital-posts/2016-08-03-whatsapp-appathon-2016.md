---
title: 'WhatsApp for Development: the Launch of App-a-Thon 2016'
date: 2016-08-03 14:42:00 -04:00
tags:
- Appathon 2016
Author: Kristen Roggemann, Adam Fivenson, Anand Varghese
thumbnail: "/uploads/WhatsApp_Logo_1.png"
---

*As we’ve ramped up our [Digital Insights](http://dai-global-digital.com/tags/?tag=digital-insights) work over the last few months, we’ve had the opportunity to talk with people around the Middle East, Latin America, Asia, and Africa about the digital tools they use to stay in touch with each other and the world around them. These conversations have reminded us that we have to work hard to stay on top of the growing number of messaging apps on the market today, as what was popular six months ago might no longer be today. “App-a-Thon 2016” is our way of quickly immersing ourselves in different messaging apps to learn about their functionality, look and feel. How does it work? The entire DAI ICT team signs up for a platform, and for one week, we use it to chat with each other, send images and video, and explore the quirks and features of the app.*

*This week, we begin with one of the most popular* -- WhatsApp.

<!--more-->

![WhatsApp_Logo_1.png](/uploads/WhatsApp_Logo_1.png)

**Key Functionalities**: Send and receive encrypted messages through mobile web (including low-bandwidth environments), create group chats (max 256 members) and a contact list, broadcast messages out to contacts who have your number in their contacts list, send video, photos, and audio messages, make voice calls

**Pros:** One of the most widely used messaging apps, often comes pre-loaded on phones sold in emerging markets; easy user interface with quick, clean functionality; functions very well in low-bandwidth environments; has web user interface for desktop platform management

**Cons:** Relatively small group and broadcast list limits; lacks richer profile or public feed capabilities of some of the other messaging apps we tested; no public API to build services or platforms on top of

# **Commentary**

**Anand**

WhatsApp’s popularity is a result, no doubt, of its super-simple user interface. This is good news for development projects that are trying to bring in first-time smartphone users. Who needs confusing public feeds and GIF searches? WhatsApp sticks to its core messaging function, and as a result, it has one of the least cluttered interfaces among the apps we tested during App-a-thon. My experience with [WeChat](https://web.wechat.com/) (which we’ll feature in an upcoming post), was the exact opposite. Additionally, WhatsApp’s voice calling feature appears to be pretty lightweight, which is great for people going out to the field. In places with weak wifi where Skype calls have dropped, I’ve found WhatsApp calls to be much more reliable.

WhatsApp’s [Broadcast List](https://www.whatsapp.com/faq/en/general/23741782) feature is also likely to help projects who don’t want groups to get out of hand with spam, banter, or worse. This feature allows you to blast a message out to a number of people on your list, but they’ll receive it as an individual message from you. Keep in mind, though, that recipients (and WhatsApp itself) are a couple of steps from blocking senders, so make sure to broadcast content that won’t be deemed as spam.

There’s also been much excitement about the new end-to-end encryption feature, but as this useful Quartz [article](http://qz.com/656035/whatsapps-new-encryption-wont-protect-you-unless-youre-also-doing-all-these-things/) points out, “before you start using WhatsApp to plot your overthrow of the global capitalist regime, bear in mind that intercepting your messages in transit is just one—indeed, possibly the least likely—of the ways a hostile party might try to snoop on you.” This is to say nothing of countrywide bans that can arise when an entire government bears its weight down on WhatsApp users. Just ask people in [Brazil](http://www.cnn.com/2016/05/02/world/whatsapp-suspended-brazil/) or [Zimbabwe](http://qz.com/724702/a-whatsapp-blackout-in-zimbabwe-was-no-match-for-massive-protests-against-mugabes-failing-economy/).

**Adam**

I use WhatsApp every day to chat with project staff and partners in Guatemala, Honduras, and El Salvador. It doesn’t have the selfie lenses, content channels, games, music, or sticker store that [Telegram](https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en), [Messenger](https://play.google.com/store/apps/details?id=com.facebook.orca&hl=en), or [Line](https://play.google.com/store/apps/details?id=jp.naver.line.android&hl=en)—has been a key factor in the app’s explosive growth: WhatsApp reported having [a billion](https://blog.whatsapp.com/616/One-billion) users in a blog post in February 2016. That breaks down to 456,621 new users *per day* between launch in January 2010 and February 2016. That’s faster than Facebook, which [took eight years](http://firstmonday.org/ojs/index.php/fm/article/view/5423/4466)—two more than WhatsApp—to hit a billion users.

As an advocate of civil society and free speech around the globe, I love WhatsApp’s end-to-end encryption, but I do have a major qualm with the system: The lack of true broadcast ability means that messaging large groups of people (a la SMS) is far more complex than simply buying an ad or launching a content channel. While WhatsApp groups are great, they still require that administrators add each additional person individually, and those people must be in the administrator’s contacts list. It’s a smart way to block spam, but in the context of DAI’s work, it means that if we want to use WhatsApp as an outreach tool, it must be through pre-existing networks.

## So what do we conclude?

**Kristen**

WhatsApp is the elephant in the room of any real ICT4D work—impossible to ignore, but difficult to navigate around. It’s frustrating because it’s one of the primary technologies we should be using—it’s about as ubiquitous as it gets, easy for users to understand, and highly functional even in low-bandwidth settings. But because WhatsApp hasn’t opened its API so that third-party systems can manage the messaging platform, it’s difficult to employ it at the enterprise-level that large development projects need for really robust social impact. Additionally, it lacks the channel, broadcast, and large group functionalities of an app like Telegram (we’ll review that soon as part of App-a-Thon 2016).  That being said, because of its sheer user volume and indispensability for its users, we’ll keep pushing for it as part of our larger ‘meet the users where they are’ philosophy, with the hope that WhatsApp opens up its API soon so that we can be even more effective with our ICT4D work.
