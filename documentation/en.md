<!-- ELUCENIA technical documentation · apgar · en · no clinical/professional/rights approval -->

# Apgar score

[conditions, sources and permissions](https://elucenia.org/en/tools/apgar)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Heart rate

`fc`

- `0` — Absent
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Respiratory effort

`resp`

- `0` — Absent
- `1` — Slow, irregular
- `2` — Good, strong cry

### Muscle tone

`tonus`

- `0` — Flaccid
- `1` — Some flexion
- `2` — Active movements

### Reflex irritability

`reflexo`

- `0` — No response
- `1` — Grimace
- `2` — Crying, coughing or sneezing

### Color

`cor`

- `0` — Cyanosis or pallor
- `1` — Pink body, cyanotic extremities
- `2` — Entirely pink

## Method edition

Apgar 1953: 5 signs 0–2; AAP/ACOG 2015 follow-up at 1/5 min and repeat if \<7

## Documented formula

Five signs, each 0 to 2: heart rate, respiratory effort, tone, reflex irritability, color. Total 0 to 10 at 1 and 5 minutes; if the 5-minute score is \<7, repeat every 5 minutes up to 20 minutes.

## Limits and population

Apgar records the newborn’s condition and response to resuscitation; it does not determine the initial steps of resuscitation, diagnose asphyxia or predict individual mortality or neurological outcomes on its own. A score assigned during resuscitation is not equivalent to one obtained during spontaneous breathing. Prematurity, maternal medicines and variability in the examination can influence the result.

## References

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
