---
title: "The Reproducibility Crisis"
date: 2025-10-12T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 1 - The Reproducibility Crisis
theme: Toha
menu:
  sidebar:
    name: 1 - The Reproducibility Crisis
    identifier: 1-the-reproducibility-crisis
    parent: adventures-in-uptime
    weight: 1
---

This one goes back to one of my very first missions.
I arrived at the client’s office, full of energy, ready to dive into their development environment.

So I asked the classic first question:

“Can I get access to the dev environment?”

The answer? A USB key.
Inside it, a virtual machine image, several gigabytes of it, along with a Word document as the only piece of documentation for the setup. No Git repository, no configuration management, ...

That same USB key was being passed from developer to developer like some kind of sacred artifact.
When one person made changes to the environment, they’d just copy it back to the USB and share it again.

When I asked if they used Docker, Ansible, or anything to make the setup reproducible, the client looked at me and said:

“Why bother? We just share the VM around. It’s reproducible enough, right?”

At that moment, I knew there was going to be a lot of work ahead. 😅

{{< img src="/posts/adventures-in-uptime/1-the-reproducibility-crisis.png" title="Adventures in Uptime - The Reproducibility Crisis" >}}

Moral of the story: If your dev environment fits on a USB stick, it’s not reproducible: it’s portable chaos...

---

And you, what's the most "creative" development setup you've encountered in your career?
