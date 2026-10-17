---
title: "The One Person Who Knows"
date: 2026-07-07T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
images: ["/posts/adventures-in-uptime/30-the-one-person-who-knows.jpg"]
description: Adventures in Uptime 30 - The One Person Who Knows
theme: Toha
menu:
  sidebar:
    name: 30 - The One Person Who Knows
    identifier: 30-the-one-person-who-knows
    parent: adventures-in-uptime
    weight: 31
---

{{< img src="/posts/adventures-in-uptime/30-the-one-person-who-knows.jpg" title="Adventures in Uptime - The One Person Who Knows" >}}

Every company has one. That one sysadmin sitting behind a fortress of monitors, cables, and coffee cups. They are the legend of the open space. When a complex legacy system acts up, colleagues point at them in reverence and whisper:

> "That’s the one who knows everything. Don’t touch anything without asking them."

But this legendary status comes with a dark side: Solo Mode. Whenever an over-eager junior dev or a desperate teammate tries to peek at the terminal and politely asks for a runbook or documentation, the answer is always the same annoyed grumble:

> "It’s faster if I do it myself."

No docs. No sharing. No witnesses.

Everything seems to run perfectly... until the inevitable happens. A simple sticky note reading "On vacation ☀️" appears on their empty desk. Almost immediately, critical alarms start screaming on the monitoring screens behind panicking colleagues. The entire team stares at a flashing dashboard, realizing they have a critical single point of failure.

When the "KNOWLEDGE DOWN" warning flashes across the room, and the team stands helplessly in front of the chaos, the tragic realization hits:

> "We should’ve backed up the human."

It’s a classic infrastructure trap. We spend thousands on high availability, redundant databases, and failover clusters, but we completely forget about the human element. We build highly available systems managed by low availability humans.

Availability: 99%. Bus factor: 1.

After all, it’s not undocumented... it’s undocumented by design.