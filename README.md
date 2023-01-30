# pilote-fne-docker

Configuration docker 🐳 pour déployer le projet pilote-fne.

Cette configuration contient : 

- Un programme Java de chargement de données d'autorité vers un Wikibase : https://github.com/transition-bibliographique/pilote-fne

- Prometheus, qui permet d'agréger des indicateurs.

- MySQLD-Exporter, qui permet de récupérer des indicateurs sur des bases de données MySQL / MariaDB.

- Grafana, qui propose des tableaux de bord permettant de consulter les mesures agrégées par Prometheus.


Cette configuration utilise une installation Wikibase, exemple : https://github.com/transition-bibliographique/pilote-fne-wb-docker

[![](https://docs.google.com/drawings/d/e/2PACX-1vQroATRULEelvPYeknKTq9d92uV_i8KE_Kzr-8bkukbRYCVnBjEhK3-dElfP5_4SNliZZqVX99RIZz0/pub?w=859&h=554)](https://docs.google.com/drawings/d/1x8U44FFEeXPOOVKPDmv0SvOMPW0tYIW4fWHAND8Ja-Q/edit?usp=sharing)
