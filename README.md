# Security_Project
This is my project for my cybersecurity class. I created with my friend Yasmine a bot that can fav, retweet and follow someone through a specific hashtag ( or hashtags ) depends on how you want it to work using Python. 
L'objectif de notre projet est de créer un BOT permettant de fav, rt et de s'abonner à une personne selon un ou plusieurs hashtags utilisant python.
En plus de cela, il est ainsi capable de :
- Vérifier l'état de la connexion au compte.
- Afficher ses propres tweets avec l'ID du tweet.
- Afficher les tweets qui sont dans mon fil d'actualité "Home".
- Afficher les abonnés du compte avec le nom du user.
Voici les différentes étapes que nous avons suivi afin de réaliser ce BOT.

Step1: Afin d'utiliser les API de Twitter nous devions d'abord créer un compte de developer twitter via https://developer.twitter.com/ .
Step2: Une fois avoir créé notre compte twitter et twitter developer, nous avons premièrement créer notre projet de BOT, activer OAuth 1.0a et modifier les permissions en "Read and write and access Direct Messages" (Sans cette autorisation, le bot ne pourra pas agir et aura uniquement la lecture des tweets)
Step3: Création des clés, et du fichiers credentials qui contenait nos clés et permettait donc notre authentification.
Le projet se consitute de 3 fichiers : 
le premier permet d'injecter les clés d'authentification au compte.
le deuxième permet de définir les hashtags, le follow et like du tweet.
le troisième représente le script à exécuter contenant toutes les commandes nécessaires.

Remarque : Nous avons choisi le mot sécurité mais il est tout à fait possible de changer ce mot, ou d'en ajouter plusieurs en modifiant la ligne contentant QUERY dans le fichier config.py par exemple comme suit : QUERY= ('#cybersecurity OR #hackers OR  #kalilinux') le programme exécutera cela selon donc plusieurs hashtags.

