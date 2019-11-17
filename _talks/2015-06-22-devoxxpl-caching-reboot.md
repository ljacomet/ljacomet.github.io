---
title: Caching reboot&#58; javax.cache & Ehcache 3
recording: https://www.youtube.com/watch?v=6kW7tcqvsVs
slides: https://www.slideshare.net/LouisJacomet/caching-reboot-javaxcache-ehcache-3-61757652
event-name: Devoxx Poland
event-url: http://devoxx.pl/
---

After more than 10 years, Java finally has a standard caching API as delivered by JSR-107. In parallel, Ehcache - the well known and over 10 years old caching library - is getting a reboot.

Version 3 is announced: JSR-107 compliant, fully generified API, the good pieces of the 2.x line and a few innovations. This could be a lot to digest at once, so the presentation will be run like a menu:

* As a starter, you will be introduced to the JSR-107 API and features.
* The main course will be to go over real-world caching use cases. This will allow us to understand what javax.cache offers but also lacks in places. It will be served with some additional features of Ehcache 3. This will show you how to get to them while your application keeps addressing the specification APIs.
* For desert, we will look at specific feature(s) that make Ehcache 3 unique compared to other cache offerings, including former versions.