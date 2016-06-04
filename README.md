# About

This is a very basic setup using the minimalistic silex framework and twig as rendering engine to help you kickstart your storyblok projects.

## Setup

Be sure to change privateToken and spaceId in webapp/bootstrap.php

## One Click deploy with heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Install composer packages

```
php -r "readfile('https://getcomposer.org/installer');" | php
sudo mkdir /usr/local/bin/
sudo mv composer.phar /usr/local/bin/composer

composer install
```

## Install npm packages

```
npm install
```

## Start the server

```
gulp
```