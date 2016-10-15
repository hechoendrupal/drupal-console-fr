# drupal-console-fr
DrupalConsole French Language / en Français

# Version Française

## Usage

Le projet Drupal Console est installé pour chaque site sous Drupal 8 avec la langue anglaise par défaut

Pour installer le package Drupal Console en langue française exécutez les instructions suivantes

```
$ composer require drupal/console-fr
```

### Install Drupal Console

Pour installer la version appropriée du projet Drupal Console dans votre installation drupal, exécutez la commande composer suivante

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Installer le lanceur Drupal Console 

Pour éviter les conflits d'une version à l'autre de Drupal et avoir une version de Drupal Console entre les versions majeures et mineures de Drupal, afin de faciliter le chargement des commandes Drupal Console disponibles pour chacune, un lanceur Drupal Console a été créé. 

En suivant les instructions ci-dessous vous pouvez installer l'application globale pour le lanceur Drupal Console.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Ou 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribuer

Si voulez contribuer à cette traduction, vous devez suivre ces étapes

- Faire un fork de ce répertoire en suivant ce lien [https://github.com/hechoendrupal/drupal-console-fr#fork-destination-box](https://github.com/hechoendrupal/drupal-console-fr#fork-destination-box)
- Cloner le répertoire du fork sur votre machine en local
- Configurer le upstream

Afin d'être à jour avec d'autres contributions vous devez configurer une connexion avec le répertoire principal en utilisant les commandes git suivantes

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fr.git
```

Pour récupérer la dernière contribution pour commencer vous devez exécuter les commandes suivantes


```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Poussez vos modifications sur votre répertoire forké afin de créer un PR par jour, pour éviter tout conflit avec d'autres contributeurs.

# English Version

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To installe Drupal Console package for French language run the following instructions

```
$ composer require drupal/console-fr
```

### Install Drupal Console

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal, in order to faciliate to load the Drupal Console commands available to each
Drupal 8 website, a Drupal Console launcher was created.
 
Following the instruction below you could install the global application for Drupal Console launcher. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps

- Fork this repository following this link [https://github.com/hechoendrupal/drupal-console-fr#fork-destination-box](https://github.com/hechoendrupal/drupal-console-fr#fork-destination-box)
- Clone your repostory forked in your local machine.
- Set up upstream

In order to be updated with other contribution you must to setup a connected with main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fr.git
```

To fetch the latest contribution before to star you must to run the next commands

```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.