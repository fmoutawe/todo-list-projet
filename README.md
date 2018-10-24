# Liste des actions à prévoir dans un projet

## Choix de la technologie
* Définir les marchés cibles (web, mobile, tablette)
* Définir la compétence des équipes et la tendance de l'emploi
* Effectuer, si nécessaire, des benchmarks des produits afin de déterminer les plus efficaces
* Choisir une technologie correctement documentée et supportée

## Documentation
* Afin de diriger le projet, il est important de commencer avec des spécifications fonctionnelles précises et le plus microscopiques possibles. Ce cadre permet de moins se tromper lors du développement du produit.
* Débuter une documentation au démarrage du projet et s'astreindre à le maintenir.

## Environnement de développement
* Mettre en place un environnement facile à mettre en place (Docker par exemple)

## Gestionnaire de source
* Mettre en place un gestionnaire de source (Git par exemple) afin de conserver une tracabilité du code et des différentes interactions faites dans le temps
* Afin de garder un historique propre, il est important de connaitre la notion de réécriture de l'historique : https://git-scm.com/book/fr/v1/Utilitaires-Git-R%C3%A9%C3%A9crire-l-historique
* Pour permettre de paralléliser les développements et de ne pas créer de conflits entre chaque développeur, il est important de créer une branche pour chaque "fonctionnalité", de préférence en suivant le modèle GitFlow.
* Lorsqu'une branche de fonctionnalité est validée, elle peut être fusionné avec le tronc principal qui représente la "production"

## Outil de déploiement
* Les scripts ou les outils de déploiement sont très utiles dès le début du projet. Même si le coût de mise en place peut être important, il est souvent amorti très vite lors que des déploiements successifs sont demandés.

## Environnement de déploiement
* En fonction des projets, le nombre d'environnement de déploiement varie. Les plus connues sont Intégration, Préproduction et Production. Quelques fois, il est possible de voir : User Acceptance Testing(UAT), Développement.
* Plus les environnement de déploiement sont proches de la production, moins d'incompatibilité peuvent exister.

## Serveur de production
* Vérifier que les fichiers inutiles comme angular.json, package.json, composer.json, README.md, LICENSE, .gitignore n'existe pas en production.
