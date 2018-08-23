# High-volume storage -NF26-

# Objectifs 

Construire un DW pour stocker les données électorales, et les méthodes d'analyse associées.

# Données

* Données électorales des élections legislatives (se limiter à la période 90-présent, en éliminant les partielles), disponnibles ici, conseil utiliser les données dun ministère de l'intérieur.
* Toutes données de l'INSÉÉ jugées pertinentes.

# Analyse

## Il s'agira de pouvoir répondre aux questions suivantes:

* Taux lors d'un suffrage de vote (ou abstension) à tous les niveaux de granularité géographiques appripriés et disponibles (bureaux, commune, dpt…)
* scores pour les différents mouvements politiques
* Évolution entre les suffrages des taux précités.
* Analyser le vote/abstension et le scores des mvt politiques en fonction de d'indicateurs socio-économiques, p.ex.
        Revenu médian
        Taux de chomage
        Niveau d'étude…

# Attendu

## Principal :

* Modélisation du problème (cf première partie). Cette modélisation n'est pas l'essence de ce projet, ce point devra être traité rapidement.
* La matérialisation des données (ou les multiples matérialisations d'icelles), sous forme de concept. C'est à dire, distribution des données, clef de partitionnement/tri, organisation, etc. Justification, pour chaque type d'analyse imaginée.
* Les méthodes d'analyse (et de comptage) à l'aide d'algo distribués (comme du map et reduce), ou au minimum travaillant en streaming (c'est à dire, sans stocker toutes les données), sous forme de concept.

## Secondaire :

* L'implémentation de la matérialisation
* L'alimentation
* L'implémentation des méthodes d'analyse
