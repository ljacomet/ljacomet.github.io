---
title: Data consistency&#58; Analyse, understand and decide
recording: https://www.youtube.com/watch?v=t7nMNy4YoVY
slides: https://www.slideshare.net/LouisJacomet/data-consistency-analyse-understand-and-decide
event-name: Devoxx Poland
event-url: http://devoxx.pl/
---

Most applications handle some form of data. And quickly you end up duplicating this data … whether going from a JPA entity to a DTO, offering a caching layer on top of your services or even because the database is replicated and clustered.

As soon as there is duplication, there is a risk of inconsistency. How long is my DTO meaningful? How do I invalidate my cache? What happens if asynchronous data replication fails?

Answering these questions quickly becomes extremely complicated and most often requires a final decision be made at the application level.

By illustrating these concepts using the resilience strategy developed for Ehcache 3, we will see that even for libraries targeted at handling data consistency in the face of failure, only the application may know the answer.

Handling these issues from day one, during design and architecture, is a major concern. And after all, isn’t the easy path quite boring?