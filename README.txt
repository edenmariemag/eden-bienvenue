EDEN — NOTIFICATION AIRDROP POUR GITHUB PAGES

Fichiers :
- index.html : page interactive et boutons de fermeture
- personnage.gif : GIF original animé, extrait de l'archive transmise
- airdrop.png : fond original avec « OK » et « J'accepte »

GitHub Pages :
1. Créez un dépôt PUBLIC « eden-bienvenue » sur github.com.
2. Ajoutez les trois fichiers à la RACINE du dépôt (README facultatif).
3. Settings > Pages > Build and deployment > Deploy from a branch.
4. Choisissez « main » et « / (root) », puis Save.
5. Attendez l'URL https://VOTRE-NOM.github.io/eden-bienvenue/
6. Remplacez l'URL Netlify dans le code Project Code de Readymag.

Le composant envoie EDEN_CLOSE_WELCOME au parent après clic sur OK ou J'accepte.
Le menu Readymag envoie EDEN_OPEN_WELCOME au parent pour ouvrir l'iframe.
Il faut donc conserver le script d'intégration dans Readymag.

Important : pour ne pas bloquer le menu Readymag, limitez la taille de l'iframe
à la notification au lieu de couvrir tout l'écran avec l'iframe interactive.
