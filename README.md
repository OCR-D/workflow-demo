# workflow-demo
[Taverna](https://taverna.incubator.apache.org/) Workflow Beispiel zu Demonstrationszwecken

![Workflow diagram](https://user-images.githubusercontent.com/952378/30741474-3393ee40-9f95-11e7-9718-2ad5781bd0d7.png)

## Anforderungen
Die folgenden Softwarekomponenten sind erforderlich:

* [Java](https://java.com/download)    
Es wird das JRE (Java Runtime Environment) in der Version 7 oder neuer benötigt.
* [Taverna Workbench Core 2.5](http://www.taverna.org.uk/download/workbench/2-5/core/)    
Für diesen Workflow wird die Version 2.5 des Taverna Workbench Core benötigt, also das letzte Release vor dem Apache Incubator.
* [Tesseract OCR 4.00](https://github.com/tesseract-ocr/tesseract/wiki)    
Für diesen Workflow wird Tesseract OCR in der Version 4.00 oder neuer benötigt. Windows-Benutzer können z.B. [hier](https://github.com/UB-Mannheim/tesseract/wiki) vorkompilierte Binaries für Tesseract 4.00 finden. Nach der Installation müssen Windows-Benutzer den Pfad zum Verzeichnis ```tessdata``` sowie zu ```tesseract.exe``` noch zu den Umgebungsvariablen hinzufügen.
Für Debian-basiertes Linux gibt es ein PPA für Tesseract 4, das [hier](https://launchpad.net/~alex-p/+archive/ubuntu/tesseract-ocr) zu finden ist. Tesseract 4.00 benötigt zudem Version 1.7.4 oder neuer von leptonica. Hierfür stellt die UB Mannheim [hier](https://digi.bib.uni-mannheim.de/tesseract/leptonica/) ebenfalls vorkomplilierte deb-Pakete bereit. 
* [Apache Commons Lang3](https://commons.apache.org/proper/commons-lang/)    
Laden Sie bitte die Datei ```commons-lang3-3.6-bin.tar.gz``` bzw. ```commons-lang3-3.6-bin.tar.gz``` herunter und entpacken sie dieses Archiv. Anschließend muss die Datei ```commons-lang3-3.6.jar``` noch in das Unterverzeichnis ```lib``` der Taverna-Installation kopiert werden.

## Anleitung
Nach der erfolgreichen Installation der oben genannten Softwarekomponenten sind ggf. noch die in der Workflowbeschreibung enthaltenen Pfade/Verzeichnisse für die lokale Umgebung anzupassen:

1. ...
2. ...
3. ...
