---
title: Protecting your organization against attacks via the build system
slides: assets/files/protecting-attacks-build-uk.pdf
event-name: Devoxx UK 2022
event-url: https://www.devoxx.co.uk/
---

Everyday, as developers, we build dozens of times.
Sometimes without noticing (in the IDE), sometimes explicitly from the CLI (gradle test, mvn clean test), sometimes from CI.
However, barely anyone recognizes the security risks of building software.

This talk will highlight potential attack vectors and explain how we can mitigate them.
The build tool is by definition insecure because it's a free execution environment.
However, there are ways we can reduce the risks, or even significantly reduce them.
Some topics we will cover:

* making sure the dependencies you use are the ones you expect
* using checksums and signatures
* rejecting vulnerable dependencies
* build reproducibility
* disposable build environments and mitigating performance issues related to them
* testing external contributions

We will mostly illustrate those with Gradle but most of the recommendations are also valid with Apache Maven. 