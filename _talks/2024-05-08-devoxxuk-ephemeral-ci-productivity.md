---
title: Don’t let ephemeral CI kill your developer productivity!
slides: assets/files/devoxxuk_ephemeral_ci_kill_productivity.pdf
recording: https://www.youtube.com/watch?v=_6Z4Ubg3aCs
event-name: Devoxx UK
event-url: https://www.devoxx.co.uk/talk/?id=21407
---

The Gradle Build Tool comes with a number of performance optimisations that help reduce the work to be done for each build.
However some of these optimisations are achieved by keeping local state.
While this is beneficial for local development, it can cause surprises in modern continuous integration setups where the trend is to have isolated and disposable environments.
Suddenly, your Gradle build is slow!

The goal of this session is to provide strategies for getting the best of both worlds:
Allow Gradle to leverage its performance optimisations while running in ephemeral environments.

The session will cover different performance aspects for a Gradle build and how you can support them in such an environment.