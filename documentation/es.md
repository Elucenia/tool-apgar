<!-- ELUCENIA technical documentation · apgar · es · no clinical/professional/rights approval -->

# Puntuación de Apgar

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/apgar)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Frecuencia cardíaca

`fc`

- `0` — Ausente
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Esfuerzo respiratorio

`resp`

- `0` — Ausente
- `1` — Lento, irregular
- `2` — Bueno, llanto vigoroso

### Tono muscular

`tonus`

- `0` — Flácido
- `1` — Alguna flexión
- `2` — Movimientos activos

### Irritabilidad refleja

`reflexo`

- `0` — Sin respuesta
- `1` — Mueca
- `2` — Llanto, tos o estornudo

### Color

`cor`

- `0` — Cianosis o palidez
- `1` — Cuerpo rosado, extremidades cianóticas
- `2` — Completamente rosado

## Edición del método

Apgar 1953: 5 signos 0–2; seguimiento AAP/ACOG 2015 a 1/5 min, repetir si \<7

## Fórmula documentada

Cinco signos, 0 a 2: frecuencia cardíaca, esfuerzo respiratorio, tono, irritabilidad refleja, color. Total 0 a 10 al minuto 1 y 5; si en 5 minutos \<7, repetir cada 5 hasta 20 minutos.

## Límites y población

Apgar registra el estado del recién nacido y la respuesta a la reanimación; no define los pasos iniciales de la reanimación, no diagnostica asfixia ni predice por sí solo la mortalidad o el desenlace neurológico individual. La puntuación asignada durante la reanimación no equivale a la obtenida en respiración espontánea. La prematuridad, los medicamentos maternos y la variabilidad de la exploración pueden influir en el resultado.

## Referencias

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
