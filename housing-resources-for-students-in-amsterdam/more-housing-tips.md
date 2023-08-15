---
description: >-
  This page includes some more detailed housing tips, highly recommended
  readthrough if you are struggling with housing
---

# 🏠 More housing tips

## Student Experience

When a new building opens for registration on studentexperience.com (amstelveen uilenstede is set to open in 2025), the main website may be down/basically unusable due to high demand. In this case, you can still get to the individual studio pages using links of the format `studentexperience.com/studios/{id}`, where `id` is just an integer likely starting from 0 with their first studio opened.

To get a rough estimate of which range the `id` you're looking for is in, follow these steps:

1. Add up the numbers of studios at all locations opened previously to get a lower bound.
2. Add the total number of studios from the new location to get an upper bound (keep in mind this might just be a rough estimation, but it seems to work at least sometimes). The numbers can be found on the website.

{% hint style="info" %}
**Also, a big disclaimer:** it's very likely against their Terms of Service (ToS), but I didn't get caught, and I doubt they bother to check. They just want the money. You could probably also do this for Minervahaven; however, there you'll get at most a handful of open studios at any time, and you need to figure out the right `id` before someone gets through naturally. This is very unlikely, probably even less so than just getting through naturally.
{% endhint %}

You could potentially make a simple Python script to find the one that is available, possibly faster than doing it naturally, but that is probably even more against their ToS and detectable.&#x20;

{% hint style="danger" %}
It might get you banned, even just for essentially DDoS'ing their servers while they are already overloaded.
{% endhint %}

Credit to fellow cs student for this writeup <3&#x20;
