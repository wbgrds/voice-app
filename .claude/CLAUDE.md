# CLAUDE.md – voice-app

## Zweck des Repos

Sprache-zu-Text-App für Windows 11: Tastenkürzel (Hotkey) startet eine Live-Transkription über Deepgram. Laut `README.md`. Art des Repos: derzeit nur Dokumentation, kein Anwendungscode.

## Stand

- Der Verlauf enthält einen einzigen Commit (`Initial commit`) und eine Datei (`README.md`, zwei Zeilen).
- Der Quellcode der App liegt nicht im Repo. Befehle, Struktur und Architektur sind daher nicht bestimmbar.

## Befehle

- Keine. Es gibt keine Build-, Test-, Lint- oder Startdateien im Repo.

## Umgebung

- Zielplattform: Windows 11 (laut `README.md`).
- Externer Dienst: Deepgram (Transkription). Name und Art der Zugangsdaten sind nicht dokumentiert. Zugangsdaten nicht in das Repo schreiben.

## Konventionen

- Sprache: Deutsch in der Dokumentation.
- Commit-Format, Branch- und PR-Workflow: ungeprüft, nur ein Commit vorhanden.

## Grenzen

- Nicht manuell ändern: `.git/`.
- Keine API-Schlüssel, Tokens oder Audiodaten in Dateien dieses Repos.

## Lücken (vor der ersten Pflege klären)

- Quellcode, Build- und Startanleitung fehlen.
- Sprache und Framework der App sind nicht angegeben.
- Benötigte Umgebungsvariablen für Deepgram sind nicht dokumentiert.
