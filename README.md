# Projet de Gestion des Posts

Ce projet est une application React qui permet d'afficher et de rechercher des posts en utilisant une API externe.

## Exercice 1 : État et Effets

### 1.1 Compléter le hook `usePosts`

**Solution** : J'ai créé un hook `usePosts` qui utilise `useState` et `useEffect` pour récupérer les posts depuis l'API dummyjson.com. Le hook gère également l'état de chargement.

!usePosts
Difficultés rencontrées : La principale difficulté était de gérer les erreurs de récupération des données. J'ai résolu cela en ajoutant un bloc try-catch.

1.2 Implémenter le composant PostList
Solution : J'ai créé le composant PostList qui utilise le hook usePosts pour afficher les posts. Le composant affiche un message de chargement pendant la récupération des données.

Difficultés rencontrées : Aucune difficulté majeure rencontrée.

1.3 Ajouter la fonctionnalité de recherche par titre ou contenu dans PostSearch
Solution : J'ai créé le composant PostSearch qui permet de rechercher des posts par titre ou contenu. Le composant filtre les posts en fonction du terme de recherche.

Difficultés rencontrées : La gestion de l'état de recherche et le filtrage des posts étaient un peu complexes. J'ai résolu cela en utilisant useState pour le terme de recherche et en filtrant les posts dans le rendu.

1.4 Documenter votre solution
Solution : J'ai mis à jour le README avec des explications, des captures d'écran, et des descriptions des difficultés rencontrées et des solutions apportées.
