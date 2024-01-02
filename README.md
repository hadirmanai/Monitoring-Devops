# Monitoring-Devops
Tout d'abord j'ai suivi le tp et j'ai faire tous les commandes de l'installer de Prometheus avec Helm et le monitoring du cluster et les étapes pour le déployement de notre application. Voici les captures suivante:

L'interface de service goprom

![text](1.png)

L'interface de service goprom-metrics

![text](2.png)


voila la capture pour  vérifiée que prometheus récupère bien les métriques de l’application avec la requête PromQL :

![text](4.png)

Et derniérement étape j'ai installer et configurer Grafana pour visualiser les requêtes :

Connection a grafana :   

![text](5.png)

L'ajout de DataSource : 

![text](6.png)

et finalement la visualisation du graph :

![text](8.png)
