# Github scraper

Was unbedingt nötig ist an Dateien für die Github Pages sind eigentlich nur Beiträge im _posts Unterordner, Format <YYY-MM-DD-Titel.md>. Wobei das natürlich vom theme abhängt.
Wer die landing page verändern will, sollte die index.html aus dem Wurzelverzeichnis des themes kopieren, das _layouts Verzeichnis könnte auch interessant sein.
Mathjax habe ich erstmal hinten an gestellt, die Beispiele im Internet haben nicht funktioniert.

Dafür gibt es ein neues Projekt: DIVI. Es benutzt Github Actions, um etwas zu bewerkstelligen, das sich [git scraping](https://simonwillison.net/2020/Oct/9/git-scraping/) nennt.
Momentan lädt es nur einmal am Tag die aktuellen Daten des [Deutschen Intensivregisters](www.divi.de) runter und hängt diese an eine CSV-Datei an.
Leider gibt es diese Daten nur als Tagesdaten, und die Joomla-Verzeichnisstruktur macht das Herausfinden der URL einer spezielle Datei nur anhand des Datums
schwierig bis unmöglich. Vielleicht bringe ich irgendwann einmal eine Auswertung dieser Daten hier in den blog.
