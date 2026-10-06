<!-- ELUCENIA technical documentation · apgar · it · no clinical/professional/rights approval -->

# Punteggio di Apgar

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/apgar)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Frequenza cardiaca

`fc`

- `0` — Assente
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Sforzo respiratorio

`resp`

- `0` — Assente
- `1` — Lento, irregolare
- `2` — Buono, pianto vigoroso

### Tono muscolare

`tonus`

- `0` — Flaccido
- `1` — Una certa flessione
- `2` — Movimenti attivi

### Reattività riflessa

`reflexo`

- `0` — Nessuna risposta
- `1` — Smorfia
- `2` — Pianto, tosse o starnuto

### Colore

`cor`

- `0` — Cianosi o pallore
- `1` — Corpo roseo, estremità cianotiche
- `2` — Completamente roseo

## Edizione del metodo

Apgar 1953: 5 segni 0–2; follow-up AAP/ACOG 2015 a 1/5 min, ripetere se \<7

## Formula documentata

Cinque segni, 0 a 2: frequenza cardiaca, sforzo respiratorio, tono, irritabilità riflessa, colore. Totale 0 a 10 a 1 e 5 minuti; se a 5 minuti \<7, ripetere ogni 5 fino a 20 minuti.

## Limiti e popolazione

Apgar registra le condizioni del neonato e la risposta alla rianimazione; non definisce le fasi iniziali della rianimazione, non diagnostica asfissia e non predice da solo la mortalità o l’esito neurologico individuale. Il punteggio attribuito durante la rianimazione non equivale a quello ottenuto in respirazione spontanea. Prematurità, farmaci materni e variabilità dell’esame possono influenzare il risultato.

## Riferimenti

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Rassicurante (7 a 10)


### 2

Moderatamente anormale (4 a 6)

Se persiste a 5 minuti, rivalutare ogni 5 minuti fino a 20 minuti di vita.


### 3

Rassicurante (7 a 10)


### 4

Apgar basso (0 a 3)

La rianimazione dovrebbe già essere in corso. Apgar ≤ 5 a 5 minuti: eseguire emogasanalisi del cordone e mantenere la valutazione ogni 5 minuti fino a 20 minuti.

