# Mini-Bloomberg: Finanzdatenanalyse

Statistische Analyse und Bewertung der Finanzkraft von Microsoft, Apple und Jenoptik auf Basis von Geschäftsberichten.

## 1. Zielsetzung
Dieses Projekt verfolgt das Ziel, mithilfe mathematisch-statistischer Methoden die finanzielle Stabilität ausgewählter Unternehmen zu beleuchten. Ziel ist es, auf Basis von harten Fakten (Finanzberichten) eine fundierte Grundlage für langfristige Investitionsstrategien zu schaffen, abseits von kurzfristigen Markttrends.

## 2. Methodik
Um die Zuverlässigkeit der Analyse zu gewährleisten, wurden folgende statistische Verfahren angewendet:

* **Robust Z-Score:** Zur Berechnung der relativen Position von Finanzkennzahlen wurden der **Median** und die **MAD (Median Absolute Deviation)** verwendet. Dies minimiert den Einfluss von Ausreißern (Outlier) und ermöglicht eine präzisere Bewertung im Vergleich zum Standard-Z-Score.
* **Multikollinearitäts-Check:** Analyse der Interaktionen zwischen Variablen, um Redundanzen zu vermeiden und die Modellzuverlässigkeit zu stärken.
* **Hypothesengetriebener Ansatz:** Formulierung und statistische Prüfung spezifischer Hypothesen zu Unternehmenswachstum und Profitabilität.

## 3. Kernergebnisse
* **Microsoft:** Fokus auf KI- und Cloud-Infrastruktur führt zu hoher operativer Effizienz bei gleichzeitigem strategischem Wachstum.
* **Apple:** Extrem hohe Kapitalrendite durch gezieltes Leverage-Management und starke Markenbindung.
* **Jenoptik:** Hohe Margenstabilität und kontinuierlicher Abbau der Verschuldung bei solidem operativen Ergebnis.

## 3. Analyseergebnisse & Hypothesenprüfung

### Hypothesenprüfung (Multikollinearität)
Im Rahmen der Analyse wurde die Hypothese aufgestellt, dass bestimmte Finanzkennzahlen unabhängig voneinander das Unternehmenswachstum beeinflussen.
* **Ergebnis:** Der Multikollinearitäts-Check zeigte, dass einige Variablen stark korrelierten und die ursprüngliche Hypothese somit nicht in ihrer vollen Form bestätigt werden konnte.
* **Erkenntnis:** Diese "gescheiterte" Hypothese führte zu einer präziseren Variablenauswahl. Es wurde deutlich, dass die Auswahl unabhängiger Faktoren entscheidend ist, um Verzerrungen in der Unternehmensbewertung zu vermeiden.

## 4. Unternehmensergebnisse
* **Microsoft:** Strategisches Wachstum durch KI-Investitionen bei gleichzeitig hoher operativer Effizienz, trotz leicht sinkender Eigenkapitalrendite (ROE).
* **Jenoptik:** Hohe Margenstabilität und kontinuierlicher Schuldenabbau, was auf eine solide finanzielle Basis hindeutet.
* **Apple:** Gezielte Nutzung von Fremdkapital (Leverage) zur Maximierung der Eigenkapitalrendite bei starker Markenstabilität.

* ## 5. Tech-Stack
* **Sprache:** Python
* **Bibliotheken:** Pandas, NumPy, Matplotlib, Seaborn
* **Tool:** Jupyter Notebook

* ### Fazit & Lernergebnisse
* **Umgang mit Multikollinearität:** Die Erkenntnis, dass Korrelationen zwischen Variablen das Modell verzerren können, führte zu einer kritischeren Variablenauswahl.
* **Wissenschaftliche Integrität:** Das Scheitern einer Hypothese wurde als Chance genutzt, um die Analyse zu verfeinern und die tatsächliche Datenstruktur besser zu verstehen.
* **Statistische Präzision:** Die Anwendung des Robust Z-Scores verdeutlichte die Notwendigkeit, Methoden an die spezifischen Eigenschaften von Finanzdaten anzupassen
