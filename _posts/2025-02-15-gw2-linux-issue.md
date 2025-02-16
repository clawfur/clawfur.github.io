---
layout: post
title: Guild Wars 2 Linux Issue
subtitle: Freezes and frameskipping, oh my!
author: Feen
---

This week I kept running into a fairly inconsistent issue in gw2 via steam on linux; fixed it by using [ProtonGE](https://github.com/GloriousEggroll/proton-ge-custom), unsurprisingly.

What happens is generally one of the following:
- Game skips frames
- Game soft freezes
- Everything starts to play slowly

In seemingly nonspecific order, this happens anytime between the 30 min <--> 1 hr mark and can be a real game stopper especially if I'm doing world boss events or something equally high value (gives lots of loot)

Prior to this issue I used [protonplus](https://flathub.org/apps/com.vysp3r.ProtonPlus) to manage proton stuff in steam, it's useful for playing non linux native games.  It goes without saying that I used this for gw2.

Something in latest protonplus must have regressed as I got inconsistent but reliable freeze and skips all week when playing.  Which is not ideal when I'm a few hours in to it focused on going all over to fight world bosses or reach hard to reach places...

I made the switch to protonplus due to protonGE becoming unmaintained, and had been using it up until today when I got fed up with these issues.  Went back to protonGE to check it out and what do I know: it was back to being maintained, so predictably I immediately switched back to it.

It seems to be smooth sailing so far, no freezes or frame skips in the 1-2 hrs I've spent playing gw2.

I consider this problem solved (for now), and I hope this post helped anyone who was dealing with the same issue.

## Edit:

Make sure you have the steam overlay turned on as well, it seems to help with perf too.