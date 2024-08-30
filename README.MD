#MyFirstSymfony

## Installation

```bash

symfony new MyfirstSymfony
cd MyfirstSymfony
```

### installation de `maker`

```
bash
composer require --dev symfony/maker-bundle
``` 


pour voir ce que l'on peut faire dans la console

```bash
symfony console
php bin/console
```
pour voir les actions possibles de maker : 

```bash
php bin/console make:
```
 ###création d'un controller

```bash
php bin/console make:controller First
```
Le nom dois être en pascale case