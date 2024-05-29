# Projet PeerCollabPolicy

Ce projet a été réalisé lors de l'UE "Analyse des réseaux" de M1 IREF. Il vise à analyser l'impact d'une intervention politique visant à encourager les collaborations scientifiques entre chercheurs. Un réseau de scientifiques a été observé avant et après cette intervention pour évaluer son efficacité.

## Le projet comprend les éléments suivants

**Données** : Deux fichiers CSV contenant les informations sur les individus et les dyades.

**Code** : Un notebook Jupyter (.ipynb) pour l'analyse du réseau.

**Rapport** : Un rapport PDF expliquant les résultats et les conclusions de l'analyse.

## Données

Les données utilisées dans ce projet sont réparties en deux fichiers CSV :

- **nodes.csv** : Contient des informations invariables dans le temps sur les agents individuels.

id : Identifiant individuel

coord : Indique si la personne est le coordinateur scientifique du cluster

core : Indique si la personne a été identifiée comme membre "core" du cluster avant le traitement

gender : Indique le genre de la personne (1 si femme)

- **edges.csv** : Contient des informations variables dans le temps sur les dyades.

source : Identifiant du premier nœud de la dyade

target : Identifiant du deuxième nœud de la dyade

pre_link : Collaboration scientifique active dans la dyade avant traitement

post_link : Collaboration scientifique active dans la dyade après traitement

## Objectifs

Représenter et analyser la structure du réseau et son évolution entre les deux périodes (avant et après traitement) avec des statistiques et des graphiques de réseau pertinents.
Discuter des connexions du réseau en ce qui concerne les attributs de base et de genre. Par exemple, explorer si les femmes ont des réseaux moins/plus denses que les hommes, ou si elles sont moins/plus centrales dans le réseau.


