---
layout: post
title: Only split a story, when it is too big?
categories: Agile
image: /assets/images/split.jpeg
---

Story Estimations in the world of agile software development is, in my opinion, a totally underrated topic*.     It has major influence on several important topics, such as the agile mindset of the team, the trust between the PO and the development team, and how to deal with pressure. I observed several biases related to this topic, and today I am going to write about one of them, the "Only split a story, when it is too big" bias.<br><br>


Assume a team, that is estimating stories** with Fibonacci numbers (0,1,2,3,5,8,...) having an average velocity of 10 story points (SP) per sprint. The rule behind the bias says: If a story is bigger than 8 SP, it is too big, and it should be split into two stories. Otherwise it is "small enough"and can stay as it is.<br><br>

There are several advantages of this, especially from the PO's POV:<br><br>

- You have less work, less text to write and less items in the backlog.<br><br>
- You can cut and merge the stories based on your feeling. If you have to split it, the estimation of the team will tell you. If no one tells you, it is okay.<br><br>
- You do not need to bother about details (from a business POV!) too much. Since there is barely any space
for details, they can stay hidden and will be handled by the team as soon as the story is being implemented.<br><br>

Here are my objections:<br><br>

First, about the flexibility:<br><br>

The number of stories in the backlog might be small, but the PO cannot change the amount of work by putting things together in one story instead of two. What he instead does, is burying the flexibility to postpone the less important part of the story and shift the more important part closer to the sprint backlog. Moreover, just think of the following situation: A big story was planned and not split, and while implementation, the team found out it is not only big, it is huge, so they cannot do it in this one sprint. In most cases, the team will continue with this story in the next sprint, and questions like "How many percent of the story are done?" or even worse "How much story points of this story have you already achieved?" might pop up. Having stories for more than one sprint leads to frustration for the development team and immobility for the PO, who has no good options, then putting the story into the next sprint again. You might have heard of the "divide and conquer" strategy in other contexts, but here it fits perfectly as well: By dividing stories as often as possible, you will be able to conquer the more important parts of the product first and leave out all the rest for later. Just as a side note: I have heard sentences like "…but if the PO doesn't want this flexibility, it is his problem.". Dear engineer with this opinion: If you try to make the life of the PO easier, he will try to make yours easier; help your PO!<br><br>

Second, about reducing the amount of work:<br><br>

A PO, who is lazy in writing stories, and has rather one long story instead of to short stories, doesn't invest  enough attention into the most important parts of his job: Leading the work of the development team into the direction, that increases the value of his product. At the end of the day it is cheaper and less time-consuming, if the PO figures out the details from a business POV upfront and puts them into stories.<br><br>

Dear PO, who thinks that he can "save work" by "just leaving as it is" and "seeing what the team thinks": You are generating unnecessary work for the development team, and for yourself; do your homework instead!<br><br>

Third, about the user feedback:<br><br>

It is a great strategy for products, that are already live and released, to monitor, which features are actually useful for the users and which are not. With smaller stories, the feedback loop gets smaller as well. The user and his wishes and needs related to the product can be understood, and the solutions, the user really desires, can be applied. The PO will be able to see, if his idea is a good idea, before investing a lot of time and money into developing it. And even if your product is not live yet: If the stories are small, the PO will get the feedback from the team, of how they understood the story, early. Therefore, he can react to misunderstandings und surprises early and reduce waste.<br><br>

Fourth, about the motivation:<br><br>

This fourth point might not seem to be the most important one, but I still decided, to note this down: What do you think feels better for all involved, saying "There are 3 stories done and one is started", or "The one (huge) story this sprint is almost done". Obviously the first option sounds better and makes people feel better, since achieving something is always better than achieving nothing. Yes, this doesn't affect the reality directly, but it is a good motivation to see constantly, that you get stuff done.<br><br>

Conclusion:<br><br>

Writing as small stories as possible (ASSAP) helps the PO to gain flexibility, by being abled to leave unimportant stuff out and putting more important stuff faster in. It also increases the speed of the development, by giving more space for the details and time to clarify them upfront. Moreover, it helps the PO and the development team with going into the right direction, by reducing the size of the feedback loops between the development team, the PO, and, for live-systems, the user. Finally, it motivates the team, by making transparent, that they actually get stuff done.<br><br>

*There are some interesting people who write about this topic, such as Woody Zuill and Mike Cohn. In general, I am not a fan of having estimations at all (Compare with Woody&rsquo;s #NoEstimates), but since it is still a very common way of planning (i.e. guessing) the future, we have to deal with it somehow.<br><br>

**All stories in this consideration underlay the precondition, that they contain only a business POV and no technical perspective on things. Typically, this looks similar to "As a user, I want to rate an online shop, in order to tell others about my experiences with it and give hints, recommendations or warnings."<br><br>