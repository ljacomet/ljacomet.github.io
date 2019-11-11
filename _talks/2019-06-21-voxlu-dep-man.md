---
title: Gestion de dépendances en pratique avec Gradle 5
slides: voxxed-lux-gestion-deps
recording: https://www.youtube.com/watch?v=IMw9eQ-O9nI
event-name: Voxxed Days Luxembourg
event-url: https://voxxeddays.com/luxembourg/
---

En tant que développeur vous devez garder le contrôle des dépendances ajoutées au `classpath` de votre application, vous assurer que les version soient compatibles, potentiellement exclure certaines versions qui ont des bugs affectant votre cas d’utilisation et faire le suivi des nouvelles versions.

Bien que Gradle ait toujours fourni un ensemble d'options pour gérer ces problèmes complexes, les versions récentes de Gradle 5.x ont ajoutés un ensemble de fonctionnalités qui améliorent encore l’outil.

Le but de cette présentation est de montrer ces fonctionnalités et d’offrir des recettes à appliquer pour résoudre certains problèmes:

* `dependencyInsight` vous donne des informations étendues sur une dépendance et sa version,
* Automatisation des mises à jour de version des librairies internes dont vous dépendez avec le “locking” et la publication des versions résolues,
* Avec les plateformes virtuelles et l’alignement, vous pouvez garantir qu’en ensemble de librairies fonctionnant ensemble partagent une version commune.
