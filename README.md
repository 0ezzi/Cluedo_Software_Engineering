# Cluedo – Software Engineering Dokumentation

Übersicht über alle Artefakte der digitalen Cluedo-Ausarbeitung  
(Use Cases, Klassendiagramm, Sequenzdiagramm, Datenmodell).

---

## Überblick

Dieses Repository bündelt die Software-Engineering-Dokumentation zum Brettspiel Cluedo.  
Ziel ist eine klar strukturierte, standardkonforme und leicht navigierbare Sammlung von Artefakten.

Organisation und Aufgabenverteilung haben über ein Trello-Board stattgefunden.

Hinweis: Die Schnelllinks unten ermöglichen einen direkten Zugriff auf die entsprechenden Dokumente.

---

## Schnelllinks

- **Trello-Board:**  
  Extern: [`trello.com/b/07q4iqQL`](https://trello.com/b/07q4iqQL)  
  Lokal: [`TrelloBoard.pdf`](docs/trello-board/TrelloBoard.pdf) · [`JSON-Export`](docs/trello-board/TrelloBoard.json)

- **UC – Use Cases:**  
  [`docs/usecases`](docs/usecases)

- **CD – Klassendiagramm:**  
  [`CD_ClassDiagram_Final.drawio`](docs/class-diagram/CD_ClassDiagram_Final.drawio) · [`CD_ClassDiagram_Final.pdf`](docs/class-diagram/CD_ClassDiagram_Final.pdf)

- **SD – Sequenzdiagramme:**
  - **SD01 – Suggestion:**  
    [`PDF`](docs/sequence-diagram/SD01_Suggestion.pdf) · [`drawio`](docs/sequence-diagram/SD01_Suggestion.drawio)
  - **SD02 – Turn:**  
    [`PDF`](docs/sequence-diagram/SD02_Turn.pdf) · [`drawio`](docs/sequence-diagram/SD02_Turn.drawio)

- **DM – Daten/Tabellen:**  
  [`DM_DataDictionary.pdf`](docs/data/DM_DataDictionary.pdf) · [`DM_Tables.pdf`](docs/data/DM_Tables.pdf) · [`DM_Tables.ods`](docs/data/DM_Tables.ods)

- **Präsentation:**  
  [`Presentation.pdf`](docs/presentation/Presentation.pdf) · [`Presentation.pptx`](docs/presentation/Presentation.pptx)

- **Prüfprotokoll (Audit):**  
  [`Pruefprotokoll.md`](docs/review/Pruefprotokoll.md)

- **AD – Aktivitätsdiagramme:**  
  Derzeit keine separate Datei im Repo; siehe [`Prüfprotokoll`](docs/review/Pruefprotokoll.md)

---

## Navigationsempfehlung

1. Beginne mit den Use-Case-Beschreibungen in `docs/usecases` (PDF) für Zieldefinition, Scope und Akteure.
2. Betrachte anschließend das Klassendiagramm in `docs/class-diagram` für die Strukturübersicht.
3. Analysiere die dynamischen Abläufe anhand der Sequenzdiagramme in `docs/sequence-diagram`.
4. Prüfe zuletzt das Datenmodell in `docs/data` (Data Dictionary und Tabellen).

---

## Repository-Struktur

```
/
└── docs/
    ├── class-diagram/      Hauptklassendiagramm (draw.io und PDF)
    ├── data/               Datenmodell, Tabellen, Dictionary
    ├── presentation/       Abschlusspräsentation
    ├── sequence-diagram/   Dynamische Abläufe (Sequenzdiagramme)
    ├── review/             Prüfprotokoll (Audit)
    ├── trello-board/       Projektorganisation (PDF-Export, JSON)
    └── usecases/           Formalisierte Use-Case-Beschreibungen
```

---

## Tools

- diagrams.net (draw.io) zur Diagrammerstellung
- Office-Anwendungen für Text, Tabellen und Präsentationen
- PDF-Export für finale, nicht bearbeitbare Artefakte
- Trello-Board zur Projektorganisation und Aufgabenverteilung

---

## Terminologie und Bezeichnungen

Zur einheitlichen Benennung werden folgende Begriffe verwendet (DE/EN):
- Vorschlag (Suggestion)
- Zug (Turn)
- Klassendiagramm (Class Diagram)
- Sequenzdiagramm (Sequence Diagram)
- Datenmodell (Data Model)

Dateinamen können englisch sein (z. B. SD01_Suggestion), die Texte im README sind deutsch. Inhaltlich sind die Begriffe konsistent. Abkürzungen werden einheitlich verwendet: UC (Use Cases), CD (Klassendiagramm), SD (Sequenzdiagramme), DM (Datenmodell).

---

## Mitwirkende

Die folgenden Personen haben zum Projekt beigetragen:

Josef Lautner - Kim Reger - Luis Schirmbeck - Nils Berggold

Kurs: WI24A3