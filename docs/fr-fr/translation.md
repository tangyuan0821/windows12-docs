---
title: Guide de traduction
layout: default
parent: Français
nav_order: 4
lang: fr-fr
permalink: /fr-fr/translate
---

<details close markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---
# Guide de Contribution à la Traduction
Pour le moment, **seul l'anglais est nécessaire**, les autres langues seront abordées une fois le système amélioré.

Avant de commencer la traduction, **veuillez nous contacter et obtenir une approbation**, pour savoir si quelqu'un travaille déjà sur la traduction, afin d'éviter les travaux en double et les conflits de fusion.

## Conditions
1. Connaissances de base en chinois
2. Bonnes connaissances de la langue cible / Volonté de configurer votre système Windows 11 dans la langue cible
3. Compétences de base en programmation

## Méthodes
Le projet utilise la bibliothèque i18n pour mettre en œuvre le support multilingue. Vous pouvez la rechercher en ligne ou étudier les parties déjà traduites.

### Ressources Existantes
0. Il est crucial de comprendre la partie de traitement linguistique au début de `desktop.js` et de se familiariser avec les principes
1. Le `trans.py` dans ce répertoire - ceux avec des connaissances en Python peuvent le rechercher eux-mêmes
2. Dans `desktop.js`, il y a `lang(txt,id)`, voir les commentaires pour plus de détails

### Remarques
Certains codes sont structurés comme ceci :
```html
<a class="btn">
    <i class="bi"></i> Texte
</a>
```
Cela peut rendre difficile la définition d'attributs. Vous pouvez ajouter une balise `<span>` à la partie texte brut, par exemple :

```html
<a class="btn">
    <i class="bi"></i>
    <span data-i18n="sth">Texte</span>
</a>
```

Veuillez également améliorer simultanément le fichier `lang_zh_cn`, ce qui serait grandement apprécié.

### Points Bonus
1. Pour les parties cohérentes avec Windows 11, elles doivent correspondre à la dernière version du contenu en langue native (autant que possible)
2. Pour les parties incohérentes, la traduction automatique doit être évitée

## Contenu à Traduire
1. Diverses pages des Paramètres à l'exception de "Personnalisation"
2. Gestionnaire de tâches
3. Parties du code JavaScript, telles que les menus contextuels, les menus déroulants et les notifications
4. L'attribut win12_title des éléments en HTML

## Rémunération
Comprend uniquement :
1. Points de contribution GitHub
2. Remerciements sincères des développeurs >u-)o
