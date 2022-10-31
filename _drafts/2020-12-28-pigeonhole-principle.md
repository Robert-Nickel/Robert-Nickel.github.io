---
layout: post
title: Too many pigeons for the holes?
heading: pigeonhole principle
categories: Thinking
image: /assets/images/pigeon.jpeg
---

While learning for my discrete mathematics exam, I stumbled across the
[pigeonhole principle](https://www.youtube.com/watch?v=2-mxYrCNX60). A pigeonhole is where
pigeons like to sit. I started liking it, when I discovered, that it is so obvious in the metaphor but, at
least for me, took a while to become able to really apply it. The pigeon metaphor goes like this:

**If there are more pigeons than pigeonholes, at least one hole will host at least two pigeons.**

🐦 -- 📭  
🐦 -- 📭  
🐦 -´

Obvious, but

**How many people in Sydney have the same amount of hair on their head?**

Lets estimate the maximum amount of hair: 150K. In Sydney live around 5.3M people.
**Preliminary conclusion**: At least 2 people in Sydney have the exact same amount of hair.

The pigeonhole principle goes further: It also tells us, how many people (at least) in Sydney have the same
amount of hair. Just divide the pigeons by the pigeonholes and ceil the number.

5.3M / 150K ~= 35,3 ceiled to 36.

**Conclusion**: At least 36 people in Sydney have the exact same amount of hair.

I believe there are many real world situations, in which the pigeonhole principle makes a lot of sense, and I cannot
wait to stumble across some of them. To be honest: For this example, it would be more effective to count (or estimate)
the amount of bald people, assuming they are the biggest group with the same amount of hair.

**Homework**: At my wedding we had 125 guests. There were 6 different main courses and 3 different side dishes, and each
guest took one main course and one side dish on their plate. How many people at least had the exact same meal?