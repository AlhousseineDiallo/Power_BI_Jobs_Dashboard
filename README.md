# Dashboard des Métiers de la Data



## Introduction

Ce tableau de bord a été créé pour **les chercheurs d’emploi, les personnes en reconversion professionnelle et celles qui changent de poste**, afin de résoudre un problème courant : les informations sur le marché de l’emploi dans le domaine des données sont absconses et difficiles à comprendre. En utilisant un jeu de données réel d’offres d’emploi en science des données de 2024 (incluant les intitulés de poste, les salaires et les localisations), ce projet fournit une interface unique et facile à utiliser pour explorer les tendances du marché et les rémunérations.

## Aperçu du projet

Ce projet a été un parcours à travers les principales fonctionnalités de Power BI. Voici un bref aperçu des étapes clés :

- ⚙️**Transformation des données (ETL) avec Power Query** : Nettoyage, mise en forme et préparation des données brutes for l’analyse en traitant les valeurs vides, en modifiant les types de données et en créant de nouvelles colonnes.

- 🧮 **Mesures implicites** : Des mesures ont été créées pour obtenir des informations clés et des KPI, on peut citer entre autres le Median Yearly Salary (Salaire annuel médian) et le Job Count (Nombre d’emplois).

- 📊 **Visualisations** : Utilisation de graphiques en barres, de courbes, etc. pour représenter les données de manière intuitive, facilitant la compréhension des tendances du marché de l’emploi.

- 🗺️ **Cartes géographiques** : Intégration de cartes pour visualiser la répartition géographique des offres d’emploi, permettant de repérer les régions les plus actives.
  
- 🔢 **Indicateurs KPI et tableaux** : Utilisation de cartes pour afficher les indicateurs clés et de tableaux pour fournir des données détaillées et triables.

- 🎨 **Conception du tableau de bord** : Création d’une mise en page intuitive et visuellement attrayante, en explorant à la fois des types de graphiques courants et moins courants pour raconter au mieux l’histoire des données.

- 🖱️ **Interactivité du rapport** :

    - **Segments (Slicers)** : Pour filtrer dynamiquement le rapport par intitulé de poste.

    - **Boutons et signets (Bookmark)** : Pour offrir une navigation fluide.

    - **Drill-through** : Pour passer d’un aperçu global à une vue détaillée et contextuelle.

---

## Vue d'ensemble du Dashboard

*Ce rapport est divisé en deux pages distinctes afin de fournir à la fois un résumé global et une analyse détaillée des données représentées.*

## Page 1 : Vue d'ensemble du marché de l'emploi:

![Page 1](/images/Project1_Dashboard_Page1.gif)

Ce dashboard esthétique est votre guide pour comprendre les tendances et enjeux du marché de l’emploi dans le domaine de la data. Il met en avant des indicateurs clés tels que le nombre total d’emplois, les salaires médians et les principaux intitulés de poste, afin de vous offrir en un coup d’œil une compréhension rapide de la situation du marché.


## Page 2 : Exploration par intitulé de poste (Drill Through)

![Page 2](/images/Project1_Dashboard_Page2.gif)

C’est la page d’exploration approfondie. Depuis le tableau de bord principal, vous pouvez effectuer un drill-through (exploration) vers cette vue pour obtenir des détails spécifiques sur un seul intitulé de poste, y compris les fourchettes de salaires, les statistiques sur le télétravail, les principales plateformes de recrutement et une carte mondiale des lieux d’emploi.

Pour ce faire un bouton de drill-through a été ajouté, permettant de naviguer facilement vers cette page détaillée. Il suffit de cliquer sur un intitulé de poste dans le tableau de bord principal et ensuite de cliquer sur le bouton de drill-through pour accéder à cette vue approfondie.

Un exemple concret serait de cliquer sur "Data Scientist" dans le tableau de bord principal sur le graphique en barre par exemple, puis d’utiliser le bouton de drill-through pour accéder à la page dédiée à ce poste. Vous y trouverez des informations détaillées telles que :
- **Fourchette de salaires** : Visualisation des salaires minimum, maximum et médian pour le poste sélectionné.

- **Statistiques sur le télétravail** : Pourcentage d’offres d’emploi proposant du télétravail, permettant de comprendre les tendances actuelles en matière de flexibilité au travail.
- **Principales plateformes de recrutement** : Liste des sites où les offres d’emploi pour ce poste sont les plus fréquemment publiées, offrant une vue d'ensemble des canaux de recrutement.
- **Carte mondiale des lieux d’emploi** : Visualisation géographique des offres d’emploi pour le poste sélectionné, permettant de repérer les régions les plus actives pour ce métier.


---


## Conclusion
Ce tableau de bord est un outil puissant pour quiconque s’intéresse au marché de l’emploi dans le domaine des données. Il offre une vue d’ensemble claire et des détails approfondis, permettant aux utilisateurs de prendre des décisions éclairées sur leur carrière. Que vous soyez un chercheur d’emploi, un professionnel en reconversion ou simplement curieux des tendances du marché, ce tableau de bord est conçu pour répondre à vos besoins.