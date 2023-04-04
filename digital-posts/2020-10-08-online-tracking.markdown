---
title: 'Understanding Data Tracking: Tips, Tricks, and Tools'
date: 2020-10-08 09:30:00 -04:00
tags:
- Data
- Privacy
- Digital Literacy
- Tracking
Author: Trevor Olexy
social-image: "/uploads/trevorblogpic.jpg"
thumbnail: "/uploads/trevorblogpic.jpg"
---

I don’t think it will ever be possible to overstate the importance of data privacy. I also don’t think it will be possible to overstate the necessity of digital literacy. And unfortunately, I don’t think it will ever be possible to completely protect our online selves from data harvesting or tracking. However, there are measures we can take to keep our data where it belongs. These measures can be taken by anyone using a phone with access to the internet and help keep us from being tracked.

<!--more-->

![blacklight_result.png](/uploads/blacklight_result.png)
`Website scan by BlackLight that uncovers how you are being tracked when visiting a page.`

As development practitioners, I can’t overstate the need for digital literacy around data privacy and how users around the world can protect themselves just with even a small amount of knowledge. I will be the first to point out that this post contains complex information, but I think understanding some of the methods, novel or otherwise, that websites or companies use to track our online presence is the first step we can take to protect our privacy online.

Here are some questions I want you to ponder as we delve into this topic:

1. **Does it matter to you that your online experience is tailored?**
2. **If you could manually manipulate your social media feed, would you?** I would venture to say most people are quite comfortable in their current social media environment. After all, that is the point of recommender algorithms, to give you things that you already like or might also like.
3. **If you did curate your own social media experience, do you think it would be any different than it is now?** Would the intentionality behind the decisions actually make a difference in what you follow (social media) or search for (general online presence)?

## Who Doesn’t Love Cookies?!

Let’s wish we were eating cookies and instead talk about your *browser’s* cookies. Cookies are basically small packets of information about you, your computer, and your visits to sites. The actions of cookies can even sometimes be flagged as malicious by virus or malware scanners. Cookies are persistent, meaning they are stored in your browser (aka on your computer) until a self-prescribed expiration date. There are two main types of cookies:

