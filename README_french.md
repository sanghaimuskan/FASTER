[! [État de build] (https://travis-ci.org/Microsoft/FASTER.svg?branch=master)] (https://travis-ci.org/Microsoft/FASTER)
[! Gitter (https://badges.gitter.im/Microsoft/FASTER.svg)] (https://gitter.im/Microsoft/FASTER?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Introduction

Gestion de l'état d'application volumineux facilement et avec des performances élevées est l'un des problèmes les plus difficiles
dans le nuage aujourd'hui. Plus rapide est un magasin de valeurs clés simultanées + cache qui est conçu pour les recherches ponctuelles et les mises à jour lourdes. Plus rapide prend en charge les données plus grandes que la mémoire, en tirant parti du stockage externe rapide. Il prend également en charge la récupération cohérente à l'aide d'une nouvelle technique de point de contrôle qui permet aux applications de négocier des performances de latence de validation.

Les caractéristiques suivantes de plus rapidement le différencier d'un point de vue technique:
1. Latch-cache libre-index optimisé.
2. unique "Hybrid record log" de conception qui combine un traditionnel permanent Append-Only log avec mises à jour sur place, pour façonner la mémoire de travail ensemble et conserver par
