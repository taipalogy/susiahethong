# 層次 (Layers)

## 語彙

* 外語
* 外語 ew 羅馬化
* 外來語
* 漢語
* 固有語

## 組成 (Composition)

| Block or Linear | 文字 | 變化 | 印刷 |
| :--- | :--- | :--- | :--- |
| block | 表語文字/漢字 | 字型變化/異體字/組成(font/variant/composition) ||
| syllabic block | 假名/syllabary | 語形變化/小寫(inflection/sutegana) | furigana |
| morpho-syllabic block | 臺灣字/諺文 | 變調/語形變化(tone sandhi/inflection) ||
| linear | 台灣字/羅馬字/Hangul | 變調/屈折性/語形變化/大小寫(tone sandhi/inflection/letter case) | ruby |
| linear | phonetic alphabet | 大小寫(letter case) ||

## 文句

| 自然語言 | Expression | 成份 (constituent) | 技術 (technology) | 自然語言 | 標記 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 文 (sentence) | expression statement | | Parser/Syntactic Analyzer |||
| 節 (clause) ||||||
| 句 (phrase) | multiword expression | 聲調組 | | 句 (phrase)/phraseme ||
| 單語 (word)/字 | 表現式/表現 (expression) | 品詞 (part of speech)/語尾 (desinence)/屈折 (inflection)/曲用 (declension)/活用 (conjugation) | lexical analyzer/word segmentation/word break | 語彙素 (lexeme) ||
| 音節 | expression | 語幹 (stem)/接辭 (affix)/異形態 (allomorph)/combining form  | morpheme-based morphological analyzer | 語形態素 (morpheme)/語素 ||
| 字母 (letter) | | 初聲 (initial)/中聲 (medial)/終聲 (final)/聲調 (tonal)/鼻音化 (nasalization) | graphemic analyzer | 書記素 (grapheme) | angle brackets &lt;&gt; |
| 音素 (phoneme) | | | synthesizer/recognizer || slashes // |
| 音標 (phonetic alphabet) | | | transcriber || square brackets [] |
