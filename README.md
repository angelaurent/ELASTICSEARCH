# BASE DE DONNEES ORIENTEES DOCUMENT : ELASTICSEARCH

#TACHE EXECUTEE
 1.MIS EN PLACE D'UN CLUSTER ELASTICSEARCH AVEC DOCKER-COMPOSE
 2.IMPLEMENTATION DE LA SCALABILITE, TOLERANCE AUX PANNES,SHARDING 
 3.CHARGEMENT DE NOTRE JEU DE DONNEES.
 4.OPERATION CRUD.
 5.FAIRE DU REQUETAGE SUR NOTRE JEU DE DONNEES.

#ELASTICSEARCH QU'EST CE QUE C'EST?
Capable de stocker une grande quantité de documents et que l’on peut interroger en temps réel .
Adapté aux donnees semi-structurées et aussi de manipuler les données contenant des informations avec une structure complexe
Moteur de recherche et d'analyse distribuée.
Logiciel écrit en JAVA.
permet le stockage de données sous forme JSON ou XML
Open source.
permet d'effectuer des recherches rapides car dispose d'Apache LUCENE pour l'indexation et la recherche de données.

# cette base de donnees dispose de son langage de requete appelé : DOMAIN SPECIFIC LANGUAGE (DSL)  
Le format ressemble à l'écriture d'un document JSON.Très flexible et permet de réaliser des recherches simples ou complexes en combinant des filtres, des agrégations, des suggestions,
des fonctions de score et bien plus encore. 

#UTILISATION DE KIBANA (Pour faciliter nos operations sur cette base de données nous avons utiliser le client kibana que nous avons aussi installer sur docker)
Outil de visualisation et de gestion des données pour ElasticSearch. 
Fournit une interface graphique accessible par un navigateur web à l’URL http//:localhost:5605.
permet de réaliser des recherches.
Pour bien fonctionner, Kibana a besoin d'un serveur ElasticSearch fonctionnel.

#PARTICULARITE DE CETTE BASE DE DONNEES
1.Vitesse
2.Scalabilité
3.Résilience au pannes
4.Architecture distribuée et modulaire
5.Langage de requête (DSL)
6.Extensible et personnalisable
7.Flexible
8.Sans schema

#USE CASE
1.Journalisation et analyse des journaux
2.Recherche et requête rapide
3.Sécurité
4.E-commerce
5.Visualisation des données
6.Analyse des métriques et évènements
