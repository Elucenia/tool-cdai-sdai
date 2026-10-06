<!-- ELUCENIA technical documentation · cdai-sdai · en · no clinical/professional/rights approval -->

# CDAI and SDAI

[conditions, sources and permissions](https://elucenia.org/en/tools/cdai-sdai)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Tender joints (out of 28)

`tjc`

range: 0–28

### Swollen joints (out of 28)

`sjc`

range: 0–28

### Patient global assessment

`pga`

0 to 10 · range: 0–10

### Physician global assessment

`ega`

0 to 10 · range: 0–10

### C-reactive protein (for SDAI)

`pcr`

mg/dL · optional · range: 0–30

## Method edition

SDAI/Smolen 2003 and CDAI/Aletaha 2005: 28 joints; global assessments 0–10; CRP mg/dL only in SDAI

## Documented formula

CDAI = tender joints (28) + swollen joints (28) + patient global assessment (0–10) + physician global assessment (0–10). Range 0–76.

SDAI = CDAI + CRP (mg/dL). Range 0 to approximately 86.

## Limits and population

The 2003 SDAI was studied for rheumatoid arthritis activity and treatment response, with a 28-joint count, global assessments on a 0–10 scale and CRP in mg/dL. It is not a standalone diagnostic test for rheumatoid arthritis. CDAI without CRP and the activity cutoffs belong to their respective variants and must be checked in the specific sources.

## References

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

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

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Moderate activity by CDAI

| Result details | |
| --- | --- |
| SDAI | 17.2 (moderate activity) |


### 2

Remission by CDAI


### 3

Low activity by CDAI


### 4

High disease activity by CDAI

