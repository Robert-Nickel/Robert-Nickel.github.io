---
layout: post
title: The 2 Dimensions of an Increment
categories: Agile
image: /assets/images/apple.jpeg
---

This post discusses the segregation of responsibility of an increment between technical people and business people. I experienced a very unclear understanding of this topic on both sides, which usually leads to wrong decisions and poor quality. I believe the proposed model will lead to a better sense of responsibility and therefore greater results.<br><br>

Lets start by some definitions: An increment can be everything between a whole product, that was
developed for years to a small feature that was developed in the last iteration/sprint.
It has many dimensions. For this model we need only two of them: the business perspective (also referred
to as functional), and the technical perspective.<br><br>

![](../images/increment_dimensions.png)

Business people are those that work on the business perspective of an increment, by defining and refining the problem, doing business research, talking to stakeholders etc; they answer the "what?". In scrum these are the product owners (POs). Technical people on the other hand are those who tackle the technical perspective on an increment. They develop a solution to a problem, by answering the "how?". And they work in a team, why not call them "tech team" for this article.<br><br>

If the tech team says, they want to do a technical task that does not directly provide business value,
but is necessary to keep the system alive, what should happen? Should the product owner agree to do it?<br><br>

The tech team as a whole is responsible for everything that happens on the technical dimension, including a sufficient level of quality ("We do not deliver Shyt!"), operations and security issues. Other examples are architectural, programming language and cloud platform related decisions, and there are many more. Since it is "their" solution to the problem, you call the tech team in the middle of the night, when the software isn't  running! Additionally, they are the only ones that know how to fix it.<br><br>

Therefore, the business people should not actively agree to the technical task, that was mentioned
earlier; they shouldn't bother at all! The questions that are asked on the business dimension are often similar to "What do we need to do?", "What is our (functional!) priority?", "When will we be done with this stage of the backlog?" and "Should I take this as one feature, or rather split it into two?". The business people should decide everything, that belongs to the business perspective, and shouldn't decide anything that does not belong to that dimension. If they would do the latter, they would take away the responsibility of people, who are better at doing that, which is a guarantuee for a loss of value from a wholesome standpoint. The business peoples decision making power starts and ends at business questions.<br><br>

This is a very clean and structural (and massively simplified!) solution to a typically "unclean"
problem. I have worked with engineers who believe, it isn't their responsibility to take actions on technical topics, because they do not feel responsibile. The technical debt piles up, which leads to quality issues and paralyzation in the development process. But they want to get told by the business people, or at least get allowance, to deliver good quality. That is not what being a craftsman and taking responsibility looks like.<br><br>

On the other side, I have seen customers and managers, who believe that the business people are responsible for everything, even technical things like architecture and quality. And of course, as common as the "unresponsible engineer" is the "I-will-take-it-all-business-person", who wants to decide on huge technical decisions or backlog items based on a two minute explanation. This persons often "allows" the tech team to decide on the smaller issues, because he "trusts" them with that. He mixes up the two given dimensions of an increment with importance or size.<br><br>

To make this more clear, think of the following example: As a member of the tech team, I have to keep my operating system up to date and secure all the time. On the long term, there is no way around it in order to be able to develop a feature, and I am responsible to do this. The very important question here is:

**Why am I responsible for doing this very small technical thing?**<br><br>

Is it because it is a technical thing to do, or is it, because it is a small thing? If the answer is the former: Great. Scale that up. You don't need to read this any further. If the answer is, because it is a quick and small thing, than you have that unclean structural problem that was mentioned above. There is no exact way in determining beforehand if a task is above or below a given threshold in size, complexity, importance, criticality etc. It is a subjective and discussable thing, that depends on experience, perspective and even the mood of people. At this point one could be tempted to think: "If it is close to that threshold, I will know if it is in my area of responsibility or not.". Yes, you might, but someone else might have a
different perception, and this relies by far to much on that subjective metric. A very clear segregation in responsibility, between the business perspective and the technical perspective
(and people who are well aware of it) is a good thing that leads to great results in software development.<br><br>

**One is responsible who has the power to make decisions, is affected by the consequences and has to deal with the reaction to those.**<br><br>

In order to embrace the segregation of responsibility, I propose that you start by cleaning up your backlog (or any other form of todo list you have). Group the items in "functional" and "technical". If some items are on the edge between those two, focus on the functional aspects first and kick out the technical questions or decisions, they will follow. The functional items are the reign of the business people. If you are one of them: This is the area you can make decisions on, and you have to take the full responsibility for your decision. This is your area of influence, doing a great job here will be easier without having all those technical aspects in mind.<br><br>

Now have a look at all the technical items. What you see is the reign of tech team.
If you are part of the tech team: This is what you decide and take the responsibility for. Ask yourself
for every legacy item you have: Which problem does my technical item solve, and is that really necessary and relevant? Clean up and discuss it with the other tech team members. You have to see the whole picture (the beyond-sprint-perspective), because you will be accountable for it.<br><br>

Just to get this right. I am not proposing to reduce the communication between business people and technical people. As a technical person, it often is a good idea to challenge business requirements. The technical people will sometimes have to justify, why they decide for a specific framework or why you
want to switch the programming language etc. But by all the technical decisions you do and execute, you should always (at least every iteration) also deliver things. Have in mind: the tools you use, are tools to solve a problem.
Tools are not useful without a problem to solve. Talk to each other :-)<br><br>

One concern I have often heard: How can you take away the responsibilty for big and time consuming technical  backlog items from the business people? They will need to meet agreements and make promises about release dates etc.! That is a valid question, and the answer is underwhelming: A technical decision is equally not in their responsibility, as protecting the engineers from getting hit by a bus. They simply cannot control it, and they shouldn't. At this point, business people have to let go the urge to control that and trust the tech team, which will deliver solutions, which will lead to more trust. It is an upward flywheel.<br><br>

I hope that this clarification about the dimensions of an increment, that should be taken into consideration  when taking responsibility for a software project in any role, helps to build highly valuable software with less stress for every involved person. Please keep in mind, that the more formal segregation I propse is no silver bullet. It is just a small piece in the big puzzle of software development, that can only work, if you have a non-broken tech team, that is abled and willing to take responsibility.<br><br>