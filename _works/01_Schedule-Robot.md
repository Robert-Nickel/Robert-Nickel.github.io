---
title: Schedule Secretary
description: Telegram Bot
image: "/assets/images/schedulerobot.jpeg"
layout: page
---

My younger brother tried to build a telegram bot, that gives him some information about his schedule, so he started, but stuck due to some infrastructure problems. I attempted to help him, and then basically took over the whole thing. I used claudia.js with its deployment and bot-builder features, and deployed it to AWS Lambda. Document based persistance happens using DynamoDB.

You can test the bot here (imagine you are still at school): [t.me/MyScheduleRobot](http://t.me/MyScheduleRobot)

Now some functional details: This bot is a schedule bot, it is not a calendar.
To make the difference, and therefore what it does and what it doesn't, more clear:

---

| Schedule                                                                                     | Calendar                                                                                          |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Days repeat every week                                                                       | Days are different every week                                                                     |
| Timeslots repeat every day (🔔 rings)                                                         | Timeslots are vary a lot                                                                          |
| [Compare this](https://i.pinimg.com/originals/e8/ec/d1/e8ecd11f3c278afd7b3543a2b81fd1ea.png) | [with this](https://cdn.vertex42.com/calendars/images/monthly-calendar-with-combined-weekend.png) |

---
<br><br>


A short high-level summary is:

1. Define all the subjects (plus room, teacher etc.) you have, the timeslots (that repeat every day) and your timezone
2. Configure your schedule, that is e.g. which subject you have first on monday, which second etc.
3. You get information for the whole week, just today, tomorrow or even now by chatting with the bot

Use /help to get the detailed and always up-to-date list of things the bot can do.

Lessons learned:
- Applying [KISS principle](https://en.wikipedia.org/wiki/KISS_principle) is good.
- ClaudiaJS, AWS Lambda and DynamoDB are really cool technologies.
- One doesn‘t get the telegram users timezone for free, you have to ask for location permission and resolve it with a third party service or ask directly for it (as I did here), which is weird, because a lot of people do not know their timezone.
- Don't expect anyone to use your bot, because of finding it coincidentally. Marketing a telegram bot is hard and reduced to the group of telegram users (surprise)!
- Take a lot of time to explain the purpose of the bot really well. It should do only [one thing really well](https://en.wikipedia.org/wiki/Unix_philosophy#Do_One_Thing_and_Do_It_Well) and creating another bot for other things is free.

You can find the [source code here](https://github.com/Robert-Nickel/schedule-bot)