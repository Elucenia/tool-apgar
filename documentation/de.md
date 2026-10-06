<!-- ELUCENIA technical documentation · apgar · de · no clinical/professional/rights approval -->

# Apgar-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/apgar)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Herzfrequenz

`fc`

- `0` — Nicht vorhanden
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Atemanstrengung

`resp`

- `0` — Nicht vorhanden
- `1` — Langsam, unregelmäßig
- `2` — Gut, kräftiges Schreien

### Muskeltonus

`tonus`

- `0` — Schlaff
- `1` — Etwas Beugung
- `2` — Aktive Bewegungen

### Reflexerregbarkeit

`reflexo`

- `0` — Keine Reaktion
- `1` — Grimassieren
- `2` — Schreien, Husten oder Niesen

### Farbe

`cor`

- `0` — Zyanose oder Blässe
- `1` — Rosiger Körper, zyanotische Extremitäten
- `2` — Vollständig rosig

## Fassung der Methode

Apgar 1953: 5 Zeichen 0–2; AAP/ACOG 2015 nach 1/5 min, Wiederholung bei \<7

## Dokumentierte Formel

Fünf Zeichen, je 0 bis 2: Herzfrequenz, Atemanstrengung, Tonus, Reflexantwort, Hautfarbe. Gesamt 0 bis 10 nach 1 und 5 Minuten; bei 5-Minuten-Score \<7 alle 5 bis 20 Minuten wiederholen.

## Grenzen und Population

Apgar dokumentiert den Zustand des Neugeborenen und die Reaktion auf die Reanimation; er legt weder die anfänglichen Reanimationsschritte fest noch diagnostiziert er Asphyxie oder sagt allein individuelle Sterblichkeit oder neurologische Ergebnisse voraus. Ein während der Reanimation vergebener Score entspricht nicht einem bei Spontanatmung erhobenen Score. Frühgeburtlichkeit, mütterliche Medikamente und Untersuchungsvariabilität können das Ergebnis beeinflussen.

## Referenzen

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Beruhigend (7 bis 10)


### 2

Mäßig auffällig (4 bis 6)

Wenn es nach 5 Minuten fortbesteht, alle 5 Minuten bis zu 20 Lebensminuten erneut beurteilen.


### 3

Beruhigend (7 bis 10)


### 4

Niedriger Apgar (0 bis 3)

Die Reanimation sollte bereits laufen. Apgar ≤ 5 nach 5 Minuten: Nabelschnurblutgasanalyse abnehmen und die Beurteilung alle 5 Minuten bis 20 Minuten fortsetzen.

