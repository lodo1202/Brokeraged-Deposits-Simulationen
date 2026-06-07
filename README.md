# Brokered Deposits – Interaktive Simulation

Interaktives Präsentationstool zum Thema **Brokered Deposits – Darstellung des Marktes und der Auswirkungen in Europa**.

Erstellt im Rahmen des Vertiefungsseminars · HWZ Hochschule für Wirtschaft Zürich · Major Banking & Finance.

## Live-Demo

Sobald GitHub Pages aktiviert ist, ist die Simulation hier erreichbar:
`https://<dein-username>.github.io/<repo-name>/`

## Inhalt

Die Single-Page-Anwendung (`index.html`) enthält fünf interaktive Szenarien:

1. **Marktübersicht** – Wachstum des europäischen Marktes, Plattform-Breakdown, LCR-Abflussraten
2. **Stabilitätsprofil** – Vergleich der Abflusskurven verschiedener Einlagentypen (Raten editierbar)
3. **LCR-Simulator** – Echtzeit-Berechnung der Liquidity Coverage Ratio mit Szenariovergleich
4. **Zinsszenarien** – Auswirkung der EZB-Zinssätze auf Finanzierungskosten und Einlagenmigration
5. **Stresstest** – Konfigurierbare Bank-Run-Simulation (Fallstudien SVB / Credit Suisse 2023)

## Technik

- Reine HTML/CSS/JavaScript-Anwendung, keine Build-Tools nötig
- Charts via [Chart.js](https://www.chartjs.org/) (über CDN geladen)
- Läuft vollständig im Browser, keine Server-Komponente

## Lokal starten

Einfach `index.html` im Browser öffnen. Für die Präsentation empfiehlt sich der Vollbildmodus (F11).

## Lizenz

Ausschliesslich für Studienzwecke im Rahmen des HWZ-Vertiefungsseminars.
