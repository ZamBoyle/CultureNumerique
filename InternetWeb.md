
**Table des matières**:
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Introduction à Internet](#introduction-à-internet)
  - [1. Qu'est-ce qu'Internet pour vous ?](#1-quest-ce-quinternet-pour-vous)
  - [2. Définition](#2-définition)
  - [3. Histoire](#3-histoire)
    - [3.1 Arpanet](#31-arpanet)
    - [3.2 Internet](#32-internet)
  - [4. Comment communique tout ce bazar ?](#4-comment-communique-tout-ce-bazar)
- [](#)
- [Introduction au World Wide Web (WWW)](#introduction-au-world-wide-web-www)
  - [1. Qu'est-ce qu'Internet pour vous ?](#1-quest-ce-quinternet-pour-vous-1)
  - [2. Définition](#2-définition-1)
  - [3. Histoire](#3-histoire-1)
  - [5. WEB](#5-web)

<!-- /code_chunk_output -->

#1. Introduction à Internet
Nous allons parler d'Internet du point de vue du développeur. Nous n'allons pas entrer dans les détails du fonctionnement d'Internet. C'est un parti pris. L'essentiel pour nous est que vous compreniez: d'où on vient, comment il fonctionne en gros, la notion de port et quelques protocoles.

#1. Qu'est-ce qu'Internet pour vous ?

#2. Définition
Internet est LE réseau mondial d'ordinateurs connectés entre eux. Il s'agit d'un réseau de réseaux. Ces ordinateurs sont connectés de différentes manières, câble réseau/ethernet, fibre optique, wifi, courant (cpl), lumière (li-fi), réseaux mobiles, satellites, etc. Pour communiquer sur Internet, les ordinateurs utilisent le protocole TCP/IP (Transmission Control Protocol/Internet Protocol). 

Une fois la pile TCP/IP chargée pour la communication réseau. Il existe d'autres protocoles qui viennent s'ajouter à TCP/IP: FTP (File Transfert Protocol=transfert de fichiers), http, https, SMTP, dns, VoIP, etc

Mais pour fonctionner sur Internet, tous ces protocoles reposent sur le protocole de communication d'internet qui s'appelle TCP/IP. Les réseaux d'entreprises et voire votre réseau privé, utilise TCP/IP pour fonctionner. En effet, il est assez "facile" à mettre en place. Il existe d'autres protocoles qui ont eu leur succès par le passé: IPX/SPX (Novell), NetBEUI/NetBios (IBM), AppleTalk, etc.

Pour beaucoup de monde, Internet c'est Google. En disant Google, ils parlent du moteur de recherche. Mais le moteur de recherche est un des applications d'Internet utilisant les protocoles http/https.

#3. Histoire
Parler d'internet c'est aussi parler de son Internet était à la base un projet militaire. L'objectif à un réseau de faire transiter l'information même si l'un des éléments de ce réseau disparaît (bombe, déconnexion, etc). Cette pensée d'une topologie réseau fonctionnant 
##3.1 Arpanet
##3.2 Internet
#4. Comment communique tout ce bazar ?
Dans les cours de communication, le schéma de la communication suivante revient très souvent:
1. Un émetteur émet un message.
2. Le message est codé (dans une langue).
2. Le message est transmis sur un canal.
3. Le récepteur reçoit le message.
4. Le récepteur décode le message.

Le récepteur devient l'émetteur et l'émetteur devient le récepteur. C'est ainsi que deux personnes peuvent communiquer.

Cette analogie est intéressante car correspond aussi à la communication entre ordinateurs sur Internet. Pour communiquer les ordinateurs

#







#Introduction au World Wide Web (WWW)

##1. Qu'est-ce qu'Internet pour vous ?

##2. Définition

##3. Histoire

##5. WEB
###5.1 L'histoire

1974: deux américains commencent à connecter des ordis via le réseau téléphone: l'internet protocole: ip. Les paquets prennent différents chemins: Commutation par paquets (paquets reconstruits)

En 1989: on envoie des emails

12 mars 1989
Tim Berners-Lee propose à son supérieur Mike Sendall un projet de gestion des informations générales sur les accélérateurs et les expériences au CERN basé sur un système hypertexte distribué5. L'annotation de Sendall, qualifiant le projet de « vague mais prometteur » en est le point de départ car elle autorise Tim Berners-Lee à travailler dans ce domaine

Au CERN il faut traiter une tonne de données et les scientifiques doivent partager leurs informations et les consulter.

Robert Cailliau comprend où Tim veut aller.
Utiliser l'hypertexte et Internet: Naviguer entre documents via Internet.
Tim va créer le protocole HTTP, le HTML et l'URL (adresse unique).
Ils reçoivent un budget et au bout de 2 ans.
Ils trouvent un nom: Le World Wide Web.

Ils n'arrivent pas à créer un navigateur entre l'homme et le SI, facile et universel (type d'ordinateur, modèle, marque)

1993 (4 ans de trav): Ils vont prendre la décision d'ouvrir le logiciel du web au public de la disposition du monde. Aucun revenu mais Tim sait que s'il ne libère pas le web, il mourra. Ils l'envoient à une dizaine de personnes via mail. ==> Perte du contrôle du web par Robert Cailliau et Tim.
22 avril 1993: Marc Endressens crée Mosaic. 206 sites internet mais le navigateur est téléchargé plus d'1 million de fois en quelques mois ==> Le Web explose.

1 an et demi plus tard ce jeune étudiant Marc Endressens va avoir un 17 millions de dollars

13 octobre 1994: Netscape
1996: 90% des internautes l'utiliseront.

Pensé dès le départ universel tout ordinateur !!!! Ont la conviction que leur invention peut changer le monde.














====================================
Interview
========================================






Depuis 20 ans une techno végète un peu.


Le britannique Tim Berners-Lee et le belge Robert Cailliau.









 Imaginons que je sois un espion style 007. Et que j'ai besoin d'un mot de passe de session de l'ordinateur du super vilain. Je pourrais mettre entre le câble de son clavier et de la tour un petit boîtier qui détecterait la pression des touches. Une lumière infrarouge s'allumerait un certain nombre de fois en fonction de la . et que j'observe ma filature depuis l'appartement en face du mien. On pourrait imaginer un autre canal de communication serait initié entre ma caméra qui observera une lampe infrarouge qui s'activerait dès que l'on tape sur un clavier.