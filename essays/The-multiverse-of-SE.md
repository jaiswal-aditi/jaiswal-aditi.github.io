---
layout: essay
type: essay
title: The multiverse of software engineering at Google
# All dates must be YYYY-MM-DD format!
date: 2022-02-08
labels:
  - Software Engineering
  - Coding practice
  - Review
---

<img class="ui medium right floated rounded image" src="../images/software-engineering.jpg">

Welcome to GCU (Google Coding Universe) and this essay will walk you through my review on an ACM tech talk `"Software Enineering at Google"`. In this talk, featuring two senior software engineers at Google, the main focus of discussion was what are some best coding practice required to maintain a healthy codebase at Google. Now I always used to correlate software engineering directly with programming and I used to think if you can code well, you can be a good developer. But this was an eye opener for me in a way that it was through this talk I learned that software engineering is so much more than that. It is a team effort, years of experience, observations and ability to evolve with time along with good programming skills. One should also know that there's no 1 solution to all, no silver bullet or no 1 language or a tool which could make development easier and better. Software development is a series of small steps which could be achieved not just by focusing on productiity but also on error budget, risk tolerance and new features. So this is the secret of Google's success.

### Tick tick, boom

The first key point was **time**. You may ask how does time affect a project? The speaker gave a very concise explanation: for a novice programmer, working on a specifiic project, the project time is measured in hours (or maybe days). Then comes the startups or app development codes which is based on specific needs and may work upto 2-3 years. Finally on a bigger scale we have tech industry projects (Linux, Google), open source development which have a long lifespan of decades probably. You don't just throw away your code but upgrade it, make it sustainable and compatible. `Software engineering is the art of making your program resilient to change over time.` And how does Google do that? I'll give you a hint: sustainability. We know that change is the only constant in life. So with time we are geeting better tools, upgraded software, hardware and new technology and if we keep on discarding each of our previous codebase it'll cost us a fortune. Well, that's where Google understood its homework correctly. It includes large scale change refactoring. Let's put it this or as they call it "Hyrum's law". No, its not a famous, standardized concept but rather an observation:

> *"with sufficient users in API, it doesn’t matter what you promise in contract: all observable behaviors of a system depend on someone."*

Let's break it down. We don't always know what users want and we can't focus on their specific needs because that will change with time, and dealing with all of them separately is too complicated. So we need to incorporate randomness in the codebase to make it resilient to the change, and be easily able to upgrade and maintain it. Sustainability means you are able to change all of the things that you ought to change, safely. This is because, in software engineering, the goal is not to just solve problems but keep the solutions working for as long as possible.

### Scale the sale!

As mentioned before, hardware (CPU, RAM), softwares and human resources, everything that your code relies on, is changing everyday. So the question which a developer should ask is *"are those  scalable in terms of cost and resource consumption?* With the ever increasing user requests how can one handle the codebase without affecting the throughput?

