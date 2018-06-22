# 層次

## 組成 \(Composition\)

| Block or Linear | 文字 | 變化 | 印刷 |
| :--- | :--- | :--- | :--- |
| block | 表意文字/漢字 | 字型變化/異體字/組成\(font/variant/composition\) | |
| syllabic block | 假名 | 語形變化/小寫\(inflection/sutegana\) | furigana |
| morpho-syllabic block | 台灣字/諺文 | 變調/語形變化\(tone sandhi/inflection\) | |
| linear | 台灣字/羅馬字/諺文 | 變調/屈折性/語形變化/大小寫\(tone sandhi/inflection/letter case\) | ruby |
| linear | phonetic alphabet | 大小寫\(letter case\) | |

## 文句

| 序列 (sequence)/系列 (series) | Expression | 成份 (constituent) | 技術 (technology) | 自然語言 | 標記 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| | expression statement | | Parser | 文 \(sentence\) | |
|  | | | | 文節 \(clause\) | |
| | | | | phraseme | |
| 句系列 \(series of phrases\) | expression | | | 句 \(phrase\) | |
| 句序列 \(sequence of phrases\) | expression | | | | |
| | | | | 語彙素 \(lexeme\) | |
| 單語系列 \(series of words/serialized sequence of words\) | 表現式 \(expression\) | 品詞 \(part of speech\)/斷語 \(word segmentation/word break\) | Lexical Analyzer | 字 \(word\) | 大小寫, 標點符號 |
| 單語序列 \(sequence of words\) | 表現 \(expression\) | | | | |
| | | | Lexer \(for tokens\) | | |
| | | | | 語形態素 \(morpheme\) | |
| 音節系列 \(series of syllables/serialized sequence of syllables\) | expression | 接辭 \(Affix\) | Morphological Analyzer | 音節 \(syllable\) | |
| 音節序列 \(sequence of syllables\) | expression |  | | | |
| | | | | 書記素 \(grapheme\) | |
| 字母系列 \(series of letters\) | | 初聲 \(initial\)/中聲 \(medial\)/鼻聲 \(nasal\)/終聲 \(final\)/聲調標記 \(tone mark\) | Grephemic Analyzer | 字母 \(letter\) | |
| 字母序列 \(sequence of letters\) | | | | | angle brackets &lt;&gt; |
| | | | Scanner \(for characters\) | | |
| 音素序列 \(phonemic sequence of sounds\) | | | Synthesizer/Recognizer | 音素 \(phoneme\) | slashes // |
| 音標序列 \(phonetic sequence of sounds\) | | | Transcriber | 音標 \(phonetic alphabet\) | square brackets \[\] |