**1. First-party cookies** are only used by the site that created them and help your browser “remember” that you are already signed-in to a site when you go back. You don’t want to have to log in to a site every time, do you? Super helpful, right? But…
**2. Third-party cookies** are the ones that get sneaky.  According to [Privacy.Net](https://privacy.net/stop-cookies-tracking/) *"third-party persistent cookies are accessed on websites that didn’t create them. This allows the cookie’s creator to collect and receive data any time the user visits a page with a resource belonging to them. You don’t even need to click on an ad or social media sharing button for a tracking cookie’s information about you to be transmitted back to a server owned by the person or company who created it. As soon as you load the page, the cookie is sent to the server where it originated."* This is often how numerous sites know about your actions and purchases on other seemingly unrelated sites. Personally, I don’t explicitly allow third-party sites to have my information, but by using sites with agreements hidden in fine print, perhaps I inadvertently have.

### How You Can Protect Yourself

1. **Delete all of your current cookies.** Unless you want to individually go through the likely thousands of cookies you have on your computer at this point, this is the most surefire way to succeed. **WARNING**: *This will subsequently require you to re-log in to all of the sites you have previously visited*. You know those “remember this computer” checkboxes? Well, they add that site’s cookies so you’ll have to click those again next time you log in. If you use a password manager like one I have talked about in a [previous post](https://dai-global-digital.com/personal-digital-security-the-beginning.html), this step will pose less of an issue.
2. **Block third-party cookies** (see image with instructions below). Tracking ads can also be blocked so you don’t see them but this still means you are likely being targeted using the information that third-party tracking cookies have already gathered about you. While you can’t force those companies to delete the information they have stored, whatever it may be, you can prevent future collection. Do this and you will quickly see that some sites may not work 100 percent as you might expect. A profile image avatar might be broken because the site directly links to Facebook and uses your profile picture, but you may want this type of thing out of convenience and need to slightly modify your settings. [Privacy Badger](https://privacybadger.org/) makes this granular customization very easy.

![3rdpartycookie.png](/uploads/3rdpartycookie.png)`Example of where to block third-party cookies in Chrome. If you do not use Chrome, search for how to do this in your browser of choice, the terminology will be similar.`

## Browser Fingerprinting

Browser fingerprinting works on the idea that the configuration and attributes of a user’s browser, location information, and system hardware properties differ enough that they can be used to deanonymize internet activity. This is an interesting yet still concerning concept. When you send a request to a website to view it, that request also includes a lot of information about you, and actually, detailed information about your computer itself.

This might seem innocuous at first, but this would enable any server/entity to potentially correlate stored information from company databases and first- or third-party cookies to identify you. Using a virtual private network will hide your exact location, but will not protect you from identification through browser fingerprinting.

![scan_1.png](/uploads/scan_1.png)`Basic browser fingerprinting scan result.`

These are screenshots from a test using the Electronic  Frontier Foundation’s browsing tracking scanner, [Panopticlick](https://panopticlick.eff.org/). It provides helpful information about what protections are already in place. I won’t go into the details of the above results, but a quick Google search for remedies to these issues might be in order. The solutions could be more technically advanced than some users feel comfortable with. If you are interested in making modifications you are not comfortable with, your friendly IT department might be able to help you or find a tech-savvy colleague or friend to help find the right buttons and configurations.

Below is a table of the “fingerprint” of my browser. The tool can see my installed browser plugins, time zone, screen size, installed fonts (quite a unique fingerprint actually), do not track settings, my graphics card (!), and very basic info about my computer. This information is sent with requests to view a site. If you want to change your plugins or settings to address some of these issues and protect your information, you will actually have a more unique browser fingerprint because the vast majority of users are unaware or unconcerned with these issues. I can’t help but wonder how many browser fingerprint data have been collected by Facebook and Google?  Who has that information been shared with? What third-party/tracking cookies have access to that information? Please, don’t actually answer those questions…

![full_scan2.png](/uploads/full_scan2.png)`Detailed scan result from Panopticlick.`

I did a quick test with a colleague where we cleared our caches and cookies, started a private browsing window, and visited Google Maps. We were in a private browsing window and therefore not logged in. Lo-and-behold, location is dead center on my location. OK fine, Google uses my internet protocol (IP) address to pinpoint me. But I was not logged in. Google must be using a stored IP address or browser information to identify the computer I am on. Additionally, IP addresses don’t immediately tell your *exact* location like that. Often, the most accurate you can get is city and internet service provider (ISP). I’m sure it is not too much of a reach for you to imagine what happens if your ISP has an agreement with Google or Facebook to share your address and exact location. If this is correlated with a list of IP addresses then voila, they know where every computer is.

## **What Can You Do?**

The most immediate change you can make is to follow the steps listed above for removing (or at least pairing down your cookies) and installing and configuring browser plugins like ad blockers, [Privacy Badger](https://privacybadger.org/) (by the Electronic  Frontier Foundation) or [Ad Block Plus.](https://adblockplus.org/)

One clever way to circumvent browser fingerprinting is by using a virtual machine on your computer. This will essentially spoof (aka fake) your hardware configuration and thus, also your browser fingerprint. Some virtual machine software available is Windows Hyper-V (baked-in to Windows), Parallels, and Oracle Virtual Box. This is very technically advanced for most, but there are good tutorials out there if you are brave enough to try this on your own.

There is a fun project I use on my home network called the [Pi-Hole](https://pi-hole.net/), which intercepts all requests from ad trackers (or any URL you specify) and prevent them from being loaded to your browser. It will easily do this for every computer on your network. This is great for removing ads across all sites, but by nature of being intercepted, you have already been tracked, so this is just for user experience improvement. It certainly improved my browsing experience!

You can also visit this [Google settings site](https://adssettings.google.com/) to adjust your ad personalization settings from Google. It is a daunting list but interesting to see what they have compiled about you as an online individual. It is important to note that this is likely only for allowing or denying Google to personalize the ads based on what it knows about you and almost certainly does not mean you are not being tracked, regardless of your settings.

![ad_personals.png](/uploads/ad_personals.png)`Google ad personalization page.`

I know this sounds slightly alarmist, and for some people, it will certainly be concerning. Overall, it is meant to highlight the deeper, hidden, lesser-known level to which our information is uncovered, collected, stored, and used for or against us. Our data and how we interact with an increasingly overwhelming amount of digital information is constantly mined, collected, bought, sold, and used to manipulate the way we interact with the digital world. The least we can do is understand more about it so we can be aware of what ads are targeting us and how they are getting and using the information to target us. We can then use our knowledge to address the ads or remove them completely.

As I was writing this, a colleague sent me information about a new tool, [Blacklight](https://themarkup.org/press-release-20200922/) (example output at the top of the page), to check websites for how they track your visit and what they are tracking. This tool is fantastic and after reading this article I recommend you check various websites you visit. You might be surprised, or terrified. Briefly, Facebook has code in many pages that can track whether you viewed a page or specific content, if you added payment information, or ended up making a purchase, without being logged in to Facebook. It certainly makes me worry.

Do you truly enjoy the experience you get of being tracked and served up a tailored experience based on your previously watched videos, purchased clothes, sites you visited, links you clicked? If the answer is yes, then go forth and be happy. I know when I am shopping online during this pandemic, I often find a tailored experience useful, to a point. But, if you are like me and more than a little concerned about what is being tracked and how it could be used, I would recommend diving in so you can find the privacy solutions that work best for you and your desired online experience, starting with the recommendations made here.