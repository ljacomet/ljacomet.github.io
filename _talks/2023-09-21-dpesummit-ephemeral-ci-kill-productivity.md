---
title: "Lightning Talks Build Tool: Don’t Let Ephemeral CI Kill Your Developer Productivity"
slides: assets/files/dpesummit_ephemeral_ci_kill_productivity.pdf
event-name: DPE Summit
event-url: https://dpesummit.com/agenda-2023/
---

The Gradle Build Tool comes with a number of performance optimizations that help reduce the work to be done for each build.
However some of these optimizations are achieved by keeping local state.
While this is beneficial for local development, it can cause surprises in modern continuous integration setups where the trend is to have isolated and disposable environments.
Suddenly, your Gradle build is slow!

The goal of this session is to provide strategies for getting the best of both worlds:
Allow Gradle to leverage its performance optimizations while running in ephemeral environments.

The session will cover different performance aspects of a Gradle build and show you how to leverage them in such an environment.
