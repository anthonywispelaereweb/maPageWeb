
# Task Runner

### Par Wispelaere Anthony Développeur Front-end

[![N|Moi](http://image.noelshack.com/fichiers/2020/06/3/1580935925-photopresentation1.png)](https://wispelaere.fr/)

## Pré-requis pour l'utilisation du task runner

Installation de [node.js](https://nodejs.org/en/download/).

Utilisation d'une console [terminal git](https://gitforwindows.org/), [iTerm2](https://www.iterm2.com/), ou autre...

Bienvenu, quelques explications :

- plusieurs fichiers et un dossier principal

> fichier .gitignore : il sert à dire a votre système de repositorie (gitlab, github,...) d'ingnorer les fichiers ou dossiers cités.

> fichier gulpfile.js : il servira à configurer l'exécution des tâches répétitives.

> fichier package.json ; il servira à installer l'ensemble du projet dans son environnement
  
### Installation

Une fois le dossier clonné :

```sh

$ git clone https://gitlab.com/anthonyWisp/taskRunner.git

$ cd taskRunner

```

Plus qu'a installer :

```sh

$ npm install

```

Puis utiliser :


```sh

$ gulp build

```


```sh

$ gulp

```
