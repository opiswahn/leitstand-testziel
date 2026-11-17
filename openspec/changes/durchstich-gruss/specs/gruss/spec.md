## ADDED Requirements

### Requirement: Begrüßungsdateien

Das Repository SHALL unter `src/durchstich/` die Dateien `hallo.txt` (Inhalt `Hallo`) und `welt.txt` (Inhalt `Welt`) enthalten.

#### Scenario: Dateien vorhanden

- **WHEN** das Repository ausgecheckt ist
- **THEN** enthalten `src/durchstich/hallo.txt` und `src/durchstich/welt.txt` je genau die vorgesehene Zeile
