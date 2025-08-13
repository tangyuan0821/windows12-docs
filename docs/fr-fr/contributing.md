---
title: Guide de Contribution
layout: default
parent: Français
nav_order: 1
lang: fr-fr
permalink: /fr-fr/contributing
---

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---
# Guide de Contribution

Merci à tous les développeurs qui ont contribué à ce projet et à tous pour votre soutien !

Si vous aimez ce projet, n'hésitez pas à donner une Star à ce projet, nous sponsoriser ou faire des contributions importantes qwq~

Veuillez ne pas soumettre de PR sans signification~ Ici nous critiquons spécifiquement :
<img width="673" alt="image" src="https://github.com/tjy-gitnub/win12/assets/121747915/2da6f2d8-369a-4ef7-a87e-7ac4ecacd78b">

## Rapport de Bugs

1. Veuillez utiliser la dernière version pour confirmer si le bug a été corrigé.

2. Veuillez confirmer si le bug ou l'erreur appartient aux problèmes que vous utilisez. Par exemple, utiliser des navigateurs plus anciens (comme IE, etc.), désactiver certaines fonctionnalités du navigateur (comme interdire le stockage de données, etc.)

3. Veuillez décrire clairement le bug afin que nous puissions mieux le corriger.

4. Vous pouvez utiliser le modèle d'Issue "Rapport de Bug" pour les commentaires, mais veuillez remplir correctement le contenu.

5. Il est interdit d'ajouter tout contenu qui viole les lois ou est politiquement sensible, sinon il sera verrouillé + banni selon la situation.

## Faire des Suggestions

1. Veuillez utiliser la dernière version pour confirmer si la suggestion a été implémentée/résolue.

2. Veuillez décrire clairement la suggestion afin que nous puissions mieux l'implémenter/la résoudre.

3. Vous pouvez utiliser le modèle d'Issue "Faire une Suggestion" pour les commentaires, mais veuillez remplir correctement le contenu.

4. Il est interdit d'ajouter tout contenu qui viole les lois ou est politiquement sensible, sinon il sera verrouillé + banni selon la situation.

## Soumission de Code

Note : Veuillez strictement suivre les spécifications de développement ci-dessous et au début de desktop.html pour éditer le code, sinon il ne sera pas fusionné

1. Veuillez essayer de commettre tout le contenu en un seul Commit. Vous pouvez ajouter des Commits, mais essayez de ne pas dépasser 5 Commits.

2. Veuillez essayer d'utiliser la ligne de commande Git, Github Desktop, [https://github.dev](https://github.dev/tjy-gitnub/win12) et d'autres méthodes pour la soumission. Veuillez ne pas télécharger des fichiers directement dans le navigateur pour la soumission.

3. Il est interdit de télécharger tout contenu qui viole les lois ou est politiquement sensible, sinon il sera verrouillé + banni selon la situation (Conseil : les actualités sont également interdites).

4. Veuillez ne pas choisir au hasard les titres et le contenu de soumission lors de la soumission, par exemple :

   - Bons exemples : Corriger le problème que xx ne peut pas être utilisé normalement, ajouter l'application xx
  
   - Mauvais exemples : Ababa, j'ai oublié de faire cette chose, trop de bugs...qwq

5. Exigences de formatage :

   - Veuillez ne pas utiliser d'outils de formatage pour formater les fichiers HTML

   - Pour les fichiers JavaScript et CSS, vous pouvez utiliser l'outil de formatage fourni avec Visual Studio Code

### Exigences des Messages de Commit

   1. Si la mise à jour a une certaine importance ou ampleur, veuillez suivre le format suivant :

      ```
      v11.4.5 - Mis à jour xxx

      (Mise à jour de @Somebody)
      - Mis à jour...
      - Optimisé...
      - Corrigé...
      ...
      ```

      - Exigences pour utiliser ce format :

         1. Cette mise à jour doit nous être notifiée avant la soumission.

      - Description :

         1. Le titre doit inclure le numéro de version et le contenu principal de la mise à jour.

         2. La première ligne du contenu doit indiquer la source de la mise à jour.

         3. Le contenu doit utiliser un format de liste pour décrire le contenu de la mise à jour.

      - Note :

         1. Veuillez ne pas sélectionner arbitrairement les numéros de version. Si vous n'êtes pas sûr, vous pouvez nous contacter via notre groupe de communication (<https://teams.live.com/l/invite/FEA0yrNkE_bAn-ddwI>) et obtenir un numéro de version assigné.

         2. Lors de la mise à jour, n'oubliez pas d'ajouter du contenu pertinent sur la mise à jour dans le journal de mise à jour de l'application "À propos de Windows 12 Version Web".

   2. Si les conditions suivantes sont remplies, le contenu de soumission n'est pas soumis à des réglementations trop strictes :

      - Moins de contenu de mise à jour.

      - Le contenu de mise à jour n'a pas de changements importants.

      Bien qu'il n'y ait pas de réglementations standard, il est toujours nécessaire :

         1. Le titre de soumission doit être clair et concis, et peut résumer brièvement le contenu principal de la mise à jour.

         2. Le contenu de soumission doit indiquer le soumetteur et décrire le contenu de cette mise à jour sous forme de liste ou d'une autre manière.

### Spécifications de Développement

1. Réglementations pour les fichiers HTML

   Voir les spécifications de code au début de `desktop.html`, assurez-vous de lire attentivement.

2. Réglementations pour les fichiers JS

   1. Veuillez développer selon le style de code suivant :

   ```js
      var sum = 0;
      for (var i = 0; i < 10; i++) {
         sum += i;
      }
      console.log(sum);
   ```

   2. Pour les noms de fonctions et la dénomination des variables, veuillez utiliser la dénomination camelCase, comme :

      - isLoaded

      - storagedItems

   3. Pour les noms de classes, veuillez utiliser PascalCase (UpperCamelCase), comme :

      - WindowManager

      - Widgets

   4. Réglementations pour les spécifications de code :

      1. Pour les codes qui n'ont pas besoin d'être développés, essayez de les compresser en une ligne
