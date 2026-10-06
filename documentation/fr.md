<!-- ELUCENIA technical documentation · cdai-sdai · fr · no clinical/professional/rights approval -->

# CDAI et SDAI

[conditions, sources et autorisations](https://elucenia.org/fr/outils/cdai-sdai)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Articulations douloureuses (sur 28)

`tjc`

intervalle: 0–28

### Articulations gonflées (sur 28)

`sjc`

intervalle: 0–28

### Évaluation globale par le patient

`pga`

0 à 10 · intervalle: 0–10

### Évaluation globale par le médecin

`ega`

0 à 10 · intervalle: 0–10

### Protéine C-réactive (pour SDAI)

`pcr`

mg/dL · facultatif · intervalle: 0–30

## Édition de la méthode

SDAI/Smolen 2003 et CDAI/Aletaha 2005 : 28 articulations ; évaluations globales 0–10 ; CRP mg/dL uniquement dans SDAI

## Formule documentée

CDAI = articulations douloureuses (28) + gonflées (28) + évaluation globale patient (0–10) + médecin (0–10). Étendue 0–76.

SDAI = CDAI + CRP (mg/dL). Étendue 0 à environ 86.

## Limites et population

Le SDAI de 2003 a été étudié pour l’activité et la réponse au traitement de la polyarthrite rhumatoïde, avec un compte de 28 articulations, des évaluations globales sur une échelle 0–10 et la CRP en mg/dL. Ce n’est pas un test diagnostique isolé de la polyarthrite rhumatoïde. Le CDAI sans CRP et les seuils d’activité appartiennent à leurs variantes respectives et doivent être vérifiés dans leurs sources spécifiques.

## Références

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Activité modérée selon le CDAI

| Détails du résultat | |
| --- | --- |
| SDAI | 17,2 (activité modérée) |


### 2

Rémission selon le CDAI


### 3

Activité faible selon le CDAI


### 4

Activité élevée selon le CDAI

