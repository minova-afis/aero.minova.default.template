# Standard Repository Vorlage

Dieses Repository dient als Grundlage für alle Zukünftigen Repositories, die kein App Projekt sind. Diese Vorlage soll die Repositories vereinheitlichen. Dies soll durch folgende Standards erreicht werden:

- Issue-Templates
- Changelog
- Dokumentations Ordnerstruktur

#### App Projekte
Die Vorlage für App Repositories befindet sich [hier](https://github.com/minova-afis/aero.minova.default.template.app).

## Ersetzen beim Erstellen eines neuen Projektes

### 1. Issue Templates

In den Issue-Templates müssen die ``XXX`` in der Abrechnung SIS Tabelle entsprechend ersetzt werden. Diese findet man unter:

**Settings -> General -> Features -> Issues -> Set up Templates**

Dort das Jeweilige Template auswählen und bearbeiten. Zu beachten ist das neue Abrechnungsformat. Das sieht wie folgt aus:

**Abrechnung={KUNDE/KONTRAKT/PROJEKT/AUFWAND}**

Hier müssen die Werte in der korrekten Reihenfolge angegeben werden (Kunde, Kontrakt, Projekt, Aufwand) und sind jeweils durch ein ``/`` getrennt.
Soll ein Feld nicht vorbelegt werden, wird die entsprechende Stelle leer gelassen. 

Der Abrechnungs-String kann auch in der Beschreibung des Repositories vermerkt werden und gilt dann für alle Issues in diesem Repository, die den String nicht explizit überschreiben. 


**HINWEIS!!! Für die Projekte alles oberhalb von H1 Projektname in der README löschen**

# Projektname (Durch den Projektnamen ersetzen)

## Abrechnungsdaten

Die Abrechnungstabelle befindet sich in jedem Issue Template und muss nicht kopiert werden. 

Abrechnung={XXX/XXX/XXX/XXX}

## Changelog

Hier befindet sich das [Changelog](Changelog.md)

## Dokumentation

Hier befindet sich die [Dokumentation](doc/contens.md)
