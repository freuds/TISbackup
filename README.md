tisbackup
=========

Installation
-----------

Dépendances python:
* Flask
* requests
* pyvmomi
* huey (<= 0.4.9)
* six
* pexpect
* MarkupSafe
* Werkzeug
* itsdangerous
* Jinja2
* Paramiko


Utilisation
-----
Le script tisbackup se base sur un fichier de configuration .ini. [Cf le fichier d'exemple pour le format](https://github.com/tranquilit/TISbackup/blob/master/samples/config.ini.sample)


Pour lancer le backup, lancer la commande

> ./tisbackup.py -c fichierconf.ini 

Pour lancer une section particulière du fichier .ini

> ./tisbackup.py -c fichierconf.ini -s section_choisi

Pour mettre le mode debug

> ./tisbackup.py -c fichierconf.ini -l debug 

Interface web
-----

![alt tag](https://raw.githubusercontent.com/tranquilit/TISbackup/master/static/images/tisbackup-gui-home.png)

Aide
-----
Pour plus d'informations aller voir le site : http://dev.tranquil.it/
