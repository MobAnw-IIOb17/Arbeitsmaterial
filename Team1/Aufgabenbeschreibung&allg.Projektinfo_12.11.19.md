# Aufgabenverteilung

## Team 1

> quasi das Backend auf dem Gerät

- Anwendungsrahmen *--> bis nächste Woche erledigt*
	- gibt die Projektstruktur vor (wir erzeugen das Ionic-Projekt)
	- Git-Repo erstellen
- SQLite-Datenbank als Zwischenlayer bauen, wo immer die neuesten Daten vom Webservices reinkommen
	- genaue Struktur unsere Entscheidung
	- Mitarbeiter & Objekte aus der Originaldatenbank müssen auf jeden Fall zur Vefügung gestellt werden
	- möglicherweise kriegen wir noch weitere Anforderungen der anderen Teams und müssen weitere Tabellen anlegen, die dann aber nichts mit dem Webservice an sich zu tun haben
	- Schnittstelle mit JSON für die anderen Teams zur Verfügung stellen, damit die nix dran rumfummeln können
- Login & Einstellungen
	- Logindaten in den Storage schreiben
	- Login dient der Identifizierung, ist die Festlegung, welcher der Mitarbeiter aus der Datenbank das Gerät besitzt, wird dann automatisch mit jeder Schadensmeldung eingetragen
	- Einstellung sind Servereinstellungen
	- diese Einstellungen sind passwortgeschützt, damit nur der Admin darauf zugreifen kann
	- zusätzliche Einstellung: darf Objektkontrolle oder darf nicht
	- GUI fürs Einstellungsmenü soll von uns erstellt werden
- Webserviceschnittstelle implementieren zur Versendung von Schadensmeldungen und der Objektkontrolle
	- wird nur angestoßen, wenn Internetverbindung da, ansonsten zwischenspeichern

## Team 2

- Schadensmeldung
- Objektbrowser
- Meldungsbrowser

## Team3

- Objektkontrolle (Grundfunktion)
	- immer wieder kehrende Schadensfälle in Quick Menu
	- Beschreibung & Fotos
- Kontrollbrowswer

# Allg

- der Zwischenlayer fehlt, eine SQLite-Datenbank in der App
- wir bauen eine hybride App mit Ionic
- wir programmieren in Typescript
- **Dokumentieren!**, Beschreibung, Parameter, Returnvalue