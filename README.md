# PaperLab – öffentliches Wettjournal

Öffentliche, schreibgeschützte Ansicht: https://cl0ckh0us3.github.io/paperlab/

## Aufbau

- `index.html`: öffentliche Dashboard-Oberfläche (ohne Editor).
- `journal-data.json`: veröffentlichte Einträge und Ergebnisse. Die Webseite liest diese Datei automatisch ein.

## Aktualisierung über ChatGPT

Dieses Repository ist mit ChatGPT über die GitHub-Verbindung erreichbar. Für neue Einträge oder Ergebnisse kann der Besitzer im Chat beispielsweise schreiben:

> „Aktualisiere das PaperLab-Journal mit den bestätigten Ergebnissen und veröffentliche die Webseite.“

Bei Änderungen zuerst den **aktuellen Repository-Stand** auslesen, nur bestätigte Daten anpassen und dann ausschließlich `journal-data.json` mit dem aktuellen SHA auf dem `main`-Branch aktualisieren. Für Darstellungsänderungen gegebenenfalls `index.html` bearbeiten. Bisherige Einträge, Einsatzwerte, Quoten und IDs nicht unbeabsichtigt überschreiben. Die Versionsnummer bleibt bei reinen Wett- oder Ergebnisupdates unverändert.

Die Veröffentlichung erfolgt über GitHub Pages nach einem Commit auf `main`. Es werden keine Zugangsdaten in Repository-Dateien gespeichert.

**Hinweis:** Die Webseite zeigt ein simuliertes Wettjournal. Besucher haben keine Bearbeitungsberechtigung für die Repository-Dateien.
