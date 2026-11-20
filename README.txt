GARDE 360 - Version 1

CONTENU
index.html : interface
app.js : logique locale
manifest.webmanifest : installation PWA
sw.js : cache hors connexion
icon.svg : icône

MISE EN LIGNE
Déposer ces 5 fichiers ensemble à la racine d'un site HTTPS statique (GitHub Pages, Netlify, etc.).
Ouvrir l'URL sur iPhone dans Safari > Partager > Sur l'écran d'accueil.
L'ouverture directe de index.html depuis l'application Fichiers ne suffit pas pour installer la PWA.

DONNEES
Sauvegardées uniquement dans localStorage du navigateur. Export JSON conseillé régulièrement.
Le fichier ICS permet un import ponctuel, pas une synchronisation iCloud automatique.
Les heures supplémentaires automatiques représentent une estimation du dépassement du quota annuel.
Le solde de récupération ne doit pas être utilisé comme relevé administratif officiel.

LIMITES V1
Pas de compte en ligne, pas de synchronisation multi-appareils, pas de notifications push.
Le format ICS peut comporter des règles de récurrence complexes ou des fuseaux horaires que cet import simplifié ne développe pas.
