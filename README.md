# Material für eine Einführung in Digital Scholarly Editions 

Hier gespeicherte Dateien:
- *README.md:* Die Datei, die sie gerade lesen.
- *tei_template.xml:* Template für eine TEI-Datei. Laden Sie diese Datei herunter, um eine Transkription zu erstellen.
- *transkribus_raw.txt:* Eine rohe, unkorrigierte Transkription des hier als Beispiel verwendeten Dokuments. Falls Sie bei der Verwendung von Transkribus auf Probleme gestoßen sind, können sie diese Datei als Ausgangspunkt verwenden.

Um eine Datei herunter zu laden, gehen Sie bitte wie folgt vor:
1. Klicken Sie auf die Datei in der Übersicht.
2. Die Datei wird geöffnet.
3. Klicken Sie auf das Downloadsymbol (<img width="35" height="40" alt="grafik" src="https://github.com/user-attachments/assets/1271b79f-6b90-41d4-9375-6f660af32e76" />„Download raw file“) in der Leiste rechts oben über dem Dateiinhalt.


# Wichtige Tags
## Wichtige Strukturelle Tags:
### Bereich
```xml
<div type="chapter">…</div>
```
### Überschrift
```xml
<head type="main">Die wunderbare Welt des XML und andere Horrorstories</head>
```
### Absatz
```xml
<p>Hier beginnt ein Absatz. Der nächste Punkt beendet den Absatz.</p>
```
### Seitenumbruch
```xml
<pb n="1r"/>
```
### Zeilenbeginn
```xml
<lb/>Hier hat gerade eine Zeile begonnen …
```
### Listen
```xml
  <list>
        <item>...</item>
        <item>...</item>
  </list>
```
## Wichtige Semantische Tags:
### Streichung 
```xml
<del>Klassischer Richtung</del>
```
### Ergänzung
```xml
mich<add place="above">riet</add> mir
```
### Ersetzung
```xml
<subst>
  <del>ursprünglicher Text</del>
  <add>ersetzter Text</add>
</subst>
```
### Personen
```xml
<rs ref="#Kralik_Richard" type="name">Rich. K.</rs>
```
### Orte 
```xml
<rs ref="#Wien" type="place">Viennæ</rs>
```
### Werke
```xml
<rs ref="#Rosenkranz" type="work" subtype="printed">Der Rosenkranz</rs>
```
### Ereignisse
```xml
<eventName>Hochzeit</eventName>
```
