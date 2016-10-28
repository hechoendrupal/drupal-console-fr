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

Check instructions at [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
