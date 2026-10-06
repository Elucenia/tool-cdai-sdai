<!-- ELUCENIA technical documentation · cdai-sdai · pt-BR · no clinical/professional/rights approval -->

# CDAI e SDAI

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/cdai-sdai)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Articulações dolorosas (de 28)

`tjc`

intervalo: 0–28

### Articulações edemaciadas (de 28)

`sjc`

intervalo: 0–28

### Avaliação global pelo paciente

`pga`

0 a 10 · intervalo: 0–10

### Avaliação global pelo médico

`ega`

0 a 10 · intervalo: 0–10

### PCR (para o SDAI)

`pcr`

mg/dL · opcional · intervalo: 0–30

## Edição do método

SDAI/Smolen 2003 e CDAI/Aletaha 2005:28 articulações; globais 0–10; PCRmg/d L somente SDAI

## Fórmula documentada

CDAI = dolorosas (28) + edemaciadas (28) + avaliação global do paciente (0 a 10) + avaliação global do médico (0 a 10). Varia de 0 a 76.

SDAI = CDAI + PCR (mg/dL). Varia de 0 a cerca de 86.

## Limites e população

O SDAI de 2003 foi estudado para atividade e resposta ao tratamento da artrite reumatoide, com contagem de 28 articulações, avaliações globais em escala 0–10 e PCR em mg/dL. Não é um teste diagnóstico isolado de artrite reumatoide. O CDAI sem PCR e os cortes de atividade pertencem às respectivas variantes e precisam ser conferidos nas fontes específicas.

## Referências

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Atividade moderada pelo CDAI

| Detalhes do resultado | |
| --- | --- |
| SDAI | 17,2 (atividade moderada) |


### 2

Remissão pelo CDAI


### 3

Baixa atividade pelo CDAI


### 4

Alta atividade pelo CDAI

