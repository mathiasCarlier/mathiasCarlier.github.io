# Portfolio — Mathias Carlier

Site personnel publié avec GitHub Pages : **https://mathiascarlier.github.io**

HTML, CSS et JavaScript, sans framework ni étape de build.

## Fichiers

| Fichier | Rôle |
| --- | --- |
| `index.html` | Tout le contenu : accueil, projets, parcours, compétences, contact |
| `styles.css` | Mise en page, thème clair / sombre, responsive |
| `script.js` | Bouton de thème, menu mobile, animations au défilement |
| `favicon.svg` | Icône de l'onglet |

## Voir le site en local

Ouvrir `index.html` dans le navigateur, ou lancer un petit serveur :

```bash
npx serve .
```

## Modifier le contenu

Tout le texte est dans `index.html`. Pour ajouter un projet, copier un bloc
`<article class="card project">` dans la section `#projets` et l'adapter.
Les couleurs se changent en haut de `styles.css` (variables `--accent`, etc.).

## Mettre en ligne

Le dépôt doit s'appeler exactement `mathiasCarlier.github.io`. Chaque `git push`
sur `main` met le site à jour en une minute environ.
