Compte Rendu - TP React Hooks Blog
1. Organisation du projet
Le projet est organisé en deux dossiers principaux sous 'src/':
- components/ : contient le composant principal Blog.jsx.
- hooks/ : contient le hook personnalisé usePosts.js.
Le fichier App.js importe le composant Blog et l'affiche.
2. Hook personnalisé - usePosts.js
Le hook usePosts est responsable de récupérer les posts depuis l'API https://dummyjson.com/posts. Il gère également les états de chargement (loading) et d'erreur (error) via useState et useEffect.
3. Composant principal - Blog.jsx
Le composant Blog utilise usePosts pour récupérer les posts et affiche :
- Un champ de recherche pour filtrer les posts par titre ou contenu.
- Un message de chargement pendant le fetch.
- Un message d'erreur en cas d'échec.
- Une liste des posts filtrés.
4. Ajout de la Pagination
La pagination a été ajoutée pour afficher 10 posts par page.
- L'état currentPage suit la page actuelle.
- Les boutons Précédent/Suivant permettent de naviguer entre les pages.
- La recherche remet la pagination à la page 1.
5. Résultat attendu
- Au lancement, les posts sont affichés par lot de 10.
- La recherche filtre dynamiquement les posts.
- Les boutons Précédent/Suivant permettent de changer de page.
- L'application gère proprement le chargement et les erreurs.
6. Bonus possible
- Amélioration de l'interface utilisateur avec du CSS ou un framework (ex : TailwindCSS).
- Création d'une page de détails pour chaque post.
