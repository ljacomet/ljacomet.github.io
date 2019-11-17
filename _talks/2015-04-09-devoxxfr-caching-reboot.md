---
title: Caching reboot&#58; javax.cache & Ehcache 3
recording: https://www.youtube.com/watch?v=cnj7b98KeRU
slides: https://www.slideshare.net/LouisJacomet/caching-reboot-javaxcache-ehcache-3
event-name: Devoxx France
event-url: https://devoxx.fr/
---

Après plus de 10 ans, Java a maintenant une API standard pour le cache, telle que délivrée par la JSR-107. En parallèle, Ehcache, cette bonne vieille librairie de 10 ans d’âge, va renaître.

Ehcache 3 est en effet annoncée: compatible JSR-107, API entièrement "générifiée", les bons morceaux des versions 2.x et quelques innovations.

Cela peut sembler beaucoup à digérer en une fois. De ce fait la présentation suivra le rythme d’un bon repas:

* En entrée, vous découvrirez l’API et les fonctionnalités de la JSR-107.
* Le plat principal couvrira des cas d’utilisation pratiques d’un cache. Cela nous permettra de comprendre ce que javax.cache offre mais aussi les manquements. Cela sera servi avec une découverte des fonctionnalités additionnelles de Ehcache 3. Vous découvrirez comment en bénéficier sans devoir abandonner la seule dépendance au standard.
* Pour le dessert, nous jetterons un coup d’oeil à des morceaux choisis de Ehcache 3 qui le rende unique comparé aux autres offres de cache, y compris les anciennes versions.