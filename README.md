# Security_Project
This is my project for my cybersecurity class. I created with my friend Yasmine a bot that can fav, retweet and follow someone through a specific hashtag (or hashtags) depends on how you want it to work using Python. 
The objective of our project is to create a BOT allowing to fav, rt and subscribe to a person according to one or more hashtags using python.
In addition to that, it is able to :
- Check the status of the connection to the account.
- Display its own tweets with the tweet ID.
- Show the tweets that are in my "Home" news feed.
- Show the followers of the account with the name of the user.
Here are the different steps we followed to make this BOT.



L'objectif de notre projet est de créer un BOT permettant de fav, rt et de s'abonner à une personne selon un ou plusieurs hashtags utilisant python.
En plus de cela, il est ainsi capable de :
- Vérifier l'état de la connexion au compte.
- Afficher ses propres tweets avec l'ID du tweet.
- Afficher les tweets qui sont dans mon fil d'actualité "Home".
- Afficher les abonnés du compte avec le nom du user.
Voici les différentes étapes que nous avons suivi afin de réaliser ce BOT.

English steps : 
Step1: In order to use the Twitter API we first had to create a twitter developer account via https://developer.twitter.com/ .
Step2: Once we have created our twitter account and twitter developer, we first create our BOT project, activate OAuth 1.0a and change the permissions to "Read and write and access Direct Messages" (Without this permission, the bot will not be able to act and will only be able to read tweets)
Step3: Re-generation of the keys according to the new permissions given, and of the credentials file which contained our keys and thus allowed our authentication.
The project consists of 3 files: 
the first one allows to inject the authentication keys to the account.
the second one allows to define the hashtags, the follow and like of the tweet.
the third one is the script to execute containing all the necessary commands.

Remark : We have chosen the word cybersecurity but it is possible to change this word, or to add several words by modifying the line containing QUERY in the config.py file for example as follows : QUERY= ('#cybersecurity OR #hackers OR #kalilinux') the program will execute this according to several hashtags.

French Steps :
Step1: Afin d'utiliser les API de Twitter nous devions d'abord créer un compte de developer twitter via https://developer.twitter.com/ .
Step2: Une fois avoir créé notre compte twitter et twitter developer, nous avons premièrement créer notre projet de BOT, activer OAuth 1.0a et modifier les permissions en "Read and write and access Direct Messages" (Sans cette autorisation, le bot ne pourra pas agir et aura uniquement la lecture des tweets)
Step3: Re-génér tion des clés selon les nouvelles permissions données, et du fichiers credentials qui contenait nos clés et permettait donc notre authentification.
Le projet se consitute de 3 fichiers : 
le premier permet d'injecter les clés d'authentification au compte.
le deuxième permet de définir les hashtags, le follow et like du tweet.
le troisième représente le script à exécuter contenant toutes les commandes nécessaires.

Remarque : Nous avons choisi le mot cybersecurity mais il est tout à fait possible de changer ce mot, ou d'en ajouter plusieurs en modifiant la ligne contentant QUERY dans le fichier config.py par exemple comme suit : QUERY= ('#cybersecurity OR #hackers OR  #kalilinux') le programme exécutera cela selon donc plusieurs hashtags.

