---
title: Naviguer dans le Labyrinthe de la Gestion de Dépendances
co-speaker: Hervé Boutemy
slides: assets/files/devoxxfr-labyrinthe-dm.pdf
event-name: Devoxx France
event-url: https://www.devoxx.fr/schedule/talk/?id=44907
---

La gestion de dépendances est une partie cruciale mais complexe du développement d'applications modernes, souvent enveloppée de mystère et, avouons-le, parfois source d'angoisse !
Le périple commence dans le domaine de la JVM, où Gradle et Maven proposent des approches divergentes pour la résolution des dépendances, la gestion des conflits et les mécanismes de contrôle par l'utilisateur.
Élargir le champ d'application à l'univers NPM révèle encore plus de contrastes.

Les différences clés émergent à partir de la gestion des dépôts centraux - comme Maven Central ou NPM registry - notamment en termes de confiance et de sécurité.
Au sein d'un projet, le processus de résolution, les mécanismes de mise en cache et d'autres facteurs peuvent avoir un impact significatif sur la fiabilité et la reproductibilité des builds.
Ces éléments influencent également ce qui apparaît dans les Software Bill Of Materials (SBOMs) et comment des outils comme GitHub fournissent des informations sur les graphes de dépendances pour les projets hébergés.

Cette session vise à doter les participants de connaissances approfondies sur ces paysages variés.
Comprendre les subtilités, les choix et les limites des technologies utilisées est essentiel.
Notre objectif est de vous fournir les connaissances et stratégies nécessaires pour éviter le redouté 'enfer des dépendances' dans votre prochain projet, assurant ainsi un processus de publication et de release fluide et sécurisé.