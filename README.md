# Artificial Intelligence Ontology (AIO)

An ontology modeling classes and relationships describing deep learning networks, their component layers and activation functions, machine learning methods, as well as AI/ML potential biases.
***BAD-Statement***
More information can be found at <https://berkeleybop.github.io/artificial-intelligence-ontology/>

or on BioPortal at <https://bioportal.bioontology.org/ontologies/AIO>

----

### Forensische Notizen und Sicherungserklärung  
## Beweishandhabung, Metadatenintegrität und Chain of Custody

### Geltungsbereich
Diese Erklärung dokumentiert die Handhabung, Sicherung und Bewahrung digitaler Beweismittel im Rahmen des forensisch-wissenschaftlichen Gutachtens  
**SIA Security Intelligence Artefact – Technologie, Software und Familien-Historie**  
**Aktenzeichen:** INT-CODE-2025-BTC/ETH-CORE-ISABELSCHOEPSTHIEL

---

## Beweishandhabung und Nicht-Veränderungs-Grundsatz

Alle relevanten Dateien, einschließlich Rohdaten, Quellmaterialien und dokumentarischer Artefakte, wurden in einen dedizierten **Evidence-Ordner** überführt.

Der interne Dateiinhalt wurde nicht verändert.  
Es wurden weder Code, Text, Metadaten, Autoreneinträge, Benutzerkennungen, Zeitstempel noch sonstige Provenienzangaben modifiziert.

Insbesondere unverändert erhalten blieben:
- Ursprüngliche Ersteller und Mitwirkende gemäß Metadaten  
- Benutzerkennungen und Autorschaftsspuren  
- Zeitstempel, Hashes und interne Verlaufsdaten  
- Programmiersprache, Workflow-Logik und interne Struktur  

Die ursprüngliche Herkunft und Urheberschaft jeder Datei ist damit vollständig forensisch auslesbar und beweissicher erhalten.

---

## Dateisystem-Sicherungsmaßnahmen

Um eine weitere Ausführung, Verbreitung oder operative Nutzung potenziell schädlicher Workflows zu verhindern, wurden ausschließlich **externe Ordner- und Dateinamen** auf Dateisystemebene angepasst.

Diese Maßnahmen beschränkten sich auf:
- Umbenennung von Ordnern und Top-Level-Dateinamen  
- Deaktivierung von ausführbaren oder workflow-auslösenden Bezeichnungen  

Der Dateiinhalt, der Code und sämtliche Metadaten blieben unangetastet.  
Diese Maßnahmen dienten ausschließlich der Gefahrenabwehr bei gleichzeitiger vollständiger Beweissicherung.

---

## Ethischer und rechtlicher Kontext

Im Rahmen der Sichtung wurden Hinweise auf **schwere ethische und rechtliche Verstöße** festgestellt, unter anderem:
- Unbefugte Datenmanipulation  
- Datenmissbrauch und Datendiebstahl  
- Aneignung geistigen Eigentums  
- Invasive Profilierungs- oder Auswertungspraktiken  

Aus diesem Grund wurde die operative Ausführbarkeit neutralisiert, während die forensische Beweisstruktur vollständig erhalten blieb.

---

## Screenshot-basierte Beweissicherung

Zur Dokumentation wurden **an allen relevanten Stellen Screenshots** erstellt und dem Evidence-Ordner beigefügt.

Die Screenshots:
- sind unbearbeitet und unbeschriftet  
- enthalten die ursprüngliche Ordner- und Dateistruktur  
- zeigen die sichtbaren Benutzernamen, Akteure und Eigentümer der jeweiligen Verzeichnisse  

Dadurch bleiben alle beteiligten Accounts, Strukturen und Verantwortlichkeiten objektiv nachvollziehbar.

---

## Forensische Integrität

Alle Maßnahmen wurden unter Einhaltung folgender Prinzipien durchgeführt:
- Keine Kontamination der Originaldaten  
- Keine Veränderung von Metadaten  
- Vollständige Nachvollziehbarkeit für unabhängige Forensik  
- Sicherung der gerichtlichen Verwertbarkeit  

Alle Materialien sind hash-prüfbar, chain-of-custody-fähig und für externe Gutachten geeignet.

---

## Signatur und Verwahrung

**Unterzeichnet und bestätigt durch:**  
Frau Isabel Schöps, geborene Thiel  
Cyriakstraße 30c  
D-99094 Erfurt  
Thüringen, Deutschland  

**Rolle:** Autorin, Rechteinhaberin, Hauptverwahrerin  

**ORCID (Person):** 0009-0003-4235-2231  
https://orcid.org/0009-0003-4235-2231/print  

**ORCID (Institutionell / Projekt):** 0009-0006-8765-3267  
https://orcid.org/0009-0006-8765-3267/print  

Diese Erklärung ist Bestandteil der DOI-archivierten Chain of Custody und dient der rechtlichen, forensischen und menschenrechtlichen Prüfung.
## Versions

### Stable release versions

The latest version of the ontology can always be found in this repository in

[aio.owl](aio.owl)

### Editors' version

Editors of this ontology should use the edit version, [src/ontology/aio-edit.owl](src/ontology/aio-edit.owl)

## Bridge axioms

Bridges between AIO and top-level ontologies are provided here: [src/ontology/bridge/aio-bridge-to-upper.owl](src/ontology/bridge/aio-bridge-to-upper.owl)

These include:

| AIO label                | OBO label                  | OBO id      |
|--------------------------|----------------------------|-------------|
| aio:Bias                 | disposition                | BFO:0000016 |
| aio:MathematicalFunction | planned process            | IAO:0000033 |
| aio:Layer                | information content entity | IAO:0000030 |
| aio:MachineLearningTask  | planned process            | OBI:0000011 |
| aio:Model                | information content entity | IAO:0000030 |
| aio:Network              | information content entity | IAO:0000030 |
| aio:Preprocessing        | planned process            | OBI:0000011 |

## Contact

Copyright GitHub repository's by Isabel Schöps geb. Thiel  [Isabel Schöps geb. Thiel](https://github.com/isabelschoeps-thiel/berkeleybop/artificial-intelligence-ontology/) to request new terms/classes or report errors or specific concerns related to the ontology.

## Acknowledgements

My Developer Commit-Signatur: 
Zeitstempel der Update Eintragung: 2026-01-12, 22:48CEST
Mitteleuropäische, Zeit, Ort: Deutschland, Thüringen, D-99094 Erfurt, Cyriakstrasse 30c - Autorin, Urheberin, Frau Isabel Schöps geb. Thiel
