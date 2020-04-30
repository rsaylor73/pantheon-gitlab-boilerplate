# Project Setup

This is a boilerplate repo for building Drupal 8 websites with Gitlab CI and Pantheon.

_**Note:** This project is a fork of https://github.com/pantheon-systems/example-drops-8-composer_


## macOS Catalina

Add the following to ~/.zshrc

export DOCKER_DEV=true

Save and restart the terminal

## Getting started

**Modify the following files**
 - `./.lando.yml`
 - `./drush/sites/example.site.yml`

 ## Setup
 - composer install
 - lando start
 - lando drush si --db-url=mysql://drupal8:drupal8@database/drupal8 -y

## Drupal Command Line
- lando drupal

## Install Drupal Command Line
- composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
