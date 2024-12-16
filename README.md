# lab-debuger-php
## 1. Vérifier la compatibilité de Xdebug avec votre version de PHP

### Ouvrir un terminal ou un fichier PHP :
####  phpinfo();

### Modifiez votre fichier php.ini pour inclure Xdebug 
zend_extension="C:\path\to\php_xdebug.dll"
xdebug.mode=debug
xdebug.start_with_request=yes
xdebug.client_host=127.0.0.1
xdebug.client_port=9003

