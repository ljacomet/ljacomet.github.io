---
layout: post
title: Coderetreat Belgium
tags:
- coderetreat
- dvcs
- git
- practices
- software
- craftsmanship
- tools
---

Saturday November 6th, I attended the (first?) Belgian [Coderetreat](https://www.coderetreat.org/) facilitated by [Corey Haines](https://twitter.com/coreyhaines) and organized by [AGILEMinds](https://twitter.com/agileminds).

Since reading about coding dojos, coding katas and other code practices advocated by the [software craftsmanship](https://en.wikipedia.org/wiki/Software_craftsmanship) movement, I have been intrigued in trying these out.
While I attended [coding](https://web.archive.org/web/20130226055914/http://www.bejug.org/confluenceBeJUG/display/BeJUG/JSR-311+REST+Dojo)
[dojos](https://web.archive.org/web/20130225122612/http://www.bejug.org/confluenceBeJUG/display/BeJUG/Scala+Dojo) organized by BeJUG,
we never had an experienced facilitator around to guide us.
We had lots fo fun, we ended up producing code and even achieving results, but not necessarily improving coding practices while doing so.
And from what I got out of the description, some of these exercises target more the craft than the result.

So, when I heard about Coderetreat, facilitated by Corey, I decided I could not miss it.
And it was a tough choice as the same week-end the [CITCon](https://www.citconf.com/) conference was taking place.

The problem worked on is [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life).
Not too big to require long description, but complex enough to require more work than the 45min session allows.
And to go with that, some rules:

* Sessions are paired
* After 45 min sessions, the code is deleted, no VCS, no zip, no nothing. Wipe it clean
* Focus is on code quality not quantity

First of all, the deletion rule is tough.
This definitely makes sure you will never complete the exercise.
Even so I found myself trying to rush to the end of it for the first two sessions without success and probably breaking most TDD rules doing so.
And producing crappy code!

After a while you really get that the whole point is to improve at code writing.
From there on, I managed to put more focus on quality with each pair change.

It is a tough rule, but also very liberating.
It allows you to forget about implementation details while retaining the abstractions.
And it is here that you can really bring over results from a previous iteration to the next one.
When my pair programmer and I achieved a nice abstraction, I tried to carry it over in the next run to test it with the rest of the problem to see how well it complied to the [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod).
Related to that, Corey asked us to be even more focused on quality and work in basic steps:

* make the test pass,
* verify names,
* eliminate duplication

Basic and very hard to follow.
But when the pair gels, follows the rules, the feeling of ending up with nice code is rewarding.
As with a lot of practices you see in the Agile world, the way all these elements fit together is impressive.

All in all, it was a very interesting day, and an experience I will certainly reproduce.
Plus meeting other passionated developer is always nice.

As a conclusion, I cannot say if this is going to make me a better coder, but from what I see on the web, smarter people than me believe it can help, so I am willing to try out, and so should you!

AgileMinds announced the [next coderetreat event](https://twitter.com/AGILEMinds/status/1319619562307584) on January 16th, 2011.