---
title: "The Blue Screen of Container Death"
date: 2025-10-29T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 3 - The Blue Screen of Container Death
theme: Toha
menu:
  sidebar:
    name: 3 - The Blue Screen of Container Death
    identifier: 3-the-blue-screen-of-container-death
    parent: adventures-in-uptime
    weight: 3
---

{{< img src="/posts/adventures-in-uptime/3-the-blue-screen-of-container-death.png" title="Adventures in Uptime - The Blue Screen of Container Death" >}}

It started as a new and exciting mission.
The client needed help setting up proper CI/CD pipelines and introducing DevOps best practices. Everything sounded great.

Then came the small detail that hadn’t been mentioned during the initial discussions.

“Oh, by the way, our application runs on Windows… and we use Windows containers.”

I froze for a second.
Windows… containers? I didn’t even know those existed before that project.

I’d always worked with Linux. For me, containers meant Docker, Kubernetes, and bash scripts. Not PowerShell and .NET frameworks.
But I tried to stay optimistic. After all, how different could it be?

A few days later, I had my answer.

Running Windows inside containers felt a bit like trying to fit a square peg in a round hole. Technically possible, but painful to watch.
The tooling was clunky, the builds slow, and debugging often ended with something that looked suspiciously like a "Blue Screen of Container Death".
And the fact that what image you can run depends on the host OS defeats half the purpose of containers to begin with.

By the end of the project, I had learned a lot... mostly patience.
There’s a reason the container ecosystem was built around Linux: it just makes sense.
To be fair, this was a few years ago, maybe things have improved since then.

---

Have you ever had to use Windows containers? What was your experience? Has the ecosystem evolved?