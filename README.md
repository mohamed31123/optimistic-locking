# Projet de Optimistic locking
## Description : 
#### Ce projet a pour objectif d’illustrer et de comprendre le mécanisme de **verrouillage 

optimiste (Optimistic Locking)** dans une application Java utilisant **JPA**. Il montre comment implémenter ce mécanisme à l’aide de l’annotation 
## `@Version` afin de détecter les modifications

concurrentes sur une même entité en base de données. Le projet simule un scénario de réservation 

où plusieurs threads tentent de modifier simultanément la même réservation, ce qui permet de provoquer volontairement

un conflit de concurrence. À travers cette simulation, l’application met en évidence la levée de l’exception `

OptimisticLockException` et démontre différentes stratégies pour la gérer, comme la détection du conflit 

ou la mise en place d’un mécanisme de retry. L’objectif pédagogique est de comprendre comment prévenir

les pertesde données lors d’accès concurrents et d’appliquer correctement le verrouillage optimiste 

dans une architecture basée sur JPA.

##  Archetecture de projet : 




## Diagramme de Classe 













## Technologies utilisées : 






## Conclusion : 






#  Auteur : 

## EDDINARI MED 


