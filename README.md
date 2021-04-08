# Stromzaehler
============

[![PHP Linting](https://github.com/dewomser/stromzaehler/actions/workflows/php-linter.yml/badge.svg)](https://github.com/dewomser/stromzaehler/actions/workflows/php-linter.yml) | 
[![Build Arduino examples](https://github.com/dewomser/stromzaehler/actions/workflows/arduino-build.yml/badge.svg)](https://github.com/dewomser/stromzaehler/actions/workflows/arduino-build.yml)
Arduino Stromzähler mit S0 Impuls mit Visualisierung

besteht aus 3 Teilen:

1. Arduino script (Arduino Mega+Ethernet shield)
2. Cronjob holt die Daten und schafft sie auf die Webseite
3. PHP-Script  Datenbankverwaltung und Visualisierung


Beispiel für stromtabelle1.php PHP7 +MYSQLI
https://www.untergang.de/index.php/linux-blog/verbrauchstabelle-erzeugen-mit-php.html

Bonus :
Strom-anzeige-smarpt.py zeigt den aktuellen Stromverbrauch als Zahl an. Für kleine Displays zB beim SmaRPt.  (Raspberry Pi)



Veraltet:
Beispiel für grafisch_tabelle.php PHP4 +MYSQL
http://bis18092014.untergang.de/index0a73.html

