<!-- ELUCENIA technical documentation · cdai-sdai · it · no clinical/professional/rights approval -->

# CDAI e SDAI

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/cdai-sdai)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Articolazioni dolenti (su 28)

`tjc`

intervallo: 0–28

### Articolazioni tumefatte (su 28)

`sjc`

intervallo: 0–28

### Valutazione globale del paziente

`pga`

0 a 10 · intervallo: 0–10

### Valutazione globale del medico

`ega`

0 a 10 · intervallo: 0–10

### Proteina C-reattiva (per SDAI)

`pcr`

mg/dL · facoltativo · intervallo: 0–30

## Edizione del metodo

SDAI/Smolen 2003 e CDAI/Aletaha 2005: 28 articolazioni; valutazioni globali 0–10; PCR mg/dL solo nello SDAI

## Formula documentata

CDAI = articolazioni dolenti (28) + tumefatte (28) + valutazione globale del paziente (0–10) + del medico (0–10). Intervallo 0–76.

SDAI = CDAI + PCR (mg/dL). Intervallo 0 a circa 86.

## Limiti e popolazione

Lo SDAI del 2003 è stato studiato per l’attività e la risposta al trattamento dell’artrite reumatoide, con conteggio di 28 articolazioni, valutazioni globali su scala 0–10 e PCR in mg/dL. Non è un test diagnostico autonomo per l’artrite reumatoide. Il CDAI senza PCR e le soglie di attività appartengono alle rispettive varianti e devono essere verificati nelle fonti specifiche.

## Riferimenti

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

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

Attività moderata secondo il CDAI

| Dettagli del risultato | |
| --- | --- |
| SDAI | 17,2 (attività moderata) |


### 2

Remissione secondo il CDAI


### 3

Bassa attività secondo il CDAI


### 4

Alta attività secondo il CDAI

