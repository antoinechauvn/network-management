# network-management
Découverte du processus de gestion des réseaux

### Qu'est-ce que la gestion de réseau ?
Le protocole de gestion de réseau (NMP) est une suite de protocoles de réseau qui définissent les processus, les procédures et les politiques de gestion, de surveillance et de maintenance d'un réseau informatique. Le NMP transmet et gère les opérations et les communications effectuées sur un réseau informatique.



## Principe de fonctionnement
Il existe 2 principaux types de fonctionnement:
* Query-Based ou Polling Based: Le NMS (Network Manager Station) envoie une requête à un appareil afin d'extraire des données.

* Event-based: Le NMS écoute les annonces

Dans le SNMP on utilise:
* ICMP
* SNMP
* WMI

![image](https://user-images.githubusercontent.com/83721477/168546791-955c897e-35ac-4fea-b61a-f035036fa1f1.png)

Le système gère les périphériques réseau tels que les commutateurs, les routeurs, les points d'accès et les contrôleurs sans fil.<br>
Il utilise généralement un serveur centralisé pour collecter les données des éléments du réseau. Le serveur peut être situé sur site, dans un centre de données privé ou dans le cloud.<br>

Les appareils, les clients et les applications sur le réseau peuvent envoyer des données au serveur avec des mises à jour sur leur état. Les administrateurs réseau peuvent surveiller les opérations du réseau en se connectant au serveur, généralement via un navigateur Web ou une application pour smartphone.<br>

Les périphériques réseau envoient généralement des données au système de l'une des deux manières suivantes :

* **SNMP :** Le protocole de gestion de réseau simple est une norme ouverte. Il est largement pris en charge par la plupart des fabricants d'éléments de réseau. Le système de gestion de réseau utilise SNMP pour « interroger » chaque élément du réseau. Chaque élément envoie alors une réponse au système.

* **Télémétrie :** Un agent logiciel installé dans un élément du réseau permet la transmission automatique des indicateurs clés de performance en temps réel. La télémétrie remplace rapidement SNMP, car elle est plus efficace, peut produire beaucoup plus de points de données et est plus évolutive. Et les normes de télémétrie, telles que NETCONF/YANG, gagnent du terrain en tant que moyens d'offrir le même support multifournisseur que SNMP.
