SUIVI BASKET — VERSION PWA FINALE

CONTENU :
- index.html -> ton application originale
- manifest.webmanifest -> installation PWA
- sw.js -> mode hors-ligne (offline)
- icon-192.png
- icon-512.png
- apple-touch-icon.png

DÉPLOIEMENT GITHUB PAGES :
1. Crée un dépôt GitHub
2. Envoie tous ces fichiers à la racine
3. Va dans Settings > Pages
4. Choisis : Deploy from branch
5. Branche : main / root
6. Attends le lien public

INSTALLATION SUR IPHONE :
1. Ouvre le lien dans Safari
2. Partager
3. Ajouter à l’écran d’accueil

IMPORTANT :
- Les données sont stockées en localStorage
- Donc chaque appareil garde ses propres équipes/résultats
- Si tu veux une synchro multi-appareils plus tard, il faudra ajouter une base de données

Cette version garde ton application telle quelle, avec juste :
- PWA installable
- Icônes
- Hors ligne
