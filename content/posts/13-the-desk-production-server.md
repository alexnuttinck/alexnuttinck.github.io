---
title: "The Desk Production Server"
date: 2026-01-26T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 13 - The Desk Production Server
theme: Toha
menu:
  sidebar:
    name: 13 - The Desk Production Server
    identifier: 13-the-desk-production-server
    parent: adventures-in-uptime
    weight: 13
---

{{< img src="/posts/adventures-in-uptime/13-the-desk-production-server.png" title="Adventures in Uptime - The Desk Production Server" >}}

We live in the era of the Cloud, Kubernetes clusters, and geo-redundant data centers. But sometimes, the most critical infrastructure is much closer to the ground. Literally.

This story comes from a moment of pure realization. I was at the office while a colleague was working remotely. He called me up, looking a bit sheepish, and asked for a favor: "Can you reboot the tower under my desk? There was a power cut and it didn't come back up."

I was confused. Why did he need his office desktop running if he was working from home?

I crawled under the desk, fought through the dust bunnies, and found the machine. Then I saw the sticky note: "Production Server - DO NOT UNPLUG."

I froze. "This... is production?" I asked.

"Yeah," he replied casually. "It feeds data to the main app. It's been running like that for years."

It turns out our "high-availability" architecture had a single point of failure: a standard desktop PC, resting on the floor, vulnerable to the cleaning crew's vacuum cleaner and accidental kicks.

It’s a reminder that Shadow IT is real, and sometimes "Enterprise-grade" just means "It hasn't crashed... yet." 😅
