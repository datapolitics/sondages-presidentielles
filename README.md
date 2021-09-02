# presidentielle

Ce repository contient les datasets suivants : 

- **candidats2022.json** est la la liste des candidats déclarés ou préssentis, avec des information sur leur parti, leur couleur politique et leur déclaration de candidature. Ce fichier sera mis à jour au cours de la campagne. 

- **race2022.json** est la liste des candidats avec pour chacun d'eux, le score estimé lors du dernier sondage réalisé, ainsi que la tendance (hausse, baisse, stagnation). La tendance est calculée sur les 2 derniers points d'une régression polynomiale locale [régression polynomiale locale]( https://en.wikipedia.org/wiki/Local_regression). Pour les candidats avec trop peu de sondages, il n'y a pas de tendance calculée.

- **presidentielleX** est contient l'ensemble des données des sondages de la campagne présidentielle de l'année X extraites des tables wikipédia des pages concernant les diffférentes élections. Il y a un fichier json par élection

- **resultats_presidentielles.json** est l'ensemble des résultats nationaux des élections présidentielle en France entre 1988 et 2017

# licence GNU 3.0


<div align="center" id="top"> 


  <!-- <a href="https://{{app_url}}.netlify.app">Demo</a> -->
</div>

<h1 align="center">presidentielle</h1>

<br>

## :dart: A propos ##

Ce projet contient les datasets constitués par Datapolitics dans le cadre de ses travaux sur la présidentielle 2022.


## :white_check_mark: Requirements ##

Aucune dépendance


## ▶️ Détails des données disponibles ##

- **candidats2022.json** est la la liste des candidats déclarés ou préssentis, avec des information sur leur parti, leur couleur politique et leur déclaration de candidature. Ce fichier sera mis à jour au cours de la campagne. 

- **race2022.json** est la liste des candidats avec pour chacun d'eux, le score estimé lors du dernier sondage réalisé, ainsi que la tendance (hausse, baisse, stagnation). La tendance est calculée sur les 2 derniers points d'une régression polynomiale locale [régression polynomiale locale]( https://en.wikipedia.org/wiki/Local_regression). Pour les candidats avec trop peu de sondages, il n'y a pas de tendance calculée.

- **presidentielleX** est contient l'ensemble des données des sondages de la campagne présidentielle de l'année X extraites des tables wikipédia des pages concernant les diffférentes élections. Il y a un fichier json par élection

- **resultats_presidentielles.json** est l'ensemble des résultats nationaux des élections présidentielle en France entre 1988 et 2017


## Points d'attentions ##

Les données des sondages des présidentielles précédentes ont été extraits depuis Wikipédia.
A ce titre, nous ne pouvons pas garantir l'exactitude de ces données.
Par ailleurs, certaines données sont incomplètes, ce qui est matérialisé par des tags "A_INSERER_MANUELLEMENT".
Cela signifie que la donnée correspondante n'était pas présente dans la table Wikipédia.

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

