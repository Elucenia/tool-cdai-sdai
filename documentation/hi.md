<!-- ELUCENIA technical documentation · cdai-sdai · hi · no clinical/professional/rights approval -->

# CDAI और SDAI

[शर्तें, स्रोत और अनुमतियाँ](https://elucenia.org/hi/tools/cdai-sdai)

## उपयोग कैसे करें

पोर्टल पर उपकरण का उपयोग करें या स्थानीय HTTP सर्वर के माध्यम से index.html खोलें। भाषा चुनें, फ़ील्ड भरें और गणना करें।

## इनपुट और इकाइयाँ

### दर्द वाले जोड़ (28 में से)

`tjc`

सीमा: 0–28

### सूजे हुए जोड़ (28 में से)

`sjc`

सीमा: 0–28

### रोगी द्वारा समग्र आकलन

`pga`

0 से 10 · सीमा: 0–10

### चिकित्सक द्वारा समग्र आकलन

`ega`

0 से 10 · सीमा: 0–10

### CRP (SDAI के लिए)

`pcr`

mg/dL · वैकल्पिक · सीमा: 0–30

## विधि का संस्करण

SDAI/Smolen 2003 और CDAI/Aletaha 2005: 28 जोड़; समग्र आकलन 0–10; CRP mg/dL केवल SDAI में

## दस्तावेज़ित सूत्र

CDAI = दर्दयुक्त जोड़ (28) + सूजे हुए जोड़ (28) + रोगी का समग्र आकलन (0–10) + चिकित्सक का समग्र आकलन (0–10)। सीमा 0–76।

SDAI = CDAI + CRP (mg/dL)। सीमा 0 से लगभग 86।

## सीमाएँ और जनसमूह

2003 के SDAI का अध्ययन रूमेटॉइड आर्थ्राइटिस की सक्रियता और उपचार प्रतिक्रिया के लिए हुआ; इसमें 28 जोड़ों की गिनती, 0–10 पैमाने पर समग्र आकलन और mg/dL में CRP शामिल हैं। यह रूमेटॉइड आर्थ्राइटिस का अकेला निदान परीक्षण नहीं है। CRP के बिना CDAI और सक्रियता के कटऑफ़ संबंधित रूपांतरों के हैं और विशिष्ट स्रोतों में जाँचना चाहिए।

## संदर्भ

- [Smolen JS et al. A simplified disease activity index for rheumatoid arthritis for use in clinical practice. Rheumatology (Oxford), 2003.](https://doi.org/10.1093/rheumatology/keg072)

- [Aletaha D et al. Acute phase reactants add little to composite disease activity indices for rheumatoid arthritis: validation of a clinical activity score. Arthritis Res Ther, 2005.](https://doi.org/10.1186/ar1740)

- [Aletaha D, Smolen J. The Simplified Disease Activity Index (SDAI) and the Clinical Disease Activity Index (CDAI): a review of their usefulness and validity in rheumatoid arthritis. Clin Exp Rheumatol, 2005.](https://pubmed.ncbi.nlm.nih.gov/16273793/)

## तकनीकी परीक्षण दोहराएँ

दर्ज कृत्रिम मामलों को दोहराने के लिए इस रिपॉज़िटरी की मूल निर्देशिका में node test.cjs चलाएँ। मूल इनपुट, अपेक्षित परिणाम और सहनशीलता सीमाएँ सुरक्षित रखी गई हैं। तकनीकी परीक्षण नैदानिक सत्यापन नहीं हैं।

```sh
node test.cjs
```

tool.json में स्रोत, संस्करण और समीक्षा का दायरा दिया गया है। examples.json में कृत्रिम इनपुट और अपेक्षित परिणाम सुरक्षित हैं; results.json में प्राप्त परिणाम दर्ज हैं।

[रिकॉर्ड और संदर्भ](../tool.json) · [JavaScript कोड](../calculator.js) · [संदर्भ मामले](../examples.json) · [results.json](../results.json)

## समीक्षा और उपयोग की शर्तें

स्वतंत्र नैदानिक समीक्षा नहीं की गई है।

यह इंटरफ़ेस लेखकों द्वारा किया गया अनुवाद है, कोई आधिकारिक या प्रमाणित संस्करण नहीं। स्वतंत्र नैदानिक समीक्षा, पेशेवर भाषाई समीक्षा और उपकरणों के अधिकारों की अनुमति की प्रक्रिया पूरी नहीं हुई है।

सूत्र या वर्गीकरण का परिणाम। व्याख्या, कार्यवाही और उपयुक्तता पेशेवर मूल्यांकन और चुने गए स्रोत पर निर्भर है।

## लाइसेंस और श्रेय

Apache-2.0 केवल ELUCENIA के कोड पर लागू होता है। उपकरणों, प्रकाशनों, अनुवादों और डेटा के अधिकार उनके संबंधित अधिकारधारकों के पास रहते हैं। LICENSE और NOTICE सुरक्षित रखें।

ELUCENIA · Felipe Guedes · Copyright © 2026

## दर्ज किए गए परिणाम

नीचे दी गई जानकारी कृत्रिम उदाहरणों के लिए पद्धति के आउटपुट को सुरक्षित रखती है। यह स्वतंत्र नैदानिक सत्यापन नहीं है।

### 1

CDAI के अनुसार मध्यम सक्रियता

| परिणाम का विवरण | |
| --- | --- |
| SDAI | 17.2 (मध्यम सक्रियता) |


### 2

CDAI के अनुसार रोगमुक्ति


### 3

CDAI के अनुसार कम सक्रियता


### 4

CDAI के अनुसार उच्च रोग गतिविधि

