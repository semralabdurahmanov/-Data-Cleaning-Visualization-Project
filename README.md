# Data Cleaning & Visualization Project

## 📌 Projektbeschreibung
Dieses Mini-Projekt zeigt den vollständigen Workflow eines Data-Analysis-Projekts:
von der Datenbereinigung bis zur explorativen Analyse und Visualisierung.

Der Fokus liegt auf:
- Datenqualität
- nachvollziehbarer Bereinigung
- klarer Trennung von Cleaning und Analyse

---

## 📂 Projektstruktur

data-cleaning-project/
├── data/
│   ├── candlestick_chart_raw.csv        # Rohdaten (unbereinigt)
│   └── candlestick_chart_cleaned.csv    # Bereinigter Datensatz
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_visualization.ipynb
│
├── README.md

---

## 🧹 01 Data Cleaning
Im Notebook `01_data_cleaning.ipynb` werden folgende Schritte durchgeführt:

- Überprüfung der Datenstruktur (`df.info()`)
- Korrektur von Datentypen (z. B. Datum, numerische Werte)
- Behandlung fehlender Werte
- Plausibilitätsprüfung mit `df.describe()`
- Erzeugung eines bereinigten Datensatzes

Ergebnis:
- `cleaned_data.csv`

---

## 📊 02 Visualisierung & Analyse
Im Notebook `02_visualization.ipynb` erfolgt die explorative Datenanalyse:

- Zeitreihenvisualisierung
- Vergleich verschiedener Preisattribute
- Analyse des Handelsvolumens
- Interpretation der Visualisierungen

Die Analyse erfolgt **interpretativ auf Basis der Diagramme**.

---

## 🛠️ Verwendete Technologien
- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🎓 Ziel des Projekts
Dieses Projekt dient als:
- Lernprojekt für Data Cleaning & EDA
- Beispiel für saubere Projektstruktur
- Referenz für Studium / Portfolio

---

## 📬 Hinweis
Die Daten wurden ausschließlich zu Analyse- und Lernzwecken verwendet.

