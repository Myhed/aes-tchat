# Tchat socket chiffré en AES

> Ce TP aura pour but de vous faire pratiquer la théorie vue sur le chiffrement AES

Afin de réaliser ce TP vous aurez besoin d'utiliser les librairies suivantes ***socket.io*** et ***aes-js*** 

## Context

Ayant assimilé la théorie d'un chiffrement AES il vous faudra le reproduire sur un tchat en temps réelle à l'aide de socket, chaque client doit avoir une clé unique.
Lorsqu'un utilisateur veut communiquer avec un autre utilisateur il devra posséder sa clé pour chiffrer et lui envoyer des données sinon le récepteur ne pourra pas
recevoir le message et le déchiffrer afin de le récupérer, l'interface graphique doit alors lui signaler que son message n'a pas pu être envoyé.

la clé de l'utilisateur doit avoir une date d'expiration, je vous laisserais le choix technique côté backend pour pouvoir réaliser cette fonctionnalité.

Au moment de l'expiration de la clé d'un utilisateur elle doit être re-calculer puis re-stocker.


## framework && lib UI

Vous aurez le choix de la technologie utiliser pour le front: 

- html/css/javscript natif
- Angular
- React
- ViewJs