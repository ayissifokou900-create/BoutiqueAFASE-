Cahier Boutique
Application web gratuite pour les petits commerces : suivi des ventes, des dettes clients et envoi de reçus et de rappels par WhatsApp. Elle s'installe sur le téléphone comme une vraie application et fonctionne sans connexion internet.
Lien de l'application : à compléter (exemple : https://mon-site.pages.dev)
Fonctions
Dettes clients : liste des clients qui doivent de l'argent, avec le total des dettes.
Anciennes dettes : recopier d'un coup le cahier papier.
Encaissement : paiements en espèces, MTN MoMo ou Orange Money.
Relances WhatsApp : message de rappel prêt à envoyer.
Ventes : vente détaillée, ou simple « total de la journée » en quelques secondes.
Reçus WhatsApp : reçu envoyé au client après chaque vente.
Stock (facultatif) : suivi des articles les plus importants, avec alerte de stock bas.
Sauvegarde et restauration : export des données dans un fichier.
Installer sur un téléphone
Ouvrir le lien dans Chrome (Safari sur iPhone), pas dans WhatsApp.
Android : menu ⋮, puis « Installer l'application ».
iPhone : bouton Partager, puis « Sur l'écran d'accueil ».
Ouvrir l'application une première fois avec internet.
Données et vie privée
Toutes les données restent sur le téléphone de l'utilisateur (stockage local du navigateur). Aucun compte n'est nécessaire et rien n'est envoyé à un serveur.
Pense à utiliser le bouton Sauvegarder mes données (onglet Historique) régulièrement.
Fichiers du projet
Fichier
Rôle
index.html
L'application complète
manifest.webmanifest
Informations d'installation (nom, icônes, couleurs)
sw.js
Fonctionnement hors connexion
icon-192.png, icon-512.png
Icônes de l'application
Mettre en ligne
L'application est un site statique : il suffit d'envoyer les fichiers sur un hébergeur gratuit comme GitHub Pages ou Cloudflare Pages. Pour mettre à jour, remplacer les fichiers au même endroit : les utilisateurs reçoivent la nouvelle version en ouvrant l'application avec internet.
