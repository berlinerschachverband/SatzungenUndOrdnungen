# Satzungen Und Ordnungen
Satzungen und Ordnungen des Berliner Schachverbands

# Verwendung
Hier liegen die Skriptdateien für die Dokumente im [TeX](https://de.wikipedia.org/wiki/TeX)-Format. Sie sind menschenlesbar und können kollaborativ bearbeitet werden.
Zum erzeugen einer PDF kann auf einem beliebigen (derzeit Unix-) Computer auf dem Docker installiert ist dieses Repository ausgecheckt und zum Beispiel
```
xelatex.sh turnierordnung.tex
```
ausgeführt werden.
  
Wie bei TeX üblich zwei mal ausführen. 
Der allererste Lauf dauert etwas länger, da das Container-Image, ca. 2GB groß, heruntergeladen werden muss.

Auf einem Windows Computer, auf dem TeX installiert ist, können die .tex Dateien auch "herkömmlich" in PDF übersetzt werden.
Dann ist aber keine komplette Gleichheit zur Docker-Variante sichergestellt.
