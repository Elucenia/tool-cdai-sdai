<!-- ELUCENIA technical documentation · cdai-sdai · ja · no clinical/professional/rights approval -->

# CDAI・SDAI

[条件・出典・許諾](https://elucenia.org/ja/tools/cdai-sdai)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 圧痛関節数（28関節）

`tjc`

範囲: 0–28

### 腫脹関節数（28関節）

`sjc`

範囲: 0–28

### 患者による全般評価

`pga`

0 ～ 10 · 範囲: 0–10

### 医師による全般評価

`ega`

0 ～ 10 · 範囲: 0–10

### CRP（SDAI用）

`pcr`

mg/dL · 任意 · 範囲: 0–30

## 方法の版

SDAI/Smolen 2003とCDAI/Aletaha 2005：28関節、全般評価0～10、CRP mg/dLはSDAIのみ

## 記載された計算式

CDAI = 圧痛関節数（28）+腫脹関節数（28）+患者全般評価（0～10）+医師全般評価（0～10）。範囲0～76。

SDAI = CDAI + CRP（mg/dL）。範囲0～約86。

## 限界・対象集団

2003年のSDAIは、28関節の評価、0–10尺度の全般評価、mg/dLでのCRPを用いて、関節リウマチの活動性と治療反応について研究されました。関節リウマチを単独で診断する検査ではありません。CRPを含まないCDAIと活動性のカットオフは、それぞれの変法に属し、個別の出典で確認する必要があります。

## 参考文献

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
