# Rapport - Template de Document Professionnel

Ce dépôt contient un template Markdown et CSS optimisé pour la création de rapports académiques ou professionnels au format PDF.

## Prérequis

Pour utiliser ce template et générer des exports PDF de qualité, il est recommandé d'utiliser **Visual Studio Code** avec les extensions suivantes :

1.  **Markdown Preview Enhanced** : Pour visualiser le rendu final.
2.  **Markdown PDF** : Pour exporter le document au format `.pdf`.

## Utilisation

1.  Ouvrez le dossier dans VS Code.
2.  Modifiez le contenu dans le fichier `Template.md`.
3.  Le style est géré automatiquement par le fichier `Style.css`.
4.  **Pour exporter en PDF** :
    *   Ouvrez `Template.md`.
    *   LANCEZ la commande `Markdown PDF: Export (pdf)` via la palette de commandes (`Ctrl+Shift+P` ou `Cmd+Shift+P`).

## Structure du projet

- `Template.md` : Le contenu de votre rapport (Markdown compatible HTML).
- `Style.css` : La feuille de style gérant la mise en page A4, les marges et la typographie.
- `Images/` : Dossier pour vos logos et captures d'écran.

## Personnalisation

Vous pouvez ajuster les variables suivantes dans `Style.css` :
- **Marges** : Dans la règle `@page`.
- **Typographie** : Dans la règle `body` (actuellement fixée à 15px).
- **Espacement** : Ajustez les `margin` des paragraphes `p` et listes `li`.
