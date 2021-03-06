Studienführer Mathematik
========================

Dieses Projekt soll es Universitäten ermöglichen, ihre Mathematik-Fakultäten
und -Studiengänge in einer vergleichbaren Weise zu präsentieren.

Natürlich ist es theoretisch auch für nicht-mathematische Studiengänge nutzbar.

Installation
------------

Benötigt wird eine MySQL-Datenbank, deren Zugangsdaten in der Datei
`config.php` hinterlegt werden (ein Beispiel ist in `config.sample.php` zu
finden). Außerdem wird die in `empty.sql.gz` gespeicherte Datenbankstruktur
erwartet.

Ferner werden die Frameworks [Slim], [Idiorm, Paris] und [Twig]
benötigt, die sich am einfachsten mit dem PHP-Paketmanager Composer
installieren lassen:

```bash
curl -s https://getcomposer.org/installer | php
php composer.phar install
```

[Slim]: http://slimframework.com/
[Idiorm, Paris]: http://j4mie.github.io/idiormandparis/
[Twig]: http://twig.sensiolabs.org/
