---
title: "Alias of Shame"
date: 2026-01-19T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 12 - Alias of Shame
theme: Toha
menu:
  sidebar:
    name: 12 - Alias of Shame
    identifier: 12-alias-of-shame
    parent: adventures-in-uptime
    weight: 13
---

{{< img src="/posts/adventures-in-uptime/12-alias-of-shame.png" title="Adventures in Uptime - Alias of Shame" >}}

Mistakes happen.
Even in carefully planned communication campaigns.

One day, a brand-new email campaign was sent out to a large audience. Everything looked fine... until someone noticed it.

The email address in the communication was wrong.

Panic followed quickly.

Instead of preparing a simple correction and sending a follow-up email with the proper address, the communication team came to us with a different request:

> "Can you create an alias so messages sent to the wrong address still arrive?"

From a sysadmin point of view, the answer was obvious: **no**.

Creating mail aliases to compensate for human mistakes is a slippery slope.
One exception quickly becomes two, then five, then ten.
Before you know it, you’re running an undocumented maze of redirects that no one remembers, no one cleans up, and everyone depends on "because it’s always been like that".

We suggested the clean solution:
Send a correction. Own the mistake. Move on.

A few hours later, the discussion was no longer technical.

A director showed up, clearly annoyed, and made it very simple:

> "Do the redirect. Now."

At that point, the decision was no longer about best practices, maintainability, or long-term sanity.
It was about hierarchy.

So we did it.
Reluctantly.

The alias was created, documented (at least by us), and silently labeled in our minds as what it really was:

**The alias of shame.**

This kind of situation doesn’t only happen with email.
It also shows up with web aliases, DNS hacks, reverse proxies, and "temporary" redirects that somehow survive for years.

Sometimes, systems aren’t shaped by good design: they’re shaped by urgency, authority, and politics.

And sysadmins?
We’re often the ones left making sure those decisions don’t explode... at least not today. 😅
