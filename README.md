ContaoUpdateMaker
=================

Generiert Update ZIP Datei für [easyupdate3](https://github.com/BugBuster1701/privat-easyupdate3), für Updates innerhalb von Contao 3

Derzeit eine reine Machbarkeitsstudie. 
Die Dateien müssen innerhalb einer Contao 3.0.1 Installation installiert werden im Verzeichnis ```ContaoUpdateMaker``` ausgehend vom Installationsverzeichnis.
Nicht in das Modulverzeichnis !!! (quasi so wie Contao Check, parallel dazu)

Es wird dann per PHP Kommandozeile aufgerufen: ```php -f updatemaker.php```
Im Unterverzeichnis ```updates``` liegt dann eine ZIP: Contao_3.0.0-3.0.1.zip
Hier noch fest kodiert von 3.0.0 nach 3.0.1 (deshalb muss das auch in eine 3.0.1 Installation rein)

Zu löschende Dateien wird als Liste auf dem Bildschirm ausgegeben.

Das Programm prüft so gut wie nichts, also Vorsicht, nur was für Kenner.
Da es nur schnell in 5 Minuten gecodet wurde, macht der Quelltext nicht viel her.
Kommt Zeit - könnte mehr draus werden :-)
