---
title: Protéger son organisation des attaques par le système de build
slides: assets/files/protecting-attacks-build.pdf
event-name: Devoxx France
event-url: https://cfp.devoxx.fr/2022/index.html
---

Tous les jours, les développeurs assemblent du code des dizaines de fois.
Parfois de façon transparente dans l’IDE, explicitement en ligne de commande ou sur l’environnement de CI.
Lors de ces actions, la notion de sécurité est souvent reléguée au second plan voire simplement ignorée.

Cette présentation illustrera les vecteurs d’attaque et expliquera comment les mitiger.
L’outil de build est par définition à risque car il s’agit d’un environnement d’exécution.
Certaines pratiques permettent heureusement de réduire significativement ces risques:

* S’assurer que les dépendances sont celles attendues
* Rejeter les dépendances vulnérables (Log4j??)
* Avoir un build reproductible
* Utiliser un environnement éphémère
* Valider les contributions externes

Nous illustrerons ces points avec Gradle mais la plupart des recommandations sont valables pour Apache Maven aussi.
