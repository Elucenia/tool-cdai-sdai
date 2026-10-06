<!-- ELUCENIA technical documentation · cdai-sdai · es · no clinical/professional/rights approval -->

# CDAI y SDAI

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/cdai-sdai)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Articulaciones dolorosas (de 28)

`tjc`

intervalo: 0–28

### Articulaciones inflamadas (de 28)

`sjc`

intervalo: 0–28

### Evaluación global del paciente

`pga`

0 a 10 · intervalo: 0–10

### Evaluación global del médico

`ega`

0 a 10 · intervalo: 0–10

### Proteína C reactiva (para SDAI)

`pcr`

mg/dL · opcional · intervalo: 0–30

## Edición del método

SDAI/Smolen 2003 y CDAI/Aletaha 2005: 28 articulaciones; valoraciones globales 0–10; PCR mg/dL solo en SDAI

## Fórmula documentada

CDAI = articulaciones dolorosas (28) + tumefactas (28) + valoración global del paciente (0–10) + del médico (0–10). Rango 0–76.

SDAI = CDAI + PCR (mg/dL). Rango 0 a aproximadamente 86.

## Límites y población

El SDAI de 2003 se estudió para la actividad y la respuesta al tratamiento de la artritis reumatoide, con recuento de 28 articulaciones, evaluaciones globales en escala 0–10 y PCR en mg/dL. No es una prueba diagnóstica aislada de artritis reumatoide. El CDAI sin PCR y los puntos de corte de actividad pertenecen a sus respectivas variantes y deben comprobarse en las fuentes específicas.

## Referencias

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

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

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Actividad moderada por CDAI

| Detalles del resultado | |
| --- | --- |
| SDAI | 17,2 (actividad moderada) |


### 2

Remisión por CDAI


### 3

Actividad baja por CDAI


### 4

Alta actividad por CDAI

