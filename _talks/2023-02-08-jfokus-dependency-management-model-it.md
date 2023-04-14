---
title: Dependency Managment? Model it!
slides: https://jacomet.dev/jfokus23_dependency_management
recording: https://youtu.be/MU0Gs7i0D6w
repository: https://github.com/ljacomet/jfokus23_dependency_management/
event-name: Jfokus 2023
event-url: https://www.jfokus.se
---

Dependency hell is a big problem for many teams.
The larger the project and its dependency graph, the harder it is to maintain.
The solutions provided by most dependency management tools are insufficient to effectively deal with this issue.

Gradle offers years of innovations to simplify solving dependency hell and other issues.
It highlights that composing software is much more than adding jars on a classpath:
Gradle offers a metadata format which enables a detailed modeling of software components built around multiple files, providing multiple variants and setting different constraints on their dependencies.

Multiple key concepts of the dependency management landscape of Gradle will be presented:

* Downgrade a dependency version, propagating that information to users of your library
* Constrain logging libraries at build time
* Automatically discover incompatible transitive dependencies (JDK version, API incompatibility, …)
* Align the version of multi jar frameworks
* And more …

For each of these concepts, we will see how application developers can leverage it and how library developers can enrich their published metadata to help their downstream consumers.
