---
title: 'How to Run an Electronic Cash Transfer Program: A Kenyan Case Study'
date: 2017-05-15 10:21:00 -04:00
tags:
- Kenya
- Electronic Cash Transfer
- Economic Growth
Author: "[Karim Bin-Humam](/authors/karim-bin-humam/) and [Anand Varghese](/authors/anand-varghese/)"
thumbnail: "/uploads/introphoto.png"
---

Working on an ICT team can sometimes feel like being the [Morpheus](https://en.wikipedia.org/wiki/Morpheus_(The_Matrix)) of the development world—all we want to do is show development project teams that digital tools can unleash immense potential. So we try our best to sneak ICT elements into projects in any way possible: short blurbs in project proposals, ICT strategy documents while on technical assignments in the field, or straight-up bribery. Whatever it takes to sugarcoat the red pill. So imagine our surprise when we were asked to meet with a DAI-led project that *already* has multiple ICT tools integrated into its workflow: the  Kenya [Hunger Safety Net Programme Phase 2 (HSNP2)](https://www.dai.com/our-work/projects/kenya-hunger-safety-net-programme-phase-2-hsnp2), funded by the U.K. Department for International Development.

![introphoto.png](/uploads/introphoto.png)

<!--more-->

While Kenya is known as one of the most connected countries in sub-Saharan Africa, what makes HSNP2 unique as a technology-driven project is that it is focused squarely on the pastoral communities in the arid northern regions of Kenya—specifically those largely off-grid communities that have the least access to technology. HSNP2 focuses on providing up to 100,000 households in four northern counties (Mandera, Marsabit, Turkana, and Wajir) with regular cash transfer payments every two months, and can scale up to provide emergency cash transfers based on prevailing drought conditions. 

The ultimate goal of these cash transfers is to reduce poverty, hunger, and vulnerability in the focus counties, resulting in better and more sustainable safety nets for poor and vulnerable households. To do this, HSNP2 has integrated a number of digital platforms into its work: (a) an e-payments system, (b) a remote sensed drought early warning system, (c) a text message and interactive voice response-based communications and case management system, and (d) a bot built on the popular messaging app [Telegram](https://telegram.org/), which we [reviewed](https://dai-global-digital.com/app-a-thon-2016-telegram-for-development.html) as a part of [App-A-Thon 2016](https://dai-global-digital.com/tags/?tag=appathon-2016).

## e-Payments System

![Picture1.png](/uploads/Picture1.png)

The heart of the project lies in a cash-transfer system that uses fully functional bank accounts, and allows the project to centrally manage the disbursement of payments directly to beneficiary bank accounts. Setting up this system required significant footwork: reaching off-grid communities through rural agent networks and leveraging banking network agents, on-site program officers, and community leaders to set up beneficiaries with personal bank accounts and ATM cards linked to those accounts. Each qualifying beneficiary receives an ATM card with 2-Factor authentication security that can be used with a personal identification number or biometric data. This card is then used to withdraw funds delivered by the project from payment agents, ATMs, or brick-and-mortar bank branches. Text messaging and interactive voice response-based communications platforms inform beneficiaries their bank account has received funds, and also when and where they can use their cards to withdraw funds.

## Satellite-Powered Drought Early Warning System

![Picture4-dea765.png](/uploads/Picture4-dea765.png)

To help the HSNP2 project plan cash transfers—particularly emergency subsistence support transfers—the project employs an automated satellite-based early warning system that monthly monitors the area’s Vegetation Condition Index, a measure of dryness and the availability of pasture for livestock. When these indices reach “severe” or “extreme” thresholds at the sub-county level, the system automatically calculates a quota of households that are to receive scaled-up payments due to their increased drought exposure. This subsystem means that the project adapts payment schedules automatically based on updated satellite information and ensures that those households in greatest need receive e-cash payments from an early stage in the drought cycle, helping mitigate adverse impacts felt at household level.

## SMS and IVR Communications and Case Management

Since many of the project’s beneficiaries move from place to place, creating reliable channels of communication can be a challenge. So HSNP2 has set up a text and interactive voice response-based system for the project’s field representatives to collect and address complaints from beneficiaries. Not only will the system cover 50,000 beneficiaries across all local telecoms, it is also extremely cost-effective. It only costs the project 1 KSH (1 cent USD) per text and 2 KSH per automated voice call (at a flat per-call rate, not per-minute). The system integrates via an API with HSNP2’s data management environment.

## Telegram Bot

The project’s 124 field-based program officers were often having to send in requests to the project’s central system to get up-to-date information on beneficiaries and their status. To automate this process, the project developed a bot on the popular messaging app Telegram (due to its open API). The bot’s current functionality is pretty basic—it allows officers to send in beneficiaries’ ID numbers and returns whether they are currently part of project’s payroll system. But the project is building out new search criteria to help streamline and decentralize the officers’ workflow and reduce their day-to-day dependency on the project headquarters.

![Picture3.png](/uploads/Picture3.png)

## HNSP2 Proves It Can Be done

[HSNP2](http://www.hsnp.or.ke/) is a shining example of a project that has managed to integrate multiple technologies and communications channels to mesh into a coherent, centrally planned and managed system. It also demonstrates how these technologies can be seamlessly integrated into human-centric processes, enabling maximum efficiency in an environment that is extremely challenging. Getting cash to people in semi-arid areas in the North is cumbersome? No problem: set up a fast electronic transfer system. Our target population doesn’t have bank accounts? No problem: leverage local networks to register them. Our population is itinerant and hard to locate? No problem: go to them and set up a system that automatically lets them know where they can get service nearby. We need to be quick to react to changes in the climate? No problem: use satellite data and link it directly to our beneficiary database to let us know how much to pay whom when.

**Our take-away**: If a project operating in such a digitally constrained environment can do so much with technology, there’s no reason why any of our other projects should be apprehensive about using digital tools!