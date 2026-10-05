<!-- ELUCENIA technical documentation · cdai-sdai · de · no clinical/professional/rights approval -->

# CDAI und SDAI

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/cdai-sdai)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Druckschmerzhafte Gelenke (von 28)

`tjc`

Bereich: 0–28

### Geschwollene Gelenke (von 28)

`sjc`

Bereich: 0–28

### Globale Beurteilung durch den Patienten

`pga`

0 bis 10 · Bereich: 0–10

### Globale Beurteilung durch den Arzt

`ega`

0 bis 10 · Bereich: 0–10

### C-reaktives Protein (für SDAI)

`pcr`

mg/dL · optional · Bereich: 0–30

## Fassung der Methode

SDAI/Smolen 2003 und CDAI/Aletaha 2005: 28 Gelenke; globale Beurteilungen 0–10; CRP mg/dL nur im SDAI

## Dokumentierte Formel

CDAI = druckschmerzhafte Gelenke (28) + geschwollene Gelenke (28) + globale Patientenbeurteilung (0–10) + Arztbeurteilung (0–10). Bereich 0–76.

SDAI = CDAI + CRP (mg/dL). Bereich 0 bis etwa 86.

## Grenzen und Population

Der SDAI von 2003 wurde für Aktivität und Therapieansprechen bei rheumatoider Arthritis untersucht, mit Zählung von 28 Gelenken, globalen Beurteilungen auf einer Skala von 0–10 und CRP in mg/dL. Er ist kein alleiniger diagnostischer Test auf rheumatoide Arthritis. CDAI ohne CRP und Aktivitätsschwellen gehören zu ihren jeweiligen Varianten und müssen in den spezifischen Quellen geprüft werden.

## Referenzen

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
