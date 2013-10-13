MaquetteZF2
===========

Introduction
------------
This is a simple, skeleton application using the ZF2 MVC layer and module
systems. This application is meant to be used as a starting place to create
ZF2 applications for Lille 1 University.
It is based on the ZendSkeletonApplication from Akrabat and the ZF2 manual.


Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and manually invoke `composer` using the shipped `composer.phar`:

    cd my/project/dir
    git clone https://github.com/mifsud/MaquetteZF2.git
    cd MaquetteZF2/
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)


Virtual Host
------------
Afterwards, set up a virtual host to point to the public/ directory of the
project and you should be ready to go!

Alternatively — if you are using PHP 5.4 or above — you may start the internal PHP cli-server in the public
directory:

    cd public
    php -S 0.0.0.0:8080 index.php

This will start the cli-server on port 8080, and bind it to all network
interfaces.
