---
title: Caching 101&#58; Caching on the JVM (and beyond)
co-speaker: Alex Snaps
recording: https://www.youtube.com/watch?v=HtrU07c17JQ
slides: https://www.slideshare.net/LouisJacomet/caching-101-caching-on-the-jvm-and-beyond
event-name: Devoxx Belgium
event-url: https://devoxx.be/
---

After numerous presentation on the JSR107, this in-depth 3 hour university session will twist the problem upside down. Instead of leading you through every aspect of the new Caching API for Java, we'll start from a real Java application, looking at its architecture, measure contention points and slowly start adding different caching patterns to it. We'll look beyond the specification as well, not in terms of proprietary APIs, but in terms of different cache topologies (onheap, offheap, distributed, ...) and considerations around them when introducing caching to both an existing or architecting a new one. Finally, we shall look at how different application containers and framework may affect decisions we've made during the session.