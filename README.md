# Carey

Lernbegleitung für das Modul Projektmanagement (Bachelor Pflege) mit drei Agenten
Kursassistent (Fragen zum Skript), Coach (Sparring ohne fertige Lösungen) und
simulierter Auftraggeber (Einschätzung hochgeladener Präsentationen, Übung des Fachgesprächs).

## Dateien
- app.py                Die Anwendung. Rollen der Agenten stehen im Block AGENTEN.
- requirements.txt      Benötigte Pakete
- skript/               Hier die Kursfolien als PPTX oder PDF ablegen (Text, keine Scans)
- secrets_VORLAGE.toml  Vorlage für die Secrets, nicht mit echtem Schlüssel auf GitHub
- logo.png              Optional, erscheint oben links
- .streamlit/config.toml Farbe der Oberfläche

## Einrichtung
1. Neues GitHub Repository anlegen und alle Dateien samt Ordner hochladen.
2. Folien in den Ordner skript hochladen (Add file, Upload files, im Ordner skript).
3. Auf share.streamlit.io "Create app", Repository wählen, Hauptdatei app.py.
4. Unter Settings, Secrets den Inhalt der Vorlage einfügen und Werte ersetzen.
5. Adresse mit ?test=1 am Ende öffnen, anmelden, "Verbindung testen".

## Hinweise
- Der Hinweis, dass allein der Dozent verbindlich einschätzt, wird bei Coach und
  Auftraggeber fest unter jeder Antwort eingeblendet, unabhängig vom Sprachmodell.
- Bilder und Grafiken (z. B. Gantt Diagramme) werden nicht ausgewertet, nur Text.
- Nach Änderungen 1 bis 2 Minuten warten, bei Problemen in Streamlit "Reboot".
