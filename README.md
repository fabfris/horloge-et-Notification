# horloge-et-Notification
Ce sont les sources liés à l'article sur mon blog byfeel.info , concernant la mise en place d'une horloge avec notification a base d'un WEMOS D1

Collez les deux fichier dans le meme repertoire puis ouvrir avec votre interface IDE Arduino le fichier Horloge_wemos_ota

Variable à definir avant compilation dans votre module

#define NOMMODULE "ESP-Horloge_Nom"   // nom module

#define NTPSERVER "pool.ntp.org"         // Serveur NTP

#define ACTIVBOUTON true              // Si bouton installé

#define ACTIVCAPTLUM true              // Si capteur luminosité installé

#define  BUF_SIZE  60                    // Taille max des notification ( nb de caractéres max )

Plus de detail dans l'article DIY Horloge et Notification sur mon blog http://byfeel.info

Historique version :

V3.1.1 : Mise a jour bug dht

V3.1 : Nouvelle version ( Novembre 2018 )


--------------------------------------------
Si pas intéressé par fonction avançés interface web - V2.6 suffit


V2.6 : Ajout affichage Horloge ( font personalisé ) - pour un affichage plus PRO.

V2.5 : Enregistrement des options en EEPROM , pour sauvegarde aprés coupure de courant
Gestion de deux ZONES

!!!!!!!!!!!!!!!!!!!!

V2.45 : Utilisation des bibliotheque V3 de parola et MAX72xx  !!!!!!!!

!!!!!!!


V2.4 : Remontée d'info dans jeedom

V2.3 : Ajout de la gestion de la luminosité et des animations depuis jeedom

V2.2 : Animation PAC Man

V2.1 : Gestion des clicks - Ajouts des animations

V2 : Ajout support bouton / refonte du code

V1.3 : Ajout interface WEB

V1.2 : Ajout du support de notification

V1 : Debut projet / affichage Horloge avec gestion NTP
