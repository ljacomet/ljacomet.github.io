---
title: The road to Gradle 9
slides: https://jacomet.dev/jfokus-gradle9/#/
recording: https://youtu.be/uIq5X7Ty0_0
repository: https://github.com/ljacomet/jfokus-gradle9
event-name: Jfokus 2024
event-url: https://www.jfokus.se
---

While the Gradle Build Tool has been around for a while, it continuously evolves.
The next major version, 9, has a couple key features in scope that will have an impact on the Gradle users and ecosystem.

For users, the focus is on two tracks: scalability and comprehensibility.
The Gradle team aims at delivering features that make builds as fast as they can be, even for massive projects.
On the other hand, comprehensibility is all about making Gradle easier to adopt and use for teams of all size and skill.
Offering all of the above will require the plugin ecosystem to match the updated Gradle APIs and patterns, including stronger constraints that are required in order to continue offering the strongest reliability guarantees.

This session will cover topics like:

* Continued investment in configuration caching,
* Upcoming isolated projects feature,
* Higher level modeling of software projects,
* Separation of concerns for build users and build authors

All of these topics will be illustrated by released features available in the Gradle 8.x line but also by looking at what is coming in 9.0 and beyond.
Both build users and plugin authors will learn what to do now and tomorrow for leveraging the most of Gradle 9.
