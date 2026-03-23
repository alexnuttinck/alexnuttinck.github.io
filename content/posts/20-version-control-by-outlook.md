---
title: "Version Control by Outlook"
date: 2026-03-23T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 20 - Version Control by Outlook
theme: Toha
menu:
  sidebar:
    name: 20 - Version Control by Outlook
    identifier: 20-version-control-by-outlook.png
    parent: adventures-in-uptime
    weight: 21
---

{{< img src="/posts/adventures-in-uptime/20-version-control-by-outlook.png" title="Adventures in Uptime - Version Control by Outlook" >}}

We’ve all been there: joining a new project, grabbing a fresh cup of coffee, and asking the developer the most basic, innocent question imaginable:

> "Hey, where's the code repo for your project?"

You expect a Github link, maybe a Gitlab URL, or even an ancient SVN server if you're feeling unlucky. What you don't expect is the developer to smile with 100% unshakeable confidence and say:

> "Oh, I manage versions myself."

When I glanced at his screen, the horror truly set in. There was no Git branch, no commit history, just an Outlook inbox bursting with emails sent to himself. Attached to each one was a ZIP file with names that belong in a museum of modern IT nightmares:

```
project_v1.zip
project_v2_final.zip
project_v2_final_really_final.zip
project_v2_final_really_final_OK.zip
```

I thought it was a joke. I prayed it was a joke. But nope. He cheerfully explained that he just emails himself a copy every time he makes a change. In his mind, it was a perfectly functioning, 100% offline manual distributed version control system.

I had to walk away and take a very long sip of my coffee. He had successfully invented email-driven Git... one attachment at a time.

Because who needs GitHub when you have Outlook, right? 😅