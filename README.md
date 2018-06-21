# codelunch

Tutorial Rails complet : https://www.railstutorial.org/book

Installation de l'environnement de travail (en local, plutot que Cloud9, afin d'être autonome. mais Cloud9 peut dépanner au début, si besoin) https://www.learnenough.com/dev-environment-tutorial#sec-native_os_setup
- Terminal
- Xcode
- Homebrew
- Rbenv & Ruby (pour savoir si c'est installé : `ruby -v`)
- Rails, avec la commande `sudo gem install rails` (pour savoir si c'est installé : `rails -v`)

Qu'est-ce qu'une "gem" ? C'est un morceau de programme, une "librairie" afin de ne pas réécrire la roue à chaque fois. Rails est une gem de Ruby. Et ensuite, dans la création d'un site web, nous utiliserons de très nombreuses autres gem.

# Intro

Quel langage connaissez-vous ? Ruby, C, Python, Java, PHP, Javascript

HTML langage de programmation ? Non, c'est un langage de mise en page reconnu par les navigateurs. Idem pour CSS

Et "Rails" ? C'est le framework adapté pour faire des sites web (équivalents dans d'autres langages : Laravel en PHP, Django en Python).

# Git
Qu'est-ce Git ? gestion de versions du code, de modifications. Permet le travail en collaboratif

Commandes de base
- `git clone https://github.com/mvaragnat/codelunch.git` pour cloner un repository sur ma machine
- `git status` pour voir ce qui est modifié
- `git add .` pour tout ajouter à la prochaine sauvegarde
- `git commit -m "ceci est le premier commit"` pour sauvegarder
- `git pull` pour récupérer les modifications récentes
- `git push` pour envoyer sur github

# Créer une application Rails. Test de Ruby

Pour créer une application Rails minimale, `rails new test_app`, qui va créer un répertoire et une application nommée "test_app"

Puis `rails c` pour ouvrir la console. Nous arrivons dans un environnement qui "parle" le langage Ruby. On peut tester quelques manipulations de base.

Opérations mathématiques
- 1+2
- 4 * 8

Variables
- a = 3
- b = 2
- c = a + b

# Types de données

A discuter
- Integer
- Float
- String
- Array
- Hash

et les methodes associées...

# Site web
Todo (`rails s` pour les curieux)
