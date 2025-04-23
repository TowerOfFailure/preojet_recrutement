# projet_recrutement

L'idée est de scrapper les différents site en fonction des informations disponibles sur les différents sites de recrutement, et d'afficher les mots clés sayants pour un poste donnée, avec une certaine experience.
 - Cela pourra aider les demandeur.se.s d'emplois à mieux organiser leurs CVs pour ces postes.
 - Ainsi qu'à repérer les entreprises les plus valorisantes et en accord avec leurs valeurs.
Cela pourra aussi permettre de voir les erreurs ques font certaines offres d'emplois, pour aider les entreprise à voir leurs propres biais et incohérences (poste de junior avec 3 ans d'experience)

## To do list: 
    [] Scrapping
        [] Création du logiciel de scrapping automatique à partir d'une liste de site et de mots clés
        [] Faciliter la modification de la liste de site (UI? App?)
    [] Conservation des données
        [] Conservation et tri des données des sources diverses dans une base de données MongoDB pour faire un premier tri (flexibilité pour les différentes sources)
        [] Fusionner ses données dans une base SQL pour une facilité d'accés des données (et vérification de la redondance)
    [] Créer une data visualisation afin d'observer les différentes tendances (Power BI? Python? Dataiku?)
    [] Dockerisation du projet
        [] Passage par des volumes
        [] Utilisation d'un docker compose/Kubernetes