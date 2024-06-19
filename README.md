# graphql
Ce projet vise à apprendre le langage de requête GraphQL en créant une page de profil utilisateur. Voici un résumé des principales étapes et objectifs :

### Objectif
Créer une interface utilisateur de profil en utilisant les données récupérées via des requêtes GraphQL. La page doit afficher plusieurs informations utilisateur et inclure une section de statistiques générées avec des graphiques SVG.

### Étapes Principales
Page de Connexion :

Créez une page de connexion pour obtenir un JWT nécessaire pour accéder à l'API GraphQL.
Utilisez l'endpoint https://academy.digifemmes.com/api/auth/signin pour authentifier l'utilisateur et obtenir le JWT.
Implémentez l'authentification Basic avec codage base64.
Affichez un message d'erreur en cas d'identifiants invalides.
Fournissez une méthode de déconnexion.
Requêtes GraphQL :

Utilisez l'endpoint https://academy.digifemmes.com/api/graphql-engine/v1/graphql pour interroger les données utilisateur.
Employez le JWT pour les requêtes en utilisant l'authentification Bearer.
Interrogez les tables user, transaction, progress, result, et object pour obtenir les données nécessaires.
Page de Profil :

Affichez au moins trois informations utilisateur (ex : identification de l'utilisateur, montant d'XP, compétences).
Incluez une section de statistiques avec au moins deux types de graphiques SVG.
Les graphiques peuvent inclure des données telles que la progression XP au fil du temps, le ratio des projets réussis/échoués, etc.
Hébergement :

Hébergez la page de profil sur une plateforme de votre choix (ex : GitHub Pages, Netlify).

### Compétences Développées
GraphQL : Maîtrise des requêtes, mutations et gestion des arguments.
GraphiQL : Utilisation de l'interface pour explorer et tester les requêtes.
JWT : Gestion des tokens pour l'authentification et l'autorisation.
SVG : Création de graphiques interactifs et animés.
UI/UX : Conception d'interfaces utilisateurs attractives et fonctionnelles.
Hébergement : Déploiement de l'application sur une plateforme en ligne.
Ce projet fournit une opportunité pratique d'apprendre et de mettre en œuvre diverses technologies modernes, tout en créant une application web interactive et fonctionnelle.











