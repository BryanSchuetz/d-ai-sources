---
title: What Good Is the Internet of Things to People Who Don’t Have the Internet?
date: 2017-01-13 14:34:00 -05:00
tags:
- Innovation
- Think Piece
Author: "[Rob Ryan-Silva](https://www.dai.com/who-we-are/our-team/robert-ryan-silva)"
thumbnail: "/uploads/internet-of-things-concept-illustration.jpg"
---

As I write this, the annual [Consumer Electronics Show](http://www.ces.tech/) has just wrapped up in Las Vegas, having introduced an allegedly eager public to [smartphone-enabled hairbrushes](http://www.bbc.com/news/technology-38503932), [Bluetooth-capable vibrating hotpants](http://www.spinali-design.com/pages/jeans-essentiel), and [refrigerators that tweet when you’re running low on soy milk](https://www.cnet.com/pictures/feast-your-eyes-on-the-fridges-of-ces-2017/). This is what marketing departments call the Internet of Things (IoT): devices that are networked for sensing, control, and/or coordination. Under the stifling blanket of hype, though, new platforms, network protocols, and data repositories really are enabling applications of value, in addition to the tweeting kitchen appliances which, one hopes, will stay in Vegas.

<!--more-->

![internet-of-things-concept-illustration.jpg](/uploads/internet-of-things-concept-illustration.jpg)

Following the release by Cisco and the International Telecommunication Union (ITU) last year of [an important paper](https://www.itu.int/en/action/broadband/Documents/Harnessing-IoT-Global-Development.pdf) on the topic, a workshop was held in Washington, D.C., to explore some of the opportunities that IoT may bring for solving development problems. Because development implementers are effectively jaded for a living, one of the questions raised was how we could talk about networking devices in the developing world when so many people remain unconnected. What good is the Internet of Things to people who don’t even have internet? It was a thoroughly rhetorical question that elicited the intended chuckles.

Allow me nevertheless to offer one answer in the form of Tepmachcha, an IoT device designed specifically to benefit people who have no access to the internet.

The [DAI Maker Lab](https://www.dai.com/our-work/solutions/dai-maker-lab) works with our projects and their various stakeholders to apply tools and approaches emerging from what is known as the maker movement to development challenges. The same kinds of ingredients that brought software development out of the exclusive domain of big corporations—open standards, open-source toolchains for writing and compiling code, and pervasive connectivity—have now arrived in the world of hardware. Using these toolchains, along with new platforms for designing embedded electronics; digital fabrication equipment; and new models for access to and training on tools, we build devices and capacity to apply technology in new ways in support of our projects’ objectives.

Last February I gave a training for civil society organizations in Cambodia on using such methods to build hardware that furthers their missions. One of the participating organizations, [People In Need](https://www.facebook.com/PINCambodiacz/), approached me about a notion they had to automate flood warnings on their existing interactive voice response (IVR) system. As it was, the system had to be triggered by a local informant who could make a call in the event of flooding. But if the informant were away, asleep, or preoccupied with saving their own life or property, they might not trigger the system in a timely fashion. Given that flooding is a function of a measurable condition—high water—could the alerts be automated?

As it happened, we had already piloted a [sonar-based flood early warning system in Honduras](http://www.networkworld.com/article/3082764/internet-of-things/flash-flood-alerts-how-sonar-iot-systems-help-protect-communities-in-honduras.html). On detecting high water on a monitored river or stream, this system would send a text message alert to a list of subscribers downstream who could then prepare for flooding. But texting is problematic in rural Cambodia; in addition to issues of literacy for some users, many phones do not correctly support the Khmer character set, so messages can be rendered as [tofu](http://www.fileformat.info/info/unicode/char/25a1/index.htm).

We adapted the hardware design to trigger a flow using the RESTful API of People In Need’s RapidPro IVR installation. The new unit, called Tepmachcha after a Hindu story immortalized in carvings at Angkor Wat about a fish that warns of a cataclysmic flood, thus can trigger a voice phone call to tens of thousands of area residents on detecting a flood condition, within a matter of minutes. No internet access is required to get the warning.

![bridge.jpeg](/uploads/bridge.jpeg) `A test unit being installed in Pursat, Cambodia`

We installed test units in Pursat and Kampot in September, and are using the output from these to further refine and iterate the design. The People In Need staff have been trained in building, repairing, and reprogramming the units, and we are currently working with them to integrate the units more seamlessly into their overall disaster information system. The system is entirely open source, with the code, fabrication files, and build instructions [available on Github](https://github.com/DAI-Maker-Lab/tepmachcha).

![tepmachcha.JPG](/uploads/tepmachcha.JPG) `One of the Tepmachcha units.`

When a phrase is as embraced as “Internet of Things,” it is tempting to stand cheerfully by while the buzz-merchants beat it to oblivion. But there is no denying the power of being able to use ubiquitous networks to connect, as in the case of Tepmachcha, real-world inputs—such as rising water—to real world outputs, like a phone call, or a pump turning on downstream.