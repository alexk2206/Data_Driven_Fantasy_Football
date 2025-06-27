# 📊 Data-Driven Fantasy Football

Ein datengetriebenes Projekt zur Optimierung von Fantasy-Football-Drafts mithilfe von Mixed-Integer Programming (MIP), simulationsbasierten Heuristiken und realen NFL-Daten.

## 🔍 Ziel des Projekts

Dieses Repository bietet eine Sammlung von Notebooks und Datensätzen, um:

* Draft-Simulationen durchzuführen (ADP- und MIP-basiert)
* verschiedene Auswahlstrategien zu evaluieren
* projektionsbasierte Spielerauswahl zu realisieren
* reale NFL-Daten für eine performanceorientierte Draft-Optimierung zu nutzen

## 📁 Projektstruktur

| Verzeichnis / Datei                                                                       | Beschreibung                                                                                |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `ADP_draft_simulations.ipynb`                                                             | Simuliert Drafts basierend auf Average Draft Position (ADP).                                |
| `MIP_draft_simulations.ipynb`                                                             | Simuliert Drafts mithilfe eines gemischt-ganzzahligen Optimierungsmodells (MIP).            |
| `Mixed_Integer_Problem_for_Draft_Optimization.ipynb`                                      | Formuliert das Draftproblem als MIP-Modell mit Constraints wie Budget, Positionsbedarf etc. |
| `Evaluation.ipynb`                                                                        | Bewertet und vergleicht verschiedene Draftstrategien.                                       |
| `create_real_projection.ipynb`                                                            | Erstellt aggregierte Spielerprojektionen aus realen Datenquellen.                           |
| `nfl_data_by_rowzero.ipynb`                                                               | Ruft reale Woche-für-Woche-Statistiken ab.                                                  |
| `Weekly_Data/`                                                                            | Erstellt aggregierte reale Woche-für-Woche-Statistiken.                                     |
| `bye_weeks/`, `pre_season_data/`, `projection_data/`, `real_projections/`, `simulations/` | Datenordner mit Vorverarbeitungs- und Prognosedaten.                                        |

## ⚙️ Anforderungen

Installiere benötigte Python-Pakete, z. B. via `pip` oder in einem Jupyter-Notebook:

pip install pandas numpy pulp matplotlib openpyxl

Für interaktive Ausführung wird empfohlen, JupyterLab oder Google Colab zu verwenden.

## 📈 Features

* 🧮 **MIP-Modellierung:** Auswahlstrategie mit Nebenbedingungen wie Kadergröße, Budget und Bye-Weeks
* 🔄 **Simulation:** Verschiedene Draftverläufe unter Unsicherheit
* 📊 **Evaluation:** Vergleich klassischer Heuristiken mit Optimierungsmethoden
* 📂 **Realitätsnahe Daten:** NFL-Spielerstatistiken und Projektionen

## 📌 To Do / Ideen

* [ ] Einbindung agentenbasierter Konkurrenzsimulation
* [ ] Automatisierte Projektionsaktualisierung mit aktuellen NFL-Daten
* [ ] Web-Dashboard zur Visualisierung von Draftstrategien

## 👤 Autor

**Alexander Keßler**
[GitHub: alexk2206](https://github.com/alexk2206)
