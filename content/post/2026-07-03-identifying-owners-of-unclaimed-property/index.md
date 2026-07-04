---
title: Identifying the Owners of Unclaimed Property
author: R Build
date: '2026-06-23'
categories:
  - business
slug: identifying-owners-of-unclaimed-property
thumbnail: '/2026/06/23/identifying-owners-of-unclaimed-property/images/missing-money.png'
---

**TL;DR:** I used Claude to build a pipeline that identifies likely owners of unclaimed property (lost or dormant assets held by the state) and just messaged the likely owners of ~$10M currently held by the state of CA. Initial notes on the project/approach are at [brshallo/escheat-finder](https://github.com/brshallo/escheat-finder).

There's that classic economist joke:

> Two economists walk down a road and see a twenty dollar bill lying on the sidewalk. 
>
> One asks, "Is that a twenty dollar bill?"
>
> The other answers, "It can't be, because someone would have picked it up already."
> 
> And they keep walking.

With the emergence of AI, it feels like we're in that in-between period where there's lots of money that has yet to be picked up. Navigating the tangle of transactions of unclaimed property seems like one such problem that should just be mostly "solved" by agents scouring public records. Until the data aggregators or the state finish the job, I thought I'd explore throwing some intelligence at it.

The process started as one of a few candidates for: "What's something genuinely useful I could set up to throw excess personal Claude tokens at before my limit resets each week?"

After some initial tests and positive responses, I felt good enough about my system to reach out to this first batch of people. Through a bunch of iterations, I now have this initial list of people I've reviewed (doctors, professors, non-profit coordinators, ...) and feel a real weight thinking about what their reaction might be when/if they see my message. Will they be...

- Excited about an asset they didn't know they had?
- Disappointed about securities they thought were appreciating but have instead been liquidated and sitting in a 0% government account?
- Annoyed at some random person they think is trying to scam them? (Or that contacted them by mistake.)

I'm also still calibrating where to set the threshold for unsolicited outreach. How confident should I be before contacting someone? Is it more acceptable to reach out on a weaker match if the potential claim is much larger? How many times should I try contacting them. What's the most effective medium (text, social media, email, mail). I'm interested to see how that changes as I start getting feedback from the people I contact in this first batch of emails.

We'll see how this initial run goes.  

Hoping people read their inboxes 🤞🤞🤞!   

[![Missing Money website](images/missing-money.png)](https://missingmoney.com/)

As a PSA, everyone should check their name (and their friends' and families' names) at https://missingmoney.com/. It's free to search and file claims (the site is legitimate and run by the National Association of State Treasurers and State Unclaimed Property Administrators).
