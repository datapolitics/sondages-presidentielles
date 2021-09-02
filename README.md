<div align="center" id="top"> 


  <!-- <a href="https://{{app_url}}.netlify.app">Demo</a> -->
</div>

<h1 align="center">sondages-presidentielles</h1>

<br>

## :dart: A propos ##

Ce projet contient les datasets constitués par Datapolitics dans le cadre de ses travaux sur la présidentielle 2022.


## :white_check_mark: Requirements ##

Aucune dépendance


## ▶️ Détails des données disponibles ##

- **candidats2022.json** est la la liste des candidats déclarés ou préssentis, avec des information sur leur parti, leur couleur politique et leur déclaration de candidature. Ce fichier sera mis à jour au cours de la campagne. 

- **noms_candidats.csv** est la même liste mais uniquement avec les noms, et au format CSV. Ce fichier sera mis à jour au cours de la campagne. 

- **race2022.json** est la liste des candidats avec pour chacun d'eux, le score estimé lors du dernier sondage réalisé, ainsi que la tendance (hausse, baisse, stagnation). La tendance est calculée sur les 2 derniers points d'une agrégation en plusieurs étapes [voir méthodologie ici]( https://datapolitics.fr/methologie-notation-sondeurs/). Pour les candidats avec trop peu de sondages, il n'y a pas de tendance calculée.

- **notations.json** contient la notation attribuée à chaque sondage par l'agrégateur de datapolitics [voir méthodologie ici]( https://datapolitics.fr/methologie-notation-sondeurs/). Pour les candidats avec trop peu de sondages, il n'y a pas de tendance calculée.

- **presidentielleX** est contient l'ensemble des données des sondages de la campagne présidentielle de l'année X extraites des tables wikipédia des pages concernant les diffférentes élections. Il y a un fichier json par élection

- **resultats_presidentielles.json** est l'ensemble des résultats nationaux des élections présidentielle en France entre 1988 et 2017


## Points d'attentions ##

Les données des sondages des présidentielles précédentes ont été extraits depuis Wikipédia.
A ce titre, nous ne pouvons pas garantir l'exactitude de ces données.
Par ailleurs, certaines données sont incomplètes, ce qui est matérialisé par des tags "A_INSERER_MANUELLEMENT".
Cela signifie que la donnée correspondante n'était pas présente dans la table Wikipédia.

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

This article uses material from the Wikipedia article <a href="https://en.wikipedia.org/wiki/Metasyntactic_variable">"Metasyntactic_variable"</a>, which is released under the <a href="https://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-Share-Alike License 3.0</a>.

Pages wikipédia utilisées : 
- https://fr.wikipedia.org/wiki/Liste_de_sondages_sur_l%27élection_présidentielle_française_de_2017
- https://fr.wikipedia.org/wiki/Liste_de_sondages_sur_l%27élection_présidentielle_française_de_2012
- https://fr.wikipedia.org/wiki/Liste_de_sondages_sur_l%27élection_présidentielle_française_de_2007
- https://fr.wikipedia.org/wiki/Liste_de_sondages_sur_l%27élection_présidentielle_française_de_2002
- https://fr.wikipedia.org/wiki/Élection_présidentielle_française_de_1995
- https://fr.wikipedia.org/wiki/Élection_présidentielle_française_de_1988
