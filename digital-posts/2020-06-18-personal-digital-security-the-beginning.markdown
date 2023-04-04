---
title: The Importance of Personal Digital Security
date: 2020-06-18 06:00:00 -04:00
tags:
- Privacy
- Cybersecurity
Author: Trevor Olexy
social-image: "/uploads/lock.png"
thumbnail: "/uploads/lock.png"
---

In the current climate of data collection and data harvesting by every website, company, government or official body that has access to your browser traffic, usage history, and location, your data is always at risk and vulnerable. To add to this, nothing is absolutely, unequivocally, 100 percent secure. Even air-gapped computers that have no connection to the internet, as demonstrated with the CIA-infected Iranian centrifuges with [Stuxnet](https://www.wired.com/2014/11/countdown-to-zero-day-stuxnet/) are vulnerable.

Did that sound alarmist? Well, it was meant to be. The good thing is there are simple measures that anyone from web and software developers to computer laypersons can take to protect themselves from the inevitable breach of their data. The more aware we are and the more precautions we take to avoid exposing our “IRL”-selves to the ever-present threats, the better our chances are of staying secure.

<!--more-->

There is a balance between security, privacy, and user-friendliness. Often one cannot achieve maximum privacy or security while maintaining an easy-to-use system. As with most things in life, there are tradeoffs. Under the ever-watchful eye of an oppressive regime, perhaps you value anonymity over ease-of-use. Perhaps you simply wish to keep your private data just that.

Your use-case, personal preference, risk-tolerance, government, and need for security can help you decide which levels of security best suits your needs. Google is your friend here as there are myriad articles addressing cybersecurity and hygiene. In fact, our own [Center for Digital Acceleration](https://dai-global-digital.com/tags/?tag=cybersecurity) has some already. In this post, I will touch on some simple, first-line defenses to keep your digital-self safe.

### When Did You Last Change Your Password?

At this point, my advice to you to change your password probably sounds like a broken record played out by your IT department. But honestly, on how many sites does your password work: two, three, 10? These are important questions. If you don’t believe me, check [https://haveibeenpwned.com/](https://haveibeenpwned.com/) by entering your email. My personal email returned several breaches of well-known services seen below:

![breaches.png](/uploads/breaches.png)

Mozilla also has a handy feature called [Mozilla Monitor](https://monitor.firefox.com/user/dashboard) that does something similar.

![mozilla.png](/uploads/mozilla.png)

Both are useful and I recommend using them. For added measure, you can use Google's built-in password checker. See the example report below. It reports no passwords have been compromised (great!) but that one of the passwords has been reused 113 times! One breach is all it takes to make all 113 accounts instantly vulnerable. Obviously 16 passwords are weak, meaning they can be guessed quickly using password cracking software or commonly used password databases.

![google_pwd_mgr-cf6263.png](/uploads/google_pwd_mgr-cf6263.png)

Easily guessable and leaked or cracked passwords are very likely to exist in databases of passwords and usernames that malicious actors share, trade, and sell across the internet and put you and your identity at risk. If you see an alert like the ones above, it is best to heed the warnings and update your password(s).

If you find your data has been breached and you haven’t updated your password in a while—maybe even if you have—it is never a bad idea to do so RIGHT NOW. I won’t delve too deep into password managers such as [LastPass](https://www.lastpass.com/solutions/business-password-manager) or [1password](https://1password.com/), but they are immensely important. While they might take some time to get used to, they save time, and immediately increase your personal digital security. The more tools you use the more you may find as one tool may not have access to or knowledge of all breaches or known common vulnerabilities and exposures (CVE: [https://nvd.nist.gov/](https://nvd.nist.gov/)). Those sites might be a bit detailed for most, but know that there are people out there keeping track of threats to keep digital-you safe.

### Keep Your Apps/OS Updated

Firstly, only ever install trusted software. How do you trust software? First don’t download installers or programs from sites that you don’t know, or if you don’t explicitly know WHY you are downloading something. For example it is often not advisable to visit or download files or otherwise interact with sites that don’t use HTTPS unless you explicitly know what you are doing on the site and trust the site host. Attackers can even fake the look of a site to appear like legitimate software offerings. This is a topic unto itself and I digress.

Look for the lock icon in addition to the https:// prefix in the URL path as seen below:

![https.png](/uploads/https.png)

Keep your operating system (Windows, MacOS, Linux) and all apps updated and as current as possible. Security vulnerabilities (see CVE above) emerge regularly and these vulnerabilities or holes are often patched very quickly. The more up-to-date your system is, the fewer attack surfaces exist for potential malicious actors to infiltrate your computer or application.

This is intended to be almost a quick start guide to personal digital security, but this is merely the beginning of your journey to digital security. I truly hope that none of this is new, but to some it will be and to those it will be a valuable step in the right direction.

We can (and will) delve much deeper into things such as home router security, web application security, and various other methods by which to secure yourself. Some methods are for developers only, some for web-surfers. In future posts I will dive deeper into more specific cases to shed some light on common security threats and ways in which developers and users can fend off would-be attackers with simple settings and behavior changes.