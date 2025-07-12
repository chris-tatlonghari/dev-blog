---
layout: post
title:  "Time Traveling to my First Internship: A Thought Experiment"
date:   2025-07-11 18:18:47 -0400
categories: jekyll update
---

I keep having a recurring daydream about simpler times in my career, specifically my first internship. What would it look like if I could travel back in time to that place? Bringing along all the technical skills and experience I have now. My first internship was in the **Fall of 2018**, not long after I wrote my first `Hello World` program. I barely knew how to code at this point. The bleeding edge of my abilities at that time was building a game of Blackjack.. on the command line.


On top of being merely amusing, it's actually a deceptively insightful thought experiment: What if you did put a Senior Software Engineer's brain inside of an intern?


> As an important disclaimer, I do not dare proclaim to be any sort of technical genius or seasoned veteran in my field. Contrarily, I know of high schoolers who are more technically competent than I should hope to be in the next **decade**. That's not an exaggeration or an attempt at self-deprecation. [Lexi Mattick](https://kognise.dev/) is actually a concrete example of this. She wrote [the article](https://cpu.land/) that taught me how CPUs work.


All of that being said, I do have years of experience under my belt now in web dev land. I've had enough growth in my career that I find it worthy to put thoughts to paper on the sheer gap between my self now and when I started. The field of software engineering is so vast and there is so much to be learned. The levels to it are insane. [DHH](https://en.wikipedia.org/wiki/David_Heinemeier_Hansson) put it best in that good developers are: 
> Constantly learning more and constantly becoming more competent such that by the end of it you're going to look like a f***ing God to your former self.

# How different would my first day go?

I'm fast forwarding through the part where I did my first interview. I vaguely remember the questions my boss posed to me, but they were very standard: *What's the most difficult project you worked on?* My **honest answer** to this question would have just shocked and confused him if I said I wrote a migration for hundreds of thousands of user accounts coordinating with tech compliance and marketing in just a few weeks --- and that the worst part was getting my assymetric decryption library to work with Alpine Linux because gRPC is dumb..

Day 1 of my internship was quite intimidating --- I assume that's a relatively common experience. I had but one year of CS to my name. It's not easy in that position to jump into a ten year old codebase in a language and framework that I've never seen. Nevertheless, they pretty much threw me right in and tasked me with rewriting of some their "feed processors".
> These feed processors were just mapping data from external providers to our own domain models. The data came from third party REST APIs. Very simple now, but this was peak wizardry for intern me.

I remember my first mentor, a mid-level engineer, was attempting to explain the general layout of the repository / flow of data to me and I completely blanked out. I didn't register a word, but I also recall not sleeping great the night before. Fully rested or not, returning to that conversation now it would have clicked immediately, and I could have followed up with a bunch of context gathering questions to onboard even quicker:
> So are you just running these processors all in a cron job? Where are you deploying this service? Why are we rewriting these again? Aren't you already serving up this data?

I remember returning to my desk and being completely lost. At some point during the day I was just looking at an existing feed processor trying to understand the syntax. (We were a C#/.NET shop, I think I only knew Python and [MATLAB](https://www.mathworks.com/products/matlab.html) at that point LOL) My boss came by and said "Are you just *reading* code?" In retrospect, I'm still not sure why he was that surprised.

I think a couple weeks and a fair share of hand-holding got me to piece together my first commit. Depending heavily on copying existing implementations of course. Obviously today, it's a pretty straightforward object mapping job. Today, it would have been a easy first day contribution. Maybe *first hour*? My throughput has been decent lately according to [DX](https://getdx.com/).

# How different would my contributions look?

It saddens me to admit that my overall contributions that Fall did not exceed much from writing those good ol' feed processors. I *maybe* also made some minor additions to our support website and dug my way up one abstraction level above those processors: writing the code that made the HTTP requests, delegated work to the processors, and did some logging.

Current me would probably have the capacity to handle the majority of the third party data provider migration (the reason for needing to rewrite those processors) in.. I don't know, a week? So, it begs the question: **What could I have done with my time there?**

I like to think I would have been able to complete a major project in the realm of improving developer experience at that company. I assume they would have realized that giving me regular developer tasks would have affected their velocity enough to merit a backfill once I went back to college for a semester. So, letting me run wild with a project that helped the company, but wasn't a strict requirement would be very logical.

> By the way, this company wasn't even using git at this point. Talk about being able to improve the dev experience... though I seriously doubt they would of let an intern come in and migrate their whole codebase and team to a new Version Control System.

A funny exercise might be spell out some projects I know I would be capable of completing in a semesters time **now** vs. how much I didn't know about what such a project entailed **then**:

| Project | Knowledge Gap |
| ----------- | ----------- |
| Rewriting our Support Website | I wasn't familiar with HTML, CSS, JS. Let alone what [ASP.NET MVC](https://dotnet.microsoft.com/en-us/apps/aspnet/mvc) was. Forget about identifying the gaps in what our developers (the support site stakeholders) had.
| Refactor Logging and Add Error Reporting | I didn't even know the difference between these things. [Serilog](https://github.com/serilog/serilog)? Slack Integration? Those words had yet to enter my vocabulary. |
| Migrate from EF DB-First to Code-First | [Entity Framework](https://learn.microsoft.com/en-us/ef/) who? ORM?! What's a migration? But really, I didn't even have my first database course yet. I didn't even know that design patterns were a thing, so how could I understand a [Unit of Work](https://en.wikipedia.org/wiki/Unit_of_work)? |

# How different would my interactions have been?

The entertaining part of this thought experiment to me is pondering what reactions I would have gotten from my coworkers just by having the knowledge I do now. This internship was pre-COVID, so we were fully in-person, making the reactions that much sweeter.

I remember hearing later on that one of my old coworkers was a big [Uncle Bob](https://en.wikipedia.org/wiki/Robert_C._Martin) follower. You know, a real strict [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882), die-hard [SOLID](https://en.wikipedia.org/wiki/SOLID) guy. I love to imagine his excitement when a young unassuming intern walks up to this cubicle to strike up a conversation about Dependency Injection or his take on Composition vs. Inheritance. Or even better, rage-baiting him when I suggest we could’ve just built the whole backend in Ruby on Rails. :)

I do vividly recall how bad I would tune out during some of our meetings (Sprint ceremonies, Company all-hands). It pretty crazy how a lack of domain knowledge and technical competency can make these meetings sounds like an actual foreign language. Naturally, I couldn't wait for these meetings to end. But nowadays I wish I had the oppurtunity to sit back in on them and context gather on all the initiatives that were happening at the company level. How were requirements trickling in? It would have been amusing to debate technical details with my boss at such a young age (especially relative to him with a couple decades of experience) in these meetings.

Every day interactions would have been immeasurably more rewarding now that I'm able to speak the language of software development. I honestly may been able to bring some good insight and perspective to our more senior/staff level engineers at the time --- having the advantage of being from **7 years in the future** in a continuously evolving field on my side.


# Final Thoughts

Looking back on this whole thought experiment, I’m struck by just how much the gap between “intern me” and “current me” reveals —-- not just about the technical knowledge I’ve gained, but about how much of software development is **invisible until it’s not**. It’s not just syntax and tooling; it’s ways of thinking, asking the right questions, noticing what matters, and knowing how to untangle complexity.

I can’t help but smile at the idea of walking into that office with seven years of hard-won lessons in my back pocket. Maybe I wouldn’t rewrite the world in a semester. But I’d ask better questions, learn faster, and connect more deeply with the people around me. And that is very likely what makes this recurring daydream so enticing.
