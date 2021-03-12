# interview_bioc

Bienvenue sur le test Data science Biocéanor: 

Vous trouverez dans le repo, un csv contenant des données sur des prélèvements effectués à Lorient sur 6 points de mesures différents (colonne "Site"). 

Vous disposez d'information sur les paramètres suivants: 

- E.coli: Taux de E.coli dans l'eau 	
- E.coli_qualite: Interprétation du taux de E.coli 
- °C: Température de l'eau 
- ppt: Salinité de l'eau
- %: Oxygène dissous en % 
- pH:Ph mesuré 

Ces prélèvements ont été effectués par la ville sur plusieurs années. Votre client n'a jamais vraiment utilisé ces données mais vous demande de les analyser pour voir si vous pouvez en retirer des tendances sur l'évolution des paramètres. 

Les mesures ont été effectuées par des personnes n'étant pas forcément familières avec l'utilisation des données, il se peut donc qu'un pré travail soit nécessaire sur les données. (exemple: un ph de moins de 7.5 ou de plus de 8.5 est une erreur de mesure)
#### Que faire?

- Présentez un notebook avec des graphes montrant les différentes informations que vous avez pu extraire de ces données. 
- Forkez le repo pour y déposer vos fichiers.

###### IMPORTANT: 
- Dans votre code laissez bien toutes les étapes que vous avez faites pour parvenir à vos résultats. 
- Fournissez également une liste de dépendances pour que nous puissions faire tourner votre code/notebook. 

###### Idées de résultats attendus:
- Evolution au fil des années
- Evolution de l'amplitudes entre les valeurs extrèmes des paramètres au fil des années
- Analyse d'évennements anormaux à un moment donné.

###### Bonus:
- Si un paramètre vous apparait comme ayant suffisament de données pour le modéliser, tentez de fiter un modèle. 
