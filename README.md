# Application Météo

Cette application est un composant Vue.js qui permet aux utilisateurs de rechercher des prévisions météorologiques pour différentes villes et pays.

## Fonctionnalités

- **Recherche de ville** : Les utilisateurs peuvent rechercher des villes en entrant le nom de la ville dans le champ de recherche. Les suggestions de villes apparaissent au fur et à mesure que l'utilisateur tape.

- **Recherche de pays** : Les utilisateurs peuvent également rechercher des pays. Cette fonctionnalité est désactivée par défaut et peut être activée en cochant la case "Pays != France ?". Les suggestions de pays apparaissent au fur et à mesure que l'utilisateur tape.

- **Prévisions météorologiques** : Une fois qu'une ville a été sélectionnée, l'application récupère les prévisions météorologiques pour les trois prochains jours à partir de l'API WeatherAPI. Les informations affichées comprennent la date, la température maximale et minimale, la condition météorologique et une icône représentant la condition météorologique.

## Comment ça marche

L'application utilise Vue.js pour la logique de l'interface utilisateur et Axios pour les requêtes HTTP. Les données de la ville et du pays sont récupérées à partir de l'API GeoDB, tandis que les données météorologiques sont récupérées à partir de l'API WeatherAPI.
