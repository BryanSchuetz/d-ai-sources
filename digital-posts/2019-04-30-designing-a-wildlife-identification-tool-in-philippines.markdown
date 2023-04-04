---
title: Designing A Wildlife Identification Tool in the Philippines
date: 2019-04-30 19:16:00 -04:00
tags:
- Human-centered design
- Digital Insights
Author: "[Rachel Clad](/authors/rachel-clad/) and [Alejandro Solis]( /authors/alejandro-solis/)\n"
social-image: "/uploads/phillipines-fauna.png"
thumbnail: "/uploads/phillipines-fauna.png"
---

Human-centered design (HCD)—the design and management framework pioneered by greats like IDEO.org and taught in countless design and business schools—is taking the development world by storm. And rightly so, in our opinion. HCD’s focus on empathy and creativity helps us design better, more sustainable solutions to some of the most difficult development challenges. We won’t go into too much detail on the broader HCD process or its application in digital development; my colleagues have written extensively on the excellent design work they’ve facilitated in places like [Cambodia](https://dai-global-digital.com/5-tips-for-doing-international-design-research.html), [Nepal](https://dai-global-digital.com/hcd-in-the-field-trading-counterfeit-rupees-for-real-insights.html), and [Guatemala](https://dai-global-digital.com/governance-app-guatemala.html). What we’d like to do today, rather, is tell you about the time we almost perished while shadowing rangers in the forests of the Philippines, and what we learned in the process.

*It is possible there is a bit of hyperbole inserted here. Possibly.*

<!--more-->

## Setting the Scene

Let us start at the beginning and set the scene. Close your eyes and picture a country comprised of thousands of islands (7,641 to be exact), each teeming with wildlife. Picture beautiful sandy beaches, tropical rainforests, and active volcanoes.

Glorious. Welcome to the Philippines.

The Philippines is home to a vast array of flora and fauna. It is recognized by Conservation International as one of only [17 mega-diverse countries](http://www.biodiversitya-z.org/content/megadiverse-countries.pdf), meaning the country harbors wildlife species found nowhere else in the world. [The International Union for the Conservation of Nature and Natural Resources (IUCN)](https://www.iucn.org/) has declared 418 animal species in the Philippines to be threatened, meaning they are either vulnerable, endangered, or critically endangered. The illegal wildlife trade is a major threat to these species and is valued at the equivalent of [US $1 billion](http://pubdocs.worldbank.org/en/997621542735912298/Illegal-Wildlife-trade-brochure-ADBDENR18NovforWEB.pdf). Species like the Philippine Cockatoo (*Cacatua haematuropygia*), tarsier (*Carlito syrichta*) and pangolin (*Manis culionensis*) are highly trafficked and critically endangered.

![Screen Shot 2019-05-03 at 7.44.11 AM.png](/uploads/Screen%20Shot%202019-05-03%20at%207.44.11%20AM.png)`Photo credits (L-R): LMArce, hbw.com/ibc/1079488, Palawan Council for Sustainable Development, Tarsius Project.`

As the country with the largest coastline in the world, countering wildlife trafficking is extremely challenging and requires extensive coordination between the Department of Environment and Natural Resources (DENR), Philippines National Police, Coast Guard, and Palawan Council for Sustainable Development, and organizations such as Conservation International. DAI, as an implementer of [USAID’s Protect Wildlife Project](https://www.dai.com/our-work/projects/philippines-protect-wildlife-protect), supports the implementation of the 10-year Wildlife Law Enforcement Action Plan (WildLEAP). A component of this plan is to support the improvement of wildlife identification skills and illegal wildlife trade reporting. Enter yours truly, Alejandro (Digital Solutions Architect) and Rachel (Design Research Specialist).

Here’s what we knew from a previous round of research: a tool named LAWIN has already been developed by the DENR and is revolutionizing the way forest patrols are carried out by improving the monitoring of forest life, including illegal forestry activities. This tool has been deployed and is currently being scaled. The next step—our task—is to design a tool to improve wildlife protection activities. Research showed us that correctly identifying species —at times challenging for enforcement officers and the public alike—is a priority feature, especially because incorrectly identifying trafficked wildlife on a report results in a technicality that leads to the acquittal of the offender.

## Our Approach

We’ve written [before](https://dai-global-digital.com/lean-design-for-development-a-practical-approach-to-human-centered-design.html) about the importance of designing your solution in the field rather than in a boardroom. In this post, we want to focus on shadowing. The quality of your research defines the quality of your solution, and shadowing your end user in their native environment and/or immersing yourself in a process from their perspective—sometimes called [“walk-a-mile immersion”](https://www.foolproof.co.uk/journal/experience-design-walk-a-mile-immersion/)—is a valuable technique to build empathy. It allows you to challenge your assumptions, develop first-hand knowledge of an experience, and identify new avenues of research. In digital, it’s critically important to understand what’s happening in the field that might impede or promote the use of a tool, especially because we’re also designing a new process. Doing exactly this is how we found ourselves traipsing through the bowels of the Puerto Princesa Subterranean River National Park.

## Our Near-Death Experience

So, we consider ourselves to be fairly in shape (emphasis on “fairly”). But there we were, standing at the entrance of a forest full of lianas (pointed thorns) and wild hogs. It was 93º F with a relative humidity of 90 percent. As we watched the park rangers bound up the mountain in flip flops without breaking a sweat, we began to doubt our hiking prowess. Fifteen minutes in, we were drenched in sweat. Three hours in, I saw my life pass before my eyes. Ale heard angels singing. This would go on for more than eight kilometers. In that time, between near-death experiences and as we were experiencing first-hand how rangers patrol, we learned a few important things. Some highlights:

1. Though LAWIN was being used for the first time by these rangers, the tool was very user-friendly. The design is no-frills, but it clearly works. It was extremely valuable to see what other apps and tools are already being used in the field because they have implications for the design of our tool.

2. The rangers deployed in a team of six-plus people. All were using LAWIN concurrently, which made us think about the design of the tool implementation process. Whatever we design must fit into existing processes. Could we have one of these people use a wildlife identification tool while the other uses LAWIN? Could we combine tools?

3. Wildlife identification could be low-tech or high-tech (think AI). Some of these rangers are using LAWIN on their personal phones, while others are using phones supplied by the government. These phones are fairly basic. Do we design for existing phones or design something for a high-tech phone, ostensibly supplied by the government and used by only one member of the patrol?

4. There are parts of the forest that have phone reception, but in general there is little-to-no cell or internet service. How might this impact the offline vs. online functionality of the tool?

5. The park rangers work in arduous conditions. As we think about this tool, it’s clear we’ll need to design something that’s easy to use and can be used rapidly. This means potentially fewer features. How can we hone it down to only what’s necessary?

6. The patrols last for many hours. We stopped after four hours (due to the near-deathedness of it all), but these rangers would normally have continued for six-plus hours. This has implications for battery life and, again, feature development.

7. In conversation with the park rangers, we discovered that their local government unit (LGU) was planning to try to adapt the LAWIN app to include a wildlife identification component. Though this LGU is not our primary user, this information was incredibly valuable. It validates the prioritization of a wildlife identification feature, as well as lets us know of possible overlap in activities, pointing to the need for additional meetings and partnerships.

**Unfortunately, we could not shadow enforcement officers due to the dangerous nature of their jobs. Le sigh.**

We learned so much during our trek with the park rangers that we would not have known otherwise. While we often field test the tools we develop, doing field work in the design stage is as important. Below are some quick points to remember, courtesy of the [Foolproof Team](https://www.foolproof.co.uk/journal/experience-design-walk-a-mile-immersion/):

* Ensure that the journey is evaluated through multiple eyes. Different customers see the world through a different lens and may even follow a different path on a complex journey with multiple entry points.

* Ensure the consultants conducting the review are naïve to the product or service and have no prior brand exposure or allegiance that may bias their experience.

* Be objective and focus on the big picture. This is not the right exercise for picking up small, detail-oriented usability issues (we’d recommend an [expert review](https://www.foolproof.co.uk/journal/expert-reviews-aligning-the-organisational-promise/ "Foolproof blog post on expert reviews ") or [depth interviews](https://www.foolproof.co.uk/journal/when-to-apply-qualitative-and-quantitative-research/ "Foolproof blog 'when to apply qualitative and quantitive research "). This activity is more valuable to identify the higher level, systemic issues for a product or service.