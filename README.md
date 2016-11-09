WSColiPosteLetterService Client Library
=======================================

![Logo](http://www.weled.fr/logo/logo-colissimo.svg)

## Congrats
This library is a fork of lexik/ws-colissimo. Thank's Nicolas Cabot

## Introduction

This library provides a client for the SOAP 
[WSColiPosteLetterService](https://www.coliposte.fr/pro/docs/docutheque/divers/socolissimo/integrationwsshipping.pdf).

Access to the WSColiPosteLetterService must be contracted with "La Poste" beforehand or 
it will simply not work. Also, note that currently only the production mode is working.

Nb: The structure of this library is based on 
[PHPForce Soap Client](https://github.com/phpforce/soap-client).

## Installation - using composer

Add the library to your `composer.json` :

```
{
    "require": {
        "NyKo24/ws-colissimo": "dev-master"
    },
    "repositories": [
        {
            "type": "vcs",
            "url":  "git@github.com:NyKo24/ws-colissimo.git"
        }
    ]
}
```
Install it by running the command :

```
php composer.phar update NyKo24/ws-colissimo
```

## Usage

### Standalone

```
# see example in sample/index.php
```
