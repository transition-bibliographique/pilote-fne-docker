# pilote-fne-docker

Configuration docker 🐳 pour déployer le projet pilote-fne.

Cette configuration contient : 

Un programme Java de chargement de données d'autorité vers un Wikibase : https://github.com/transition-bibliographique/pilote-fne

Prometheus, qui permet d'agréger des indicateurs.

MySQLD-Exporter, qui permet de récupérer des indicateurs sur des bases de données MySQL / MariaDB.

Grafana, qui propose des tableaux de bord permettant de consulter les mesures agrégées par Prometheus.


Cette configuration utilise une installation Wikibase, exemple : https://github.com/transition-bibliographique/pilote-fne-wb-docker
