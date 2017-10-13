# Installation de l'environnement de travail

Nous allons commencer par installer l'environnement de travail qui servira à la fois à la partie front et à la partie back.


### Installation de NodeJS, Cordova & Ionic

* NodeJS : [https://nodejs.org/en/](https://nodejs.org/en/) Il suffit de télécharger et installer le package correspondant à votre OS / machine pour que ça fonctionne. ne vous inquiétez pas trop de la version précise ça ne change pas grand chose.
* Cordova & Ionic : il suffit de lancer un terminal / console et de lancez la commande `npm install -g cordova ionic`.


### Git & Github

Comme vu lors du cours d'introduction, Git sera utilisé en permanence pour **versionner** le code et **collaborer**. Cela servira aussi à vos coachs pour vous aider et vous débloquer par moment. Il est donc indispensable de commencer par ça.

Nous utiliserons **GitHub** comme serveur de Git en profitant de l'offre gratuite pour les comptes open sources.

Vous pouvez donc dès maintenant :

* Vous créer un compte sur Github
* Installer un client git si vous n'en avez pas déjà un (si vous êtes passés par railsinstaller pour Windows ça devrait être bon), par exemple celui proposé par GitHub pour [**Windows**](http://windows.github.com/) ou [**Mac**](http://mac.github.com/)
* Vous pourrez ensuite créer une __organization__ sur Github qui correspondra à votre groupe (__Workshop-Polytechnique__ dans cet exemple).

Bien qu'il existe des interfaces graphiques pour Git, nous vous conseillons d'utiliser git en ligne de commande afin de bien comprendre comment ça marche (utilisez donc git shell ou bash sous windows).
Allez maintenant faire un tour sur cette petite application interactive pour vous former à Git & Github : [http://try.github.io](http://try.github.io)

### Editeur de code

Il vous faudra un IDE ou éditeur de code tout au long de ce cours. Le plus simple sera le mieux, vous pouvez par exemple utiliser [**Sublime Text 3**](http://www.sublimetext.com/3).

### Avant de commencer

Ouvrez un Terminal / une console, et pour tester que tout est installé vous pouvez réaliser ces petits tests (il ne faut pas taper le `$`, cela correspond à ce qu'on appelle le `prompt` et il peut varier en fonction de votre installation).

    $ git --version
    git version 1.9.3 (Apple Git-50)
    $ node --version
    v5.1.1
    $ npm --version
    3.10.6
    $ cordova --version
    6.2.0
    $ ionic --version
    2.0.0
    

Le test est validé si à chaque fois un numéro de version s'affiche (même si il n'est pas identique à celui présenté ici) et échoue si vous voyez une réponse du type `command not found`. Si c'est le cas assurez vous que vous n'avez pas oublié une des étapes décrites ci-dessus.

### Les proxys de l'X

NB : N'étant pas dans vos kazerts, cette partie est expérimentale. Tout retour de votre part sur ces commandes sera grandement appréciée

Pour Git, si vous êtes à l'X vous devez :

	$ git config --global http.proxy http://kuzh.polytechnique.fr:8080
	$ git config --global https.proxy http://kuzh.polytechnique.fr:8080
	
Pour les retirer (en dehors de l'X) :

	$ git config --global --unset http.proxy
	$ git config --global --unset https.proxy
  
### Hello World

Pour commencer à tester votre environnement et vérifier que tout fonctionne, il va falloir lancer un *Hello World*
Pour ça, nous vous demandons de réaliser [ce mini tutoriel](https://medium.com/@adnanrahic/hello-world-app-with-node-js-and-express-c1eb7cfa8a30)


