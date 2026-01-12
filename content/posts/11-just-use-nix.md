---
title: "Just Use Nix"
date: 2026-01-12T10:00:00+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: Adventures in Uptime 11 - Just Use Nix
theme: Toha
menu:
  sidebar:
    name: 11 - Just Use Nix
    identifier: 11-just-use-nix
    parent: adventures-in-uptime
    weight: 12
---

{{< img src="/posts/adventures-in-uptime/11-just-use-nix.png" title="Adventures in Uptime - Just Use Nix" >}}


It all started with a classic developer frustration:

> "Why doesn’t this app build the same way on my machine?!"

A colleague leaned over, smiling with the confidence of someone who has already been converted:

> "You should just use Nix."

How complicated could it be?

Well... Nix isn’t *just* a package manager.
It’s a whole paradigm shift: reproducibility, determinism, portability, system stability: everything defined declaratively.
It promises environments that never drift and setups that behave exactly the same everywhere.
And then there’s **NixOS**. Not just a tool, but an entire operating system built on the same ideas.

But then comes the part everyone warns you about: **the Nix language**.

It’s powerful, elegant in theory... and completely foreign to anyone used to Bash, JSON, or traditional config systems.
A functional, declarative DSL with lazy evaluation and recursion everywhere.
A lot of newcomers describe their first encounter with it as:

> "This looks like sorcery."

And honestly? They’re not wrong.
The learning curve doesn’t slope upward. It goes straight up.

Yet every Nix enthusiast keeps repeating the same sentence with a serene smile:

> "Once you get it, Nix will change your life."

And they might be right.
Because once the concepts click, you gain something incredibly powerful:

* fully reproducible environments
* deterministic builds
* clean rollbacks
* no dependency drift
* no "works on my machine" ever again

It’s a brilliant system... hidden behind a wall you have to climb first.

So yes, Nix (and NixOS) are impressive.
But they’re also a journey: one that requires patience, curiosity, and possibly a strong coffee habit. 😅

And you... have you tried Nix or NixOS?
