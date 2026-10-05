<!-- ELUCENIA technical documentation · cdai-sdai · zh · no clinical/professional/rights approval -->

# CDAI 与 SDAI

[条件、来源与许可](https://elucenia.org/zh/tools/cdai-sdai)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 压痛关节数（28 个关节）

`tjc`

范围: 0–28

### 肿胀关节数（28 个关节）

`sjc`

范围: 0–28

### 患者总体评价

`pga`

0 至 10 · 范围: 0–10

### 医生总体评价

`ega`

0 至 10 · 范围: 0–10

### CRP（用于 SDAI）

`pcr`

mg/dL · 选填 · 范围: 0–30

## 方法版本

SDAI/Smolen 2003与CDAI/Aletaha 2005：28关节；总体评估0–10；仅SDAI含CRP mg/dL

## 已记录的公式

CDAI = 压痛关节（28）+肿胀关节（28）+患者总体评估（0–10）+医生总体评估（0–10）。范围0–76。

SDAI = CDAI + CRP（mg/dL）。范围0至约86。

## 限制与适用人群

2003年的SDAI用于研究类风湿关节炎活动度和治疗反应，包括28个关节计数、0–10量表的总体评估及以mg/dL计的CRP。它不是独立诊断类风湿关节炎的检测。无CRP的CDAI及活动度截点属于各自变体，需要在专门来源中核对。

## 参考文献

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
