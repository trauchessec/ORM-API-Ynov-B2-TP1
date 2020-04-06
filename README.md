# ORM-API-Ynov-B2-TP1

## Questions :

1. Quel est l'intérêt de créer une API plutôt qu'une application classique ?
* L’avantage de crée une API plutôt qu’une application classique est qu’elle peut évoluer facilement, elle facilite le développement des applications. Elle permet à des développeurs externes de s'intégrer proprement et rapidement.

2. Résumez les étapes du mécanisme de sérialisation implémenté dans Symfony
*

3. Qu'est-ce qu'un groupe de sérialisation ? A quoi sert-il ?
*

4. Quelle est la différence entre la méthode PUT et la méthode PATCH ?
* La méthode PUT est le plus souvent utilisé pour les capacités de mise à jour, vers une URI de ressource. Alors que la méthode PATCH soumet une modification partielle à une ressource, par exemple si on doit uniquement mettre à jour un champ pour la ressource..

5. Quels sont les différents types de relation entre entités pouvant être mis en place avec Doctrine ?
* Il y a 3 types de relation qui permet de lier des entités entre elles : OneToOne, OneToMany et ManyToMany.
  * OneToOne (1.1) correspond à une relation unique entre deux objets
  * OneToMany (1.n) correspond à une relation qui permet à une entité d’avoir une relation avec plusieurs entités
  * ManyToMany (n.n) correspond à une relation qui permet à plusieurs d'objets d'être en relation avec plusieurs autres objets

6. Qu'est-ce qu'un `Trait` en PHP et à quoi peut-il servir ?
* Un `Trait` est un peu comme une forme d’héritage, il nous permet de mutualiser des variables et des fonctions pour qu’elles soient réutilisables dans n’importe qu’elle classe.
