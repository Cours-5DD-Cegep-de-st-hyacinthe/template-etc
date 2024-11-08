# Épreuve terminale de cours

## CONTEXTE :
Un riche philanthrope vous donne la chance de développer votre propre projet personnel, toute dépense payés (wow!).
Vous avez jusqu’au 20 décembre pour assembler un MVP (Minimum Viable Product), et s’il est assez impressionné il vous engagera comme CTO (Chief Technical Officer) pour une startup qu’il fondera à ce moment-là.

## SPÉCIFICATIONS :
Vous devrez choisir un sujet pour votre épreuve et le réserver avec moi en m’envoyant un MIO. Il ne sera 
pas possible de choisir le même sujet qu’un autre étudiant, donc premier arrivé premier servi! 
Votre application devra vivre à l’intérieur d’un cloud Kubernetes local. Elle devra être composée d’un 
service qui distribue une application front-end, qui communiquera avec un serveur back-end. Ce back-end 
devra être composé d’au moins 2 services et/ou micro-services, un qui recevra les requêtes du front-end 
et communiquera avec l’autre service afin de compléter les requêtes. 
Les deux services back-end pourront communiquer de la manière qui vous convient le mieux (appels REST 
API à travers un service Kubernetes, queue de message, etc.). 
Il se peut que votre architecture demande d’avoir une base de données. Si c’est le cas, vous pourrez aller 
chercher sur internet comment déployer une base de données dans un cloud local. 
Vous avez libre-choix sur les langages et technologies utilisées dans votre projet. 
Vous devrez produire un diagramme de l’architecture de votre système, qui contiendra les différentes 
pièces qui le compose et comment ces pièces communiquent entre eux. 
Il est préférable de faire une démo interactive avec l’enseignant (soit en personne, ou par Teams) afin 
d’éviter des oublis dans la démo. Vous devrez démontrer que l’application est fonctionnelle, qu’elle roule 
dans Kubernetes, et que les pods sont en ligne et sans erreur.
 
## BARÈMES DE CORRECTION :
1. (15%) Diagramme de l’architecture de votre application : 
À l’aide d’un diagramme de votre choix, vous devrez représenter l’architecture de votre 
application. Il devrait y avoir les applications, et comment ces applications interagissent entre eux. 
2. (40%) Utilisation de conception distribué 
3. (30%) Bonne méthode de communication entre les différents services 
4. (15%) Fichiers de déploiement bien construits, ne contiennent que le strict nécessaire 
5. (-40%) Manquements au respect du gabarit, des standards et des conventions abordées dans le cours. 
6. (-40%) Manquements à la traçabilité de votre démarche à travers les traces d'évolution du travail sur 
GitHub Classroom. (Je dois voir la progression évoluer à chaque cours : faites des push souvent!) 
7. (-10%) Fautes de français 
