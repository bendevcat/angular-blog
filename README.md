# Angular Blog - OC Project [DEPRECATED]

[OpenClassrooms exercise link](https://openclassrooms.com/fr/courses/4668271-developpez-des-applications-web-avec-angular/exercises/2353)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.2.

## Instructions (fr)

Vous allez créer une application simple de type blog.  Cette application va afficher les posts du blog, et chaque post aura un bouton permettant de "love it" ou de "don't love it".  Chaque post aura la forme suivante : 

```
post: {
  title: string,
  content: string,
  loveIts: number,
  created_at: Date
} 
```
Quand un post a plus de "love it" que de "don't love it" (loveIts > 0), il sera coloré en vert, et inversement quand loveIts < 0, il sera coloré en rouge.

Information : je vous conseille d'utiliser Bootstrap pour cet exercice.  Si vous créez des list-group-item dans un list-group, vous avez les classes list-group-item-success et list-group-item-danger pour colorer les item.

En termes de structure :

* votre AppComponent contiendra l'array des posts, et il le passera à un component PostListComponent
* votre PostListComponent affichera un PostListItemComponent pour chaque post dans l'array qu'il a reçu
* chaque PostListItemComponent affichera le titre, le contenu et la date de création du post dans le template
* les PostListItemComponent auront des boutons qui permettent d'augmenter et de diminuer le nombre de loveIts — cette modification aura uniquement un effet sur le component, et n'a pas besoin d'être remontée au component parent

## Livrables

Le code complet et fonctionnel doit être déposé dans un dépôt Git en ligne que les validateurs doivent pouvoir cloner. Vous fournirez le lien vers le dépôt. Le projet doit être fonctionnel une fois que le projet a été cloné et que la commande npm install a été saisie à la racine.
