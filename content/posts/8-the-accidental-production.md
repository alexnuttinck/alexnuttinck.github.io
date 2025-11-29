---
title: "The Accidental Production"
date: 2025-12-01T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 8 - The Accidental Production
theme: Toha
hidden: true
menu:
  sidebar:
    name: 8 - The Accidental Production
    identifier: 8-the-accidental-production
    parent: adventures-in-uptime
    weight: 8
---

{{< img src="/posts/8-the-accidental-production.png" title="Adventures in Uptime - The Accidental Production" >}}

It started as a simple mission: build a Kubernetes POC to explore the benefits and rethink the current architecture.
The demo worked, the checklist was green, everyone was happy.

We made it clear to the client:

> "This is only a demo environment, nothing critical."

They nodded, satisfied.
We moved on.

---

A few weeks later, the phone rang.
It was the same client. Except this time, they didn’t sound calm at all. 😨

> "Everything’s gone! Our production is down!"

An incident at the OVH datacenter had taken out their entire infrastructure. Servers, backups, everything hosted in the same place.
A total loss.

For a moment, silence.
Then came the question we didn’t expect:

> "Can we use the Kubernetes POC as production?"

The POC was running, tests were green, and the app didn’t need long-term persistence hopefully. Their business processed streaming data for the day or week, not years.
So we took a breath and said: "Let’s go."

---

The next few hours were chaos.
Scaling up replicas, securing ingress, adding monitoring, cleaning up demo secrets, turning our quick prototype into something that could actually handle real traffic.

And somehow, against all odds, it held.
The client’s app came back online.

A few hours later, the same person called again.
This time, they were smiling.

> "It works perfectly!"

We smiled too.
Then quietly thought:

> "It was never supposed to..." 😅