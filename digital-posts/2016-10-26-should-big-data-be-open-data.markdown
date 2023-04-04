---
title: Should Big Data Be Open Data?
date: 2016-10-26 11:56:00 -04:00
tags:
- Data
- Think Piece
Author: "[Michelle Kaffenberger](https://www.linkedin.com/in/michellekaffenberger)
  and [Bill Kedrock](https://www.linkedin.com/in/wkedrock)"
---

*This is a guest post by [Michelle Kaffenberger](https://www.linkedin.com/in/michellekaffenberger), Applied Research Consultant, and [Bill Kedrock](https://www.linkedin.com/in/wkedrock), Independent Consultant. The post uses Nigeria smallholder farmer data collected through the Growth Enhancement Scheme as the backdrop for a set of initial principles to guide those weighing the pros and cons of opening big data.*

We propose that when considering whether big data should be made open, decision makers should apply a litmus test including at least the following three questions, and likely many others according to the specific context of the data. 

<!--more-->

### 1. What level of personal information is contained in the data?

Big data, which can include call data records, GPS coordinates, and mobile money transactions contains [an incredible amount of personal information](http://cis-india.org/papers/ebola-a-big-data-disaster). The smallholders database in Nigeria, for example, contains sensitive data points including the farmer’s national ID number (the equivalent of a social security number), e-money transaction data, bank account ownership, size of the farm, and GPS coordinates. Making this level of personal information publicly available is poor practice in any context—would you want the world to see your bank account transactions?

In addition, even if the data is “anonymized” by removing data points that directly identify someone (such as name, identification number, and GPS coordinates) it is now notoriously [easy to determine an individual’s identity based on correlations](https://www.wired.com/2015/02/powerspy-phone-tracking/). The ability to mine anonymized data for individuals’ information suggests that: (1) extreme care must be taken to ensure enough information is removed from the data set during the anonymization process that an individual cannot be personally identified, and (2) big data should be released only at an aggregated level, permitting analysis of aggregate consumer data at a district or county level, but not at the individual level.

### 2. Are the individuals comfortable with their data being shared publicly? Have they consented to sharing, and if so, do they understand what they consented to?

If data will be shared openly, consumers should have the option to opt-in (or not) through an informed consent process. In this way, the default is that their information is kept private, unless they make an active, intentional decision for it to be shared. [CGAP research shows](https://www.cgap.org/publications/informed-consent-how-do-we-make-it-work-mobile-credit-scoring) that providing simple explanations of data and its potential uses helps consumers make informed decisions about when they share. Looking at our smallholder farmer data from Nigeria, there was no request to opt-in to data sharing, and no consent sought from farmers. Without their explicit consent, including an adequate explanation of how their data could be used (such as for targeted marketing), the farmers’ data should not be shared.

### 3. How will the data be used? How will this affect the poor?

In [Kenya](http://www.cgap.org/publications/proliferation-digital-credit-deployments), for example, the use of big data to assess creditworthiness and extend loans has been growing rapidly, with [mixed outcomes](https://www.cgap.org/blog/digital-credit-kenya-time-celebration-or-concern). Many customers have benefited from increased access to credit. At the same time however, credit offers are often promoted through [blast SMS which tempt customers](http://www.cgap.org/blog/digital-credit-consumer-protection-m-shwari-and-m-pawa-users) to take out loans they don’t need, with poor disclosure of costs and fees, and with annual percentage rates that are [in excess of 200 percent](https://www.cgap.org/blog/digital-credit-kenya-time-celebration-or-concern). Without proper safeguards, this easy access to credit—which the consumer may or may not have sought in the first place—can lead to a cycle of debt.

For smallholder farmers, it is common to need loans to buy fertilizer and seeds at the beginning of the season that can then be repaid several months later after harvest. Big data-driven digital loans, as currently offered, would not meet this need—the digital loans are typically small and have short repayment periods (seven to 30 days). Yet, once data is publicly available to banks or other providers, there is a temptation to push a product even where there is a mismatch, leaving the borrower exposed to unneeded debts and default. Because of this, calls to make the data open could put farmers’ sensitive information at risk, without providing adequate benefits to make that a worthwhile tradeoff.

## Not All Data is the Same

The push to make data open—prominently supported by the [World Bank](http://www.worldbank.org/en/topic/opendevelopment/overview) and [the U.S. Agency for International Development (USAID)](https://www.usaid.gov/sites/default/files/documents/1868/ADS579FactSheet 2015-02-13.pdf), among others—has had an incredible impact on the quantity of data available for development-oriented research and for understanding the lives of the poor. However, not all data is the same. To date, many efforts to make data open, such as by the World Bank and USAID, relate to survey data (e.g., data collected via door-to-door household interview, or as part of a projects or program evaluation). This type of data has usually been collected as a public good (e.g. with public money), and can be anonymized before being made “open.”

These factors are generally not true of big data, which is why we must be careful when deciding whether to make it open. One approach to big data is to put individuals in control of their own data. This could be through an opt-in option (see point No. 2 above) or through more direct control by the individual of the data gathered. For example, a Nigerian farmer might provide a lender the information necessary to secure a loan (such as an e-wallet statement showing transaction history), while not opting in to the public release of his/her data, thus keeping it out of the public domain.

Another approach would be to segment information into three buckets—(Green) could safely be made public; (Yellow) if aggregated or sufficiently anonymized may be made public; and (Red) should not be made public. For example:

### Segmenting big data

| Red—Not to be made open          | Yellow—Possibly made open with appropriate precautions | Green—Can be made open                                |
|------------------------------------|----------------------------------------------------------|---------------------------------------------------------|
| Names                              | CDRs, with appropriate safeguards and consent            | Aggregate figures (60 percent of District X uses mobile money) |
| Phone numbers                      |                                                          |                                                         |
| GPS coordinates                    |                                                          |                                                         |
| Mobile money transaction records   |                                                          |                                                         |
| Identification numbers (e.g. SSNs) |                                                          |                                                         |

## Big Data as Open Data is a Two-Edged Sword

There is much that can be learned from big data that can benefit marginalized populations such as smallholder farmers. Additionally, poorly conceived data releases that enable access to individuals’ information can lead to misuse of such information to the determent of the individual. In light of often inadequate consumer protection regulations regarding data privacy, the burden in many cases falls on other stakeholders—companies or governments that hold or control data, donors and funders who hold influence, implementing organizations, and others involved in decision-making—to decide which data to share and when.

<aside>
<p>Some weeks back Bill wrote an <a href="http://www.ictworks.org/2016/08/15/big-data-needs-to-be-open-data/">ICTWorks blog post </a>on the benefits of turning big data into open data based on a presentation by Dr. Debisi Araba at <a href="http://merltech.org/">MERLTech 2016</a>. Bill concluded by calling for donors and others to assist countries like Nigeria as they grapple with the opportunities and challenges of open data. Since the post, the recently published <a href="https://www.usaid.gov/sites/default/files/documents/1867/USG-Global-Food-Security-Strategy-2016.pdf">USAID Food Security Strategy </a>notes that, “Open and accessible data are essential assets that provide a foundation of evidence for scientists and decision-makers globally and help fuel entrepreneurship, innovation, and scientific discovery in food security and nutrition.”</p>
<p>In response to Bill’s post, Michelle Kaffenberger, who is helping launch a new data privacy initiative at <a href="https://www.cgap.org/">CGAP</a>, reached out to him to raise a number of questions regarding risks associated with making big data open.</p>
</aside>
