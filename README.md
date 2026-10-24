# AlgoLab

**🇬🇧 English | [🇫🇷 Français](#-français)**

A local, serverless web app to write, run and visualize algorithms in French pseudo-code. It is a single HTML file: no installation and no server.

🔗 **Live demo:** https://YOUR-USERNAME.github.io/algolab/

Made by **EL HASSAK IMAD**.

## Features

- **Pseudo-code structure:** `Algorithme` → `Constante` → `Variable` → `Debut` → `Fin`
- **Types:** `entier`, `reel`, `chaine`, `caractere`, `booleen`, `table` (1D and 2D)
- **Instructions:** assignment (`<-`), `ecrire`, `ecrireln`, `lire`, `si / sinon si / sinon / finsi`, `tantque`, `pour … pas`, `repeter … jusqua`
- **Syntax highlighting** with a distinct color per syntax category
- **Hover tooltips** with a description and an example for each keyword, type, function and operator
- **Autocomplete** for keywords and declared variables, with full block templates (`si`, `pour`, `tantque`…)
- **Auto-closing** of `(`, `[`, `"` and `'`; typing `ecrire(` gives `ecrire("")`
- **Step-by-step visualization:** current line highlighted, variables as cards, tables as cells with bars, changed values highlighted
- **Themes:** Night, Light, Dracula
- **Built-in documentation** with examples (Documentation button)
- **Clear error messages** with line numbers, and protection against infinite loops
- **Export / import** of `.alg` files, plus automatic saving in the browser

## Quick start

1. Open `index.html` in your browser (double-click), or use the live demo link.
2. Write your algorithm, or load an example.
3. Click **▶ Execute** (`Ctrl+Enter`) to run it, or **Visualize** to follow it step by step.

## Example

```
Algorithme Palindrome
Variable
  mot, inverse : chaine
  i : entier
Debut
  ecrire("Saisir un mot : ")
  lire(mot)
  inverse <- ""
  pour i de longueur(mot) a 1 pas -1 faire
    inverse <- inverse + mot[i]
  finpour
  ecrireln("Inverse : ", inverse)
  si mot = inverse alors
    ecrireln("Palindrome")
  sinon
    ecrireln("Non palindrome")
  finsi
Fin
```

## Notes

- Indexes of tables and strings start at 1 (`mot[1]` is the first letter). A single character of a string can be read but not modified.
- Variable names are case-sensitive.
- `selon … cas`, procedures and functions are not supported yet.
- Algorithms are saved in your own browser (local storage).

## Deploy for free (GitHub Pages)

Rename the file to `index.html`, upload it to a public repository, then go to **Settings → Pages**, choose branch `main` and folder `/ (root)`, and save.

## Author

**EL HASSAK IMAD**

---

# 🇫🇷 Français

Une application web locale, sans serveur, pour écrire, exécuter et visualiser des algorithmes en pseudo-code français. Elle tient dans un seul fichier HTML : aucune installation, aucun serveur.

🔗 **Démo en ligne :** https://YOUR-USERNAME.github.io/algolab/

Réalisée par **EL HASSAK IMAD**.

## Fonctionnalités

- **Structure du pseudo-code :** `Algorithme` → `Constante` → `Variable` → `Debut` → `Fin`
- **Types :** `entier`, `reel`, `chaine`, `caractere`, `booleen`, `table` (1 ou 2 dimensions)
- **Instructions :** affectation (`<-`), `ecrire`, `ecrireln`, `lire`, `si / sinon si / sinon / finsi`, `tantque`, `pour … pas`, `repeter … jusqua`
- **Coloration syntaxique** avec une couleur propre à chaque catégorie
- **Infobulles au survol** : description et exemple pour chaque mot-clé, type, fonction et opérateur
- **Autocomplétion** des mots-clés et des variables déclarées, avec des structures complètes (`si`, `pour`, `tantque`…)
- **Fermeture automatique** de `(`, `[`, `"` et `'` ; taper `ecrire(` donne `ecrire("")`
- **Visualisation pas à pas :** ligne en cours surlignée, variables en cartes, tables en cellules avec barres, valeurs modifiées mises en évidence
- **Thèmes :** Nuit, Clair, Dracula
- **Documentation intégrée** avec exemples (bouton Documentation)
- **Messages d'erreur clairs** avec numéro de ligne, et protection contre les boucles infinies
- **Export / import** de fichiers `.alg`, et sauvegarde automatique dans le navigateur

## Démarrage rapide

1. Ouvre `index.html` dans ton navigateur (double-clic), ou utilise le lien de la démo.
2. Écris ton algorithme, ou charge un exemple.
3. Clique sur **▶ Exécuter** (`Ctrl+Entrée`) pour le lancer, ou sur **Visualiser** pour le suivre pas à pas.

## Exemple

```
Algorithme Palindrome
Variable
  mot, inverse : chaine
  i : entier
Debut
  ecrire("Saisir un mot : ")
  lire(mot)
  inverse <- ""
  pour i de longueur(mot) a 1 pas -1 faire
    inverse <- inverse + mot[i]
  finpour
  ecrireln("Inverse : ", inverse)
  si mot = inverse alors
    ecrireln("Palindrome")
  sinon
    ecrireln("Non palindrome")
  finsi
Fin
```

## Remarques

- Les indices des tables et des chaînes commencent à 1 (`mot[1]` est la première lettre). On peut lire un caractère d'une chaîne, mais pas le modifier.
- Les noms de variables sont sensibles à la casse.
- `selon … cas`, les procédures et les fonctions ne sont pas encore pris en charge.
- Les algorithmes sont enregistrés dans ton propre navigateur (stockage local).

## Déploiement gratuit (GitHub Pages)

Renomme le fichier en `index.html`, envoie-le dans un dépôt public, puis va dans **Settings → Pages**, choisis la branche `main` et le dossier `/ (root)`, et enregistre.

## Auteur

**EL HASSAK IMAD**
