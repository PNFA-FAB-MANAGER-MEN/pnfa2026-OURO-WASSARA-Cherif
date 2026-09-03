# Cahier des charges fonctionnel

> Livrable L3 · Jalon J1.

## Énoncé du besoin

> **À qui le dispositif rend-il service ?**

Aux établissements scolaires, aux enseignants et aux élèves.

> **Sur quoi agit-il ?**

Sur la gestion des horaires et le déclenchement automatique de la sonnerie scolaire.

>**Dans quel but ?**

Automatiser les sonneries de début et de fin des cours tout en utilisant une alimentation solaire afin de réduire la dépendance au réseau électrique.

En bref : 

> Le dispositif rend service aux établissements scolaires, aux enseignants et aux élèves. Il agit sur la gestion des horaires scolaires et sur le déclenchement de la sonnerie. Son objectif est de programmer et déclencher automatiquement les sonneries correspondant aux différents horaires de l'établissement, tout en utilisant une source d'énergie solaire pour assurer son autonomie énergétique.


## Fonctions de service et contraintes

| Réf. | Fonction                                           | Critère                         | Niveau visé                                      | Flexibilité |
| ---- | -------------------------------------------------- | ------------------------------- | ------------------------------------------------ | ----------- |
| FS1  | Déclencher automatiquement la sonnerie             | Respect de l'horaire programmé  | ± 0.5 min                                          | Faible      |
| FS2  | Permettre la programmation des horaires            | Nombre d'horaires programmables | ≥ 10 horaires/jour                               | Moyenne     |
| FS3  | Alimenter le système à partir de l'énergie solaire | Autonomie énergétique           | Fonctionnement quotidien                         | Faible      |
| FS4  | Informer l'utilisateur de l'état du système        | Affichage/indication de l'état  | Visible et compréhensible                        | Moyenne     |
| FC1  | Être transportable                                 | Dimensions du dispositif        | ≤ 60 × 60 × 60 cm                                | Faible      |
| FC2  | Être simple à utiliser                             | Temps de prise en main          | ≤ 10 min                                         | Faible      |
| FC3  | Fonctionner sans connexion Internet                | Fonctionnement local            | 100 % des fonctions principales                  | Faible      |
| FC4  | Résister à une utilisation quotidienne             | Fiabilité                       | Fonctionnement sur une journée scolaire complète | Faible      |



## Déclinaison des exigences fonctionnelles du programme

| Réf. CDC | Exigence                                                  | Déclinaison sur ce projet                                                                                                  | Vérification prévue                                          |
| -------- | --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| EF-01    | Intention pédagogique explicite                           | Le projet permet aux élèves de mettre en pratique l'électronique, la programmation et l'utilisation de l'énergie solaire.  | Présentation du fonctionnement et démonstration              |
| EF-02    | Mesure et action sur le monde physique                    | Le système utilise des composants électroniques pour commander automatiquement une sonnerie selon les horaires programmés. | Test de déclenchement de la sonnerie                         |
| EF-03    | Restitution exploitable hors internet                     | La programmation et les horaires sont enregistrés localement dans le système.                                              | Test avec Internet déconnecté                                |
| EF-04    | Prise en main élève ≤ 10 min                              | L'interface de programmation des horaires doit être suffisamment simple pour être utilisée rapidement.                     | Test avec un élève/utilisateur                               |
| EF-05    | Transportable, ≤ 60 × 60 × 60 cm, mise en service ≤ 5 min | Le dispositif est conçu sous forme d'un système compact et facilement transportable.                                       | Mesure des dimensions et chronométrage de la mise en service |

