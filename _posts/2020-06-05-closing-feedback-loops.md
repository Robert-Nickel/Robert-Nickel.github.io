---
layout: post
title: Hammurabis understanding of evolutionary loops
categories: [Thinking, Agile]
image: /assets/images/house.jpeg
---


A long time ago, [King Hammurabi of Babylonia](https://en.wikipedia.org/wiki/Hammurabi),
wrote a code of law, the so called [Code of Hammurabi](https://en.wikipedia.org/wiki/Code_of_Hammurabi),
which holds some surprisingly effective thoughts regarding the contract between a landlord and a house
builder.

„If a builder build a house for a man and complete it, (that man) shall give him two shekels of silver
per SAK [a length unit] of house as his wage.“ [1]

A bigger house costs more money. But isn‘t it interesting, how the house builder is not paid depending
on the time it took to build it? There is no hourly rate, which means, the landlord wont get any unhappy financial surprises, which is good. But wait a second! Doesn‘t that mean, that a house builder will do anything as fast and cheap as possible, wouldn't that be a catastrophy? He might put those people in danger, who want to live in this house later on. The key question is: How can the owner of the house assure, that it has a good quality, if he only pays depending on the size of the house?

Hammurabi thought about this, did some risk management, and solved this „quick and dirty“ approach by
the following law:

„If a builder build a house for a man and do not make its construction firm, and the house which he has built collapse and cause the death of the owner of the house, that builder shall be put to death. If it cause the death of a son of the owner of the house, they shall put to death a son of that builder.“ [2]

There is no need to explain, that the house builders will do their absolute best to prevent houses to
collapse and kill someone, because they have so much skin in the game for an unlimited amount of time, meaning they can be killed because a house collapsed, they built 20 years ago. How exactly assured Hammurabi the quality of houses? By closing a feedback loop for the craftmanship of house building. Those who are really good at building houses will be able to keep building houses, while those who fail doing that will be stopped putting peoples live in danger. It might sound like a cruel practice from our modern cultural perspective, but it led to ridiculously good houses, there is no doubt.

The house building quality solution is not a solution for house building anymore, maybe because of technological advancement and regulations, but I believe we can learn a lot from Hammurabis structural solution here. He shows us, that we need to close the feedback loop and reduce its complexity. This is, in my opinion, the single most important task of agile software processes. What I mean goes far beyond [„You build it, you run it.“](https://aws.amazon.com/de/blogs/enterprise-strategy/enterprise-devops-why-you-should-run-what-you-build/).

One example: A software architect, who does architectural work on a project and then leaves over to the next project, has zero skin in the game of the old project, and is therefore hardly able to improve. In a frictionless world, this architect would maybe get verbal feedback from people on the lower technical levels, that experience the actual haptical feedback that result from his decisions. But in the real world, complexity, reputation and hierarchy fog this verbal feedback, which complicates improvement for the architect further.
And this is just one example for the concept of closed feedback loops, and therefore having skin in the game.

Lets enhance our motto: „You build it, you run it .. and you bleed for it.“, where bleeding is metaphorical
for all the (negative) consequences that result from our decisions. It may be a phone call in the middle of the night, it may be doing overtime that originates in our own mistakes or might be getting fired. Especially the last point might sound extreme on the first glance, but think about this on a theoretical level first: Do you really want to build a team, in which people don't experience negative feedback on their own
actions? Do you prefer working with people who survived the sometimes brutal reality, or would you rather work
with people that have set up (and used!) safety nets a little too often? Please get this right: I am all for improvement that is based and being able to fail and learn. In order to be able to innovate, it is crucial to have playgrounds with limited consequences to failure. On the other hand I am worried, that an extensive lack of consequences will lead weak software craftsmen, who build houses that collapse.

And, of course, be aware! Don‘t let someone else put YOUR skin in HIS game. It has happend more than once, that a release plan, that was promised by a project manager led to overtime for engineers, or that product owners are blamed for quality issues, that were caused by „I will fix it later“ minded engineers. See my article [The Two Dimensions of an Increment](http://robertnickel.online#segregating-responsibility) to get more detail on this topic.

I found the inspiration for this thoughts in the book [Skin in the Game](https://amzn.to/2XzNbl7)
[3] by Nassim Nicholas Taleb.

[1] [Harper, Robert Francis, Ph.D. The Code of Hammurabi, King of Babylon about 2250 B. C. Autographed Text, Transliteration, Translation, Glossary, Index of Subjects, Lists of Proper Names, Signs, Numerals, Corrections, and Erasures, with Map, Frontispiece, and Photograph of Text.](https://ia800302.us.archive.org/6/items/cu31924074445523/cu31924074445523.pdf) p.81, §228

[2] [Harper](https://ia800302.us.archive.org/6/items/cu31924074445523/cu31924074445523.pdf) p.81, §229, §230

[3] [Taleb, Nassim Nicholas. Skin in the Game, Random House, 2018](https://amzn.to/2XzNbl7).