---
title: "Load Test Reality"
date: 2025-12-15T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 10 - Load Test Reality
theme: Toha
menu:
  sidebar:
    name: 10 - Load Test Reality
    identifier: 10-load-test-reality
    parent: adventures-in-uptime
    weight: 10
---

{{< img src="/posts/adventures-in-uptime/10-load-test-reality.png" title="Adventures in Uptime - Load Test Reality" >}}

It was a new mission: run performance tests on an application built by another consultant. The goal was simple: either confirm everything was fine, or prove there were real performance issues.

The original consultant was very confident. From his point of view, there was no problem at all.

> "We tested with JMeter. It scales perfectly. No problem."

Let’s just say... our results didn’t exactly match that statement.

We set up our own load tests and started small: just 10 concurrent users.

Very quickly, things went downhill. Response times exploded, errors piled up, and the application crashed as soon as we got close to those 10 users. We were surprised by how bad it actually was, we weren’t expecting the app to fall over that fast.

I don’t know exactly how the application had been architected, but one thing was clear: there was going to be a lot of work to make it truly scalable.

Sometimes, load tests don’t just reveal bottlenecks, they reveal reality. 😅
