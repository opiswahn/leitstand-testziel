## ADDED Requirements

### Requirement: Zählerdateien

Das Repository SHALL unter `src/neustart/` die Dateien `1.txt` bis `5.txt` enthalten, jede mit ihrer Ziffer als einziger Zeile.

#### Scenario: Dateien vorhanden

- **WHEN** das Repository ausgecheckt ist
- **THEN** enthält `src/neustart/<n>.txt` genau die Zeile `<n>`
