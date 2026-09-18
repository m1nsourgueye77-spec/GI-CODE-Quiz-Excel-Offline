# GI.CODE – Quiz Excel Offline

## Contenu
- index.html : quiz Excel complet
- manifest.json : installation comme application
- sw.js : fonctionnement hors connexion
- icons/ : icônes de l'application

## Utilisation hors connexion
1. Déployer cette version sur HTTPS (par exemple Render).
2. Ouvrir le quiz une première fois avec Internet.
3. Laisser la page se charger complètement.
4. Sur Chrome/Edge : utiliser « Installer l'application » si proposé.
5. Couper Internet et relancer l'application : le quiz reste disponible.

## Important
Le Service Worker ne fonctionne pas en ouvrant simplement index.html avec un double-clic
(file://). Pour le mode PWA hors connexion, il faut d'abord charger l'application depuis
une adresse HTTPS (comme votre site Render) ou utiliser un serveur local.

Les 30 questions et le barème de la version fournie ont été conservés.
