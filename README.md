# Neural-CNC

**Interface IA pour usinage CNC** — Projet Tailwind CSS v4 + PostCSS

Interface moderne et professionnelle pour le pilotage d'une machine CNC assistée par intelligence artificielle (réseau neuronal pour optimisation de parcours, détection d'usure, etc.).

## Fonctionnalités principales

- **Top Bar** : Navigation par onglets, statut de connexion machine, profil utilisateur
- **Sidebar** : Navigation principale + panneau d'état machine en temps réel (positions X/Y/Z, vitesse)
- **Dashboard** : KPIs (pièces usinées, temps, précision IA, économies), usinages récents, insights IA
- **Éditeur G-Code** : Édition manuelle + aperçu visuel SVG du parcours
- **Optimiseur IA** : Prompt en langage naturel → optimisation neurale (simulation) avec gains quantifiés
- **Moniteur Live** : Visualisation temps réel sur canvas animé + métriques + logs IA

## Lancement rapide

Ouvre simplement `index.html` dans ton navigateur (Tailwind via CDN).

Pour le build CSS (optionnel) :

```bash
npm install
npm run build:css
# ou en watch
npm run watch:css
```

Le fichier `index.html` utilise le CDN Tailwind pour un prototypage rapide et autonome.

## Stack
- Tailwind CSS v4
- PostCSS
- Vanilla JS (interactivité)
- Font Awesome icons

Projet en cours de développement. Prochaines étapes : intégration WebSocket pour vraie machine, Three.js pour vue 3D, export G-Code optimisé.

Créé avec ❤️ pour l'usinage de précision assisté par IA.