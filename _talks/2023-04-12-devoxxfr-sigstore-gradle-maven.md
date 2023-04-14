---
title: Sécurité de la chaîne logicielle avec Sigstore
co-speaker: Hervé Boutemy
repository: https://github.com/ljacomet/sigstore-devoxx
slides: assets/files/devoxxfr-sigstore-maven-gradle.pdf
event-name: Devoxx France
event-url: https://cfp.devoxx.fr/2023/talks
---

L’utilisation de dépendances est un des piliers de la construction d’applications ou de services en Java.
Et les hackers l’ont bien compris! Il devient de plus en plus important de maîtriser la sécurité de la chaîne logicielle de bout en bout.
Un des éléments est de pouvoir s’assurer qu’une nouvelle version d’une librairie a bien été publiée par ses auteurs.

C’est là qu’intervient Sigstore, un nouveau standard pour signer, vérifier et protéger le logiciel.
Les membres de l’OpenSSF (Open Source Security Foundation) développent cette initiative pour les différents langages et écosystèmes.

Qu’est-ce que cela veut dire pour l’écosystème JVM et son repository par défaut Maven Central?

Dans cette université, nous aurons l'occasion de développer les points suivants:

* Qu’est-ce qu’une signature Sigstore? Et comment la créer ou la vérifier.
* Maven Central et Sigstore, comment ça marche?
* Impacts pour Maven et Gradle
  * Publication de composants signés
  * Vérification des signatures Sigstore
