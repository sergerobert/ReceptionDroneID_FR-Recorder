# ReceptionDroneID_FR-Recorder
Ce depot donne une marche  suivre afin d enregistrer les trames d identification des drones. Dans le cadre des textes reglementaires, les UAV (ou AERONEFS CIRCULANT SANS EQUIPAGE À BORD) doivent etre equipe d un « DISPOSITIF DE SIGNALEMENT ELECTRONIQUE OU NUMERIQUE » des que leur masse est superieures a 800 grammes.

La loi n° 2016-1428 du 24 octobre 2016 relative au renforcement de la sécurité de l'usage des drones civils a introduit l’obligation d’équiper certains aéronefs circulant sans personne à bord d’un dispositif de signalement électronique ou numérique. Les textes d’application de cette disposition législative ont été publiés fin 2019 : - décret n° 2019-1114 du 30 octobre 2019 pris pour l'application de l'article L. 34-9-2 du code des postes et des communications électroniques - arrêté du 27 décembre 2019 définissant les caractéristiques techniques des dispositifs de signalement électronique et lumineux des aéronefs circulant sans personne à bord.
Sources : https://www.ecologie.gouv.fr/sites/default/files/notice_signalement_electronique.pdf

L’objectif d’un récepteur est de pouvoir faire des enregistrements des signaux (trames) pour vérifier que le dispositif fonctionne pour un drone de plus de 800 grammes. 
Le code du récepteur est directement inspiré du code Python qui à été publié sur GitHub « GendarmerieNationale/ReceptionInfoDrone », les modifications et ajouts concernent la mise en forme des informations reçues et leurs enregistrements.
Sources : https://github.com/GendarmerieNationale/ReceptionInfoDrone

Une procédure décrit également comment démarrer le dispositif automatiquement sur le site des évolutions du drone sans intervention autre que celle de le mettre sous tension.
La station de réception pourra être installée près de la zone du décollage du drone. Idéalement pour obtenir une meilleure réception sur support au-dessus en vérifiant de ne pas créer un obstacle.

Ce dépôt complète celui qui permet de construire son propre dispositif de signalement « DIY-ESP32-Arduino-Signalement-Drone ». Il est recommandé de prendre connaissance des informations déjà.

Il y a donc deux parties dans cette publication :
-	Le paramétrage d’un Raspberry PI 3 avec le noyau et les modifications permettant de recevoir les informations, les décoder, les formater et les enregistrés.
-	Un programme python «json.py »  modifié par rapport au dépôt initial.
