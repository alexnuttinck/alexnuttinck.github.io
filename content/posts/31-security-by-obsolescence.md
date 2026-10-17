---
title: "Security by Obsolescence"
date: 2026-07-27T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
images: ["/posts/adventures-in-uptime/31-security-by-obsolescence.jpg"]
description: Adventures in Uptime 31 - Security by Obsolescence
theme: Toha
menu:
  sidebar:
    name: 31 - Security by Obsolescence
    identifier: 31-security-by-obsolescence
    parent: adventures-in-uptime
    weight: 32
---

{{< img src="/posts/adventures-in-uptime/31-security-by-obsolescence.jpg" title="Adventures in Uptime - Security by Obsolescence" >}}

Do you remember where you were in December 2021? If you work in IT, you probably do. The sky was falling. The internet was on fire. **Log4Shell** had just dropped, and suddenly, every Java application on the planet looked like a ticking time bomb.

We were no exception... I was already mentally preparing to spend my entire weekend patching JAR files.

We saw the scanners hitting our firewalls. LDAP injections, JNDI lookups—the whole nasty catalog of exploits trying to break down our doors. We rushed to check our legacy monolith, convinced it was the weak link that would doom us all.

And then, we found it.

`log4j-1.2.15.jar`

We weren't vulnerable. Not because we were secure. Not because we were patched. But because our stack was so incredibly ancient that it didn't even support the feature being exploited. The vulnerability required Log4j 2.x. We were rocking a version from 2007.

For once, our massive Technical Debt wasn't a burden; it was a hardened bunker. We were protected by the sheer weight of our own obsolescence.

Did we eventually upgrade? Of course. But for that one glorious weekend, while the rest of the world burned, we sat back, drank our coffee, and toasted to the unbreakable shield of Legacy Code.
