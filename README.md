# TimeTravel Agency — Webapp Interactive

Webapp pour une agence de voyage temporel fictive, développée avec HTML/CSS/JS vanilla et IA générative.

## Stack Technique

- HTML5 + CSS3 (animations natives, CSS custom properties)
- Tailwind CSS (CDN)
- Google Fonts — Cormorant Garamond + Inter
- Mistral AI API (chatbot conversationnel)
- Canvas API (particules animées)
- IntersectionObserver (scroll reveal)

## Features Implémentées

- Landing page avec hero animé et particules temporelles
- Galerie de 3 destinations temporelles (Paris 1889, Crétacé −65M, Florence 1504)
- Chatbot IA conversationnel "Chronos" — widget flottant (bas droite)
- Quiz personnalisé de 4 questions pour recommander une destination
- Formulaire de réservation interactif
- Animations au scroll (fade-up reveal)
- Design responsive mobile-first
- Mode démo sans clé API

## Configuration Chatbot Mistral

1. Créez votre clé API sur platform.mistral.ai
2. Ouvrez `index.html`
3. Ligne ~350 : remplacez `const MISTRAL_API_KEY = '';` par votre clé
4. Le chatbot utilise le modèle `mistral-small-latest`

## Intégration des Visuels (Projet 1)

Dans `index.html`, cherchez les 3 commentaires :
```
ZONE VISUEL — PARIS 1889
ZONE VISUEL — CRÉTACÉ
ZONE VISUEL — FLORENCE 1504
```
Remplacez chaque bloc `<div class="dest-placeholder">` par :
```html
<img src="VOTRE_IMAGE.jpg" class="dest-img" alt="Description" loading="lazy" />
```

## Déploiement

**Vercel / Netlify** : glissez-déposez le dossier `timetravel-agency/`  
**GitHub Pages** : poussez sur un repo public, activez Pages sur la branche main

## IA Utilisées

- Chatbot : Mistral Small via API REST
- Code : Claude Sonnet 4.6 (Claude Code)
- Visuels destinations : à intégrer depuis le projet TimeTravel Agency (Midjourney / Runway)

## Crédits

- Fonts : Google Fonts (Cormorant Garamond, Inter)
- CSS utilities : Tailwind CSS (CDN)
- API : Mistral AI

## Licence

Projet pédagogique — M1/M2 Digital & IA
