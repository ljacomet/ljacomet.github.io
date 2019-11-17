---
title: Ehcache 3 JSR-107 on steroids
slides: https://www.slideshare.net/LouisJacomet/ehcache-3-brujug
event-name: BruJUG
event-url: https://www.meetup.com/BruJUG/
---

JSR107, aka the Temporary Caching API for the Java Platform, was finalised almost 3 years ago. We've heard all about its ease of use and capabilities. But there is much left unaddressed.

So what do you do now? Go for proprietary APIs?!

Ehcache, the de facto caching API for 10 years now, has gone through a major API revamp for version 3. One major theme, beyond its usual ease of use, was JSR-107. Natively integrating it, but also looking beyond. With close to no API tie-ins, Ehcache3 lets you extend the JSR-107 API transparently to go beyond the specification:

* topology-wise: whether you want to go offheap and scale up, or scale out by clustering your caches;
* functionality-wise: using transactional caches, automatic resource control or even using a write-behind cache to scale out writes…

We will illustrate how easy it is to leverage these features while keeping the easy integration of JSR-107 offered in well known frameworks such as Spring.

Best of all, these features are not only minimally intrusive, they are also all free to use and available as part of the open-source Ehcache 3.0.0 that was released mid April 2016.