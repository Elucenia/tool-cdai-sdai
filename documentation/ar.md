<!-- ELUCENIA technical documentation · cdai-sdai · ar · no clinical/professional/rights approval -->

# CDAI وSDAI

[الشروط والمصادر والأذونات](https://elucenia.org/ar/tools/cdai-sdai)

## كيفية الاستخدام

استخدم الأداة في البوابة أو افتح index.html عبر خادم HTTP محلي. اختر اللغة، وأكمل الحقول، ثم أجرِ الحساب.

## المدخلات والوحدات

### المفاصل المؤلمة (من ٢٨)

`tjc`

النطاق: ٠–٢٨

### المفاصل المتورمة (من ٢٨)

`sjc`

النطاق: ٠–٢٨

### التقييم العام من المريض

`pga`

٠ إلى ١٠ · النطاق: ٠–١٠

### التقييم العام من الطبيب

`ega`

٠ إلى ١٠ · النطاق: ٠–١٠

### CRP (لحساب SDAI)

`pcr`

mg/dL · اختياري · النطاق: ٠–٣٠

## إصدار الطريقة

SDAI/سمولن 2003 وCDAI/أليتاها 2005: 28 مفصلًا؛ تقييمات عامة 0–10؛ CRP بوحدة mg/dL في SDAI فقط

## المعادلة الموثقة

CDAI = المفاصل المؤلمة (28) + المتورمة (28) + التقييم العام للمريض (0–10) + للطبيب (0–10). النطاق 0–76.

SDAI = CDAI + CRP (mg/dL). النطاق من 0 إلى نحو 86.

## الحدود والفئة السكانية

دُرس SDAI لعام 2003 لنشاط التهاب المفاصل الروماتويدي والاستجابة للعلاج، مع عدّ 28 مفصلًا وتقييمات عامة على مقياس 0–10 وCRP بوحدة mg/dL. ليس اختبارًا تشخيصيًا منفردًا لالتهاب المفاصل الروماتويدي. ينتمي CDAI دون CRP وعتبات النشاط إلى صِيغهما الخاصة، ويجب التحقق منها في المصادر المحددة.

## المراجع

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## إعادة إجراء الاختبارات التقنية

شغّل node test.cjs في المجلد الجذري لهذا المستودع لتكرار الحالات الاصطناعية المسجلة. تُحفظ المدخلات والنتائج المتوقعة وحدود التفاوت الأصلية. لا تُعدّ الاختبارات التقنية تحققًا سريريًا.

```sh
node test.cjs
```

يحتوي tool.json على المصادر والإصدار ونطاق المراجعة. يحتفظ examples.json بالمدخلات والنتائج المتوقعة للحالات الاصطناعية؛ ويسجل results.json النتائج التي تم الحصول عليها.

[السجل والمراجع](../tool.json) · [شيفرة JavaScript](../calculator.js) · [حالات مرجعية](../examples.json) · [results.json](../results.json)

## المراجعة وشروط الاستخدام

لم تُجرَ مراجعة سريرية مستقلة.

هذه الواجهة ترجمة أعدّها مؤلفوها، وليست إصدارًا رسميًا أو معتمدًا. لم تُجرَ مراجعة سريرية مستقلة أو مراجعة لغوية مهنية، ولم تُستكمل الموافقة على حقوق استخدام الأدوات.

نتيجة المعادلة أو التصنيف. يعتمد التفسير والتصرف ومدى الانطباق على التقييم المهني والمصدر المحدد.

## الترخيص ونسبة العمل إلى أصحابه

ينطبق Apache-2.0 على كود ELUCENIA فقط. تبقى حقوق الأدوات والمنشورات والترجمات والبيانات لأصحابها المعنيين. احتفظ بملفّي LICENSE وNOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
