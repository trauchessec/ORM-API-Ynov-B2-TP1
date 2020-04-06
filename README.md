# ORM-API-Ynov-B2-TP1

## Questions :

1. Quel est l'intérêt de créer une API plutôt qu'une application classique ?
* L’avantage de crée une API plutôt qu’une application classique est qu’elle peut évoluer facilement, elle facilite le développement des applications. Elle permet à des développeurs externes de s'intégrer proprement et rapidement.

2. Résumez les étapes du mécanisme de sérialisation implémenté dans Symfony
*

3. Qu'est-ce qu'un groupe de sérialisation ? A quoi sert-il ?*
*

4. Quelle est la différence entre la méthode PUT et la méthode PATCH ?
* La méthode PUT est le plus souvent utilisé pour les capacités de mise à jour, vers une URI de ressource. Alors que la méthode PATCH soumet une modification partielle à une ressource, par exemple si on doit uniquement mettre à jour un champ pour la ressource..

5. Quels sont les différents types de relation entre entités pouvant être mis en place avec Doctrine ?
* Il y a 3 types de relation qui permet de lier des entités entre elles : OneToOne, ManyToOne et ManyToMany.
  * OneToOne correspond à une relation unique entre deux objets (1.1)
  * ManyToOne correspond à une relation qui permet à une entité d’avoir une relation avec plusieurs entités (n.1)
  * ManyToMany correspond à une relation qui permet à plein d'objets d'être en relation avec plein d'autres objets (n.n)

6. Qu'est-ce qu'un `Trait` en PHP et à quoi peut-il servir ?
*
