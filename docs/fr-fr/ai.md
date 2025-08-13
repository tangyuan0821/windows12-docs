---
title: Introduction du Backend AI Copilot
layout: default
parent: Français
nav_order: 2
lang: fr-fr
permalink: /fr-fr/ai
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
Cette IA et cette documentation proviennent de github@NB-Group
# Introduction du Backend AI Copilot
## Introduction
AI Copilot est un outil de génération de texte basé sur l'IA qui utilise le modèle LLAMA et peut générer automatiquement du contenu textuel.
Cette IA est déployée sur le service Worker AI fourni par la plateforme Cloudflare, qui peut recevoir des requêtes des pages frontend et retourner le texte généré.

Cependant, le service IA actuellement déployé par Cloudflare est soumis à des restrictions et ne peut pas être accédé directement, donc un VPN est requis pour y accéder.
J'ai déployé un programme de redirection sur pythonanywhere pour rediriger les requêtes vers Cloudflare.

Le code spécifique pour le serveur IA Cloudflare peut être consulté [ici](https://github.com/tjy-gitnub/win12/blob/main/scripts/AI%20Copilot%20service/Cloudflare%20AI.js)
