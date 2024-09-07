# 設計概念

## 特點

### 用字母表示聲調

Liwiongw 音節 siongw 尾溜 chiapf burz kangw 款 ew 聲調記號 (tone letter) laiz piaufsiw 聲調. Chitf chiong 記號 ewtangy piauzsiw 台語九 ez 聲調.

Tiw 設計上 siongw 關鍵 ew 所在 tiurhw siw aiy uw 法度 hienfsiw 台語九个聲調 kahf 所有 ez 語音變異 (Sound Change), maw aiy 有法度 piaufsiw 各種 ew 語形變異 (Metaplasm).

### 聲調

聲調符號 pauzkuatf final stop consonant kahf 聲調記號 (tone letter). 聲調記號 kizsitw uw modifier letter ew 功能. 舒聲 ew 聲調符號 siw 聲調 (tonal). 入聲 ew 聲調符號 siw final stop consonant kazsiongw 聲調 (tonal).

聲調記號 long khngy tiw 音節 siongw 尾溜, maw siw khngy tiw 鼻音字母後壁. 第一調 chury 接頭辭 ew 時, 聲調記號 siw `-f`, naw siw chury 單語 hikwchiafsiw 接尾辭 tiurhw mw bien iongw 聲調記號. 第二調 siw iongw `-y` chury 聲調記號. 第三調 siw iongw `-w` chury 聲調記號. 第四調入聲 `-p`, `-t`, `-k` 本身 siw 終聲, maw siw 聲調符號 ew 一部份. 第四調輕聲 `-h` 本身 siw 終聲, maw siw 聲調符號 ew 一部份. 第五調 siw iongw `-x` chury 聲調記號. 第六調 siw iongw `-zx` chury 聲調記號. 第七調 siw iongw `-z` chury 聲調記號. 第八調入聲 `-pp`, `-tt`, `-kk` 本身 siw 終聲, maw siw 聲調符號 ew 一部份. 第八調輕聲 `-hh` 本身 siw 終聲, maw siw 聲調符號 ew 一部份. 第一調入聲 siw iongw `-f` chury 聲調記號, 第一調輕聲 maw siw iongw `-f` chury 聲調記號. 第五調入聲 siw iongw `-x` chury 聲調記號. 第五調輕聲 maw siw iongw `-x` chury 聲調記號. 第三調入聲 siw iongw `-w` chury 聲調記號. 第三調輕聲 maw siw iongw `-w` chury 聲調記號. 第九調 siw iongw -`xx` chury 聲調記號.

### 鼻音 (nasal consonant)

鼻音字母 `m`, `n`, kahf `ng` ewtangy siw 初聲, 中聲, hikwchiafsiw 終聲. Inzuiw 因 siw 子音, maw siw 準母音 (Mater Lectionis).

### 準母音 (Mater Lectionis)

參考鼻音.

### 鼻母音 (nasal vowel)

母音後壁 kazsiongw 鼻音化記號 nn. 鼻音化記號 nn siw khngy tiw nucleus 後壁，coda 頭前.

Inwui `nn` siw 二 ez `n` siurz lienzsuaw, tiysu syllable-tokenizer te cufli 字母序列 `nng` ew 時拵 ew sanfsingz chitwkua 問題. `nng` tauytuey siw behf thiahy chury `n` khahf `ng`, ahwsiw `nn` kahf `g` neh? Uw chitwlez 考慮 ew 方向 siw kaw 鼻音化記號 kai chury `nr`, anfne syllable-tokenizer te cufli `nrg` ew 時拵 tiurhw ewtangy kaw iz thiahy chury `nr` kahf `g`. Naw siw tuiy `nn` khahf `nr` long burz 滿意, tiurhw pitfsuz aiy lingwguaw kurhf cuew 符號 laiz 用.

A naw tokenizer tu tiurhw 字母序列 `ng` ew 時拵, kam behf kaw iz thiahy chury `n` khah `g` neh? Che maw siw tokenizer suziauy 注意 ew 一 ez 重點.

### 入聲

`-p`, `-t`, `-k`, kahf `-h` piaufsiw 第四調入聲 kahf 第四調輕聲. `-pp`, `-tt`, `-kk`, kahf `-hh` piaufsiw 第八調入聲 kahf 第八調輕聲. `-pf`, `-tf`, kahf `-kf` piaufsiw 第一調入聲, `-hf` piaufsiw 第一調輕聲. `-pw`, `-tw`, kahf `-kw` piaufsiw 第三調入聲. `-hw` piaufsiw 第三調輕聲. `-px`, `-tx`, kahf `-kx` piaufsiw 第五調入聲. `-hx` piaufsiw 第五調輕聲.

### 輸入法

Chitf thury 書寫系統 maw siw chitwlez 輸入法.

## 優點

### 九聲調 ew 記號

台語人機界面 pitfsuz uanzchuanz uafkhury 台語 ew 變調機制 laiz 運作. Chitf thury 書寫系統 ewtangy kaw 九个聲調 uanzchuanz 區別 kurhf suzsia 清楚.

### sikfhapw 寫程式

Inzuiw 程式 long pitfsuz aiy iongw 英語 ew alphabet 書寫. Sofi chitf thury 書寫系統 siw huizsiongz sikfhapw thehw laiz suzsia 程式. 譬喻 kong 輸入法 ew 程式, 自然語言處理 ew 程式.

### 聲調記號 maw siw 隔音符號

聲調記號 ew lingwguaw 一个功能 siw 隔音符號.

### 字母 ur kahf or ew 區別

Inzuiw 電腦語言 siw 美國人發明 ez, 大部份 ew 電腦語言教科書 long siw iongw 英語寫 ew. 程式碼 maw siw iongw 英語 chury keyword. Iongw 台語 le 書寫 kahf 電腦語言相關 ew 題目 ew 時拵, `or` chitflez 單語 ew kahf 英語 ew 單語 `or`, 電腦語言 ew "logical or", hikwchiafsiw "exclusive or" hunz buew 清楚. Sofi chitfthury 書寫系統 siw iongw "ur" laiz piaufsiw 蚵 ew 母音.

chitfthury iongw 羅馬字設計 ew 書寫系統 burz 法度 uanzchuanz 避免 uw chitwkua 單語 siw kahf 英語單語相仝, tanwsiw chifiauy ewtangy 避免 chitwkua 特定 ew keyword, tiw 使用上 tiurhw ingykaiz burz 啥乜問題.

Lingwguaw 蚵仔 maw ewtangy sia chury `urxuay`, 其中尾音節 `-uay` ew 字母 `u` siw chitwlez 過渡音. Naw siw `orxay` tiurhw burz chitflez 過渡音. 芋仔 ew `oxay` maw 無.

### ASCII-ization

Chitfthury 書寫系統 kanznaz sufiongw tiurhw 26 个英文字母 (alphabet), tiw ASCII ew 環境 maw siw kanznaz sufiongw 26 个英文字母. Sofi chitfthury 書寫系統 ewtangy tiw ASCII ew 環境使用, maw ewtangy iongw laiz sia 程式碼.

### Romanized Popular Alphabet (RPA)

RPA kaw 聲調記號 khngy tiw 音節 siongw 尾溜. 林繼雄 ew 台語現代文 chinz uw 可能 siuw tiurhw RPA ew 影響.

## 其他設計要點

### 通用 ew 標準書寫系統

Naw siw behf congy chitw ez 通用 ez 標準書寫系統, pitfsuz aiy khurfluw ifhaw 事項: 拍字利便, 手寫利便, 讀 khih laih 輕鬆, 外來語 ew 書寫, 字典順序 ew 設計, anfchuann 排版 khahf suiy, tiw 電子冊 tingfkuanx behf anfchuann 顯示 khahf 清楚.

### 鼻音化 ew 表示 (nasalization)

Chitfthury 書寫系統 siw iongw `nn` laiz piaufsiw 鼻音化. 鼻音化記號 ew 設計 ewtangy camzkhur 台灣語假名 ew 方式, tiurhw siw kaw 聲調 kapf 鼻音化記號 katf 做伙. Hikwchiafsiw sietfkey chitwlez 專用 ew 字母 laiz cuftaiw 二重音字 (digraph) `nn`. Naw siw uw 人 chuftiunnz 鼻音化記號 burz ingykaiz kahf 母音分開, tiw 設計 ew 時拵 turhw kaw 母音 sietfkey chury 兩套, 一套 siw 母音 kahf 鼻音化記號融合, 一套 siw kanznaz 母音 burz 鼻音化記號.

### 聲調 ew 標示

Anfchuann liwiongw 26 个英文字母 laiz piaufsiw 各種 ew 聲調 sufiauy tietwpietw 考慮.

### 音讀平仄 ew 標示

平調以外 ew 調 long siw 仄調. 一个書寫系統 naw siw chuanzmngz sufiongw tiw 詩詞創作 chitf 方面, iz ew tietwpietw kiongztiauw 平仄 (level tones and oblique tones/piannzcheh) ew 分別. chuanzmngz sufiongw tiw 詩詞創作 ew 書寫系統, iz ew 最高設計原則 tiurhw siw 音讀 kapf 平仄 ew 處理.

### 歌仔, 相褒歌, 南管曲音 ew 書寫

Naw siw behf thehw 台語 laiz chury 樂理上 ew 使用, ingykaiz khurfluw 啥乜欵 ew 設計 ewtangy kahf 樂理結合.

### 腔口 ew 書寫

Tiw le chury 台語學術性書寫 ew 時拵, 三不五時 tiurhw ew kaw 腔口 thehw cutflaiz 討論. Kurhf kazsiongw 台南腔, 北部腔, 南部腔等等無仝欵 ew 分別, long how 書寫系統 ew 設計 chingzkaz 一 ez 考慮 ew 因素.

* 六个母音
 * a, e, i, o, u, ur
 * a, e, i, o, u, er
* 七个母音
 * a, e, i, o, u, ur, ir

Uw 人 chuftiunnz 海語 mw siw 台灣話, inzuiw 聲調 kahf 變調 long hamw 台灣話無㒰。不管 anfchuanny, lan singz chury chitwez 記錄。

* 八个母音
 * a, e, i, o, u, ur, ir, er

### 語音辨識

台語語音辨識 ew 重點 siw 單語分割, tiurhw siw anfchuann kaw 一个一个單語辨識 cut laih. A 單語分割 ew 基礎 tiurhw siw 台語 ew 單位 aiy 詳細 kaw 規定. 譬喻 kong 啥乜 siw 一字, 啥乜 siw 一个單語, 啥乜 siw 一句, 啥乜 siw 一个片語, 啥乜是一个文, long aiy kaz 規定好勢. Ia kurhf uw 繼續調 kahf 原調 (終止調) ew 對照 maw siw aiy 斟酌處理.

### 無聲調書寫

Uw chitwkua 輸入法 ew iongw 無聲調 ew 方式 suzjipw 文字, 譬如 kong 書寫系統 chitflez 單語 ewtangy iongw `su-sia-he-thong` 輸入. Uw chitwkua 場合 siw behf kahf 韓語, 日語 chury 對照, maw ewtangy iongw 無聲調 ew 書寫型式, 譬喻 kong 韓國話 ew `hanja`, 日語 ew `kanji`, kahf 台語 ew `hanji`.

無聲調書寫 maw sikfhapw iongw laiz suzsia 南島語 kahf 外語.

### 隔音符號

chitfthury 書寫系統 siw liwiongw `-f`, `-w`, `-y`, `-x`, kahf `-z` chury 隔音符號. `-f` siw iongw chury 第二調 pieny chury 第一調 ew 接辭. `-xx` siw iongw tiw 疊音變.

Maw uw 人 kong 隔音符號 siw 界音符號. Che 二个單語 long ewtangy piaufsiw 音節 ew 隔界.

### 聲調區別性

台語 tauytuey uw 幾若个聲調 neh? I 書寫系統 ew 設計目標 laiz 決定 uw 幾个聲調. 無仝欵 ew 設計理論 kurhf kazsiongw 無仝欵 ew 設計目標 ew ingfhiong tiurhw 聲調 ew 數目.

### 南島語 kahf 外語 ew 書寫

Chitflez 區別 kahf 語源 (etymology) 有關. 一个書寫系統 behf anfchuann 區別 burzkanz 來源 ew 語彙, siw mw siw ewtangy iongw 聲調 laiz 區別. 外語 ew 書寫 behf anfchuann piaufsiw 屈折性 kahf 語尾變化.

台語內底 uw cinzciunnw 'otobai' chitf 種 ew 外來語. Sofi tiw le sietfkey 書寫系統 ew 時拵, ewtangy sunwsuay khurfluw 外語 ew 處理 kahf 書寫, kienylipw 一套符號轉換 ew 規則. 外語 kahf 固有語 ewtangy liwiongw 分別 ew 方式書寫, anfne tiw 視覺上 ewtangy 區別.

### 字辭典 ew 編排

Uw 幾个首字母 ewtangy thehw laiz 用. Behf anfchuann liwiongw chuanzpow 26 ez 字母. Anfchuann liwiongw 羅馬字 ew 特性 laiz piaufhienw 台語. Anfchuann thezsingz 查字典 ew 速度 kahf 效率.

Turhfchitwlez 聲調 mw bien iongw 聲調記號表示. Uw 人 siw 第一調 mw iongw 聲調, Uw 人 siw 第七調 mw 用. Lingwguaw kurhf ewtangy khurfluw turhfchitwlez 聲調 siw iongw chury headword.

### 字母 o, ur kahf u ew 分別

Tiw 台灣語假名內底, tuzliau `iur`, `iurh`, `ur`, kahf `urh` 以外, uw 母音 `ur` ew 音節頭前 uw chiapf 子音 `m-` ew 時拵, `ur` 會變做 `o`. 詳細 ew 變化 ewtangy khuanny 台灣語假名內底 ew 音節表.

`o` kahf `ur` ew 差別 maw aiy hunz how 清楚, iuzkiz siw tiw 頭前後壁 uw 鼻音 ew 情形下.

### 書寫方向

### 自然語言處理 (natural language processing)

啥乜欵 ew 設計 ewtangy how 軟體 khahf hur 處理台語 ew 語料 (corpus).

進前 siw 卡多人 kong 計算語言學 (computational linguistics).

### 大小寫

羅馬字 uw 大小寫 ew 區別, tanwsiw 諺文無, 漢字 kahf 假名 maw 無.

### 組成 (composition)

Siw mw siw ewtangy sia chury syllabic-block. Ewtangy camzkhur 諺文.

### 二重音字 (digraph)

Chitfthury 書寫系統 siw taiwliongw sufiongw 二重音字 laiz piaufsiw 終聲, 鼻音化記號, kahf 母音.

鼻音化記號 siw iongw `nn` 表示.

外來語 ew 部份, inzuiw 台語 burz 子音 `sh`, sofi siw iongw `s` taiwthey `sh`.

### 拍字速度

Tiwle sietfkey 書寫系統 ew 時拵, 拍字速度 siw ewtangy 考慮 ew 一个因素.

### 字體大細

Kaw 字放大縮小, anfne 字看 khih laih kam iuzuanz 好勢, kam uw 清楚.

### 聲調號碼 kam suziauy kahf alphabet ew 順序仝欵

Che siw khahf 字典 ew 編排 kahf uw 關係. 譬喻 kong, piaufsiw 第二調 ew 聲調符號 `y` kahf piaufsiw 第三調 ew 聲調符號 `w`, inz tiw alphabet 內底 ew 順序 siw `w` tiw `y` ew 頭前. 聲調 ew 順序 kahf alphabet ew 順序 ew ingfhiong 書寫系統 ew 設計.

### 漢字濫聲調

Iongw 大寫 ew 羅馬字 laizs piaufsiw 漢字, 小寫 ew 羅馬字 piaufsiw 聲調. 譬喻 kong: `HANyJIz`. Iahw siw 小寫 ew 羅馬字 piaufsiw 漢字, 大寫 ew 羅馬字 piaufsiw 聲調. 譬喻 kong: `hanYjiZ`.

### 字母 ph, th, kahf kh

Ingw tiw 外語 ew 書寫.

### 字母 d

字母 `d` siw 濁音, ingw laiz suzsia 外語 siw 無問題.

### 雙元對立 kahf 三元對立

外來語基本上 siw iongw 雙元對立 ew 方式書寫. 台語固有語 kahf 漢語 ew 部分 siw iongw 三元對立 ew 方式書寫 kurhf kazsiongw 聲調.

南島語 ew 部分 phahysngy maw siw iongw 雙元對立 ew 方式書寫.

### 第五調 kahf 第八調入聲

Inzuiw khurfluw tiurhw 無聲調 ew 場合, sofiy kaw 第三調 kahf 第五調入聲 sia chury `-h`, `-p`, `-t`, hamw `-k`. Sofiy `-hw` hamw `-hx` ew 原調 ingykaiz siw 第八調 `-hh`, `-p` siw `-pp`, `-t` siw `-tt`, `-k` siw `-kk`.

### kana kahf hangul

Le suzcutf kana kahf hangul che lngwkhuan 符號 ew 時拵, uw siurfkhua chingzca. Tiurhw siw kong kana siw 雙元對立 ez 符號. Ahf hangul siw 三元對立 ez 符號.

Inzuiw 台語 siw 三元對立 ew 語言, ewtangy camzkhur 東門正韻 ez 做法. Liwiongw 台語 ew 語頭子音 tiurhw thingyhur suzcutf tuiyingw ew hangul 符號. Naw siw uw pi 東門正韻 kurhf khahf 好 ew 做法, khahf huzhapw 現代人 ew 方式, ewtangy kurhf chaiy 修改.

### 字母 v, d, kahf q

Chimfmay ew 設計 siw iongw 字母 `v` cuftaiw 教羅字母 `p`, 字母 `d` cuftaiw 教羅字母 `t`, 字母 `q` cuftaiw 教羅字母 `k`. Nawchun kong buaix iongw 字母 `v`, `d`, kahf `q`, turhw aiy kaw 字母 `ph`, `th`, kahf `kh` 加 jib baih.

字母 `v`, `d`, kahf `q` uw chitwlez iuztiamy tiurhw siw syllable tokenizer ew khahf hur 做. Inzuiw syllable tonkenizer naw khuanny tiurhw `v`, `d`, ahwsiw `q` tiurhw chaiziann siw chitwlez 音節 ew 起頭.

字母 `v`, kahf `q` kurhf uw lingwguaw chitwchiong anzpaix, tiurhw siw kaw inz iongw tiw 聲調記號. Uw 可能 iongw 字母 q 表示第六調, 字母 v 表示第九調.

字母 `d` 目前是保留. 台語 uw tuiy 日本話吸收外來語， 其中 tiurhw uw 音素 `d` 走 jib bai 台語. 譬喻講英語 ew `dome`, `guard-rail`.

### iongw lng cuftaiw nng

Le 解析 ew 時拵, `lng` siw pi `nng` khah hur 處理. Inzuiw `nng` ew `nn` ew how 解析器 tongychury siw 鼻音化記號. 解析器 aiy tuiy `nng` chury 特別處理 chiahf ewtangy kaw iz kaifsikf chury `n` kahf `ng`. Naw 字母 `l` chury 語頭子音 tiurhw mwbien 特別處理. `lng` hamw `nng` ew 發音 kizsitw siw 仝欵 ew.

Kurhf uw chitwkua spell ew 要點 aiy 注意. 譬喻 kong, 生卵雞 siw sia churhy `sennzlngwke` ahw siw `sennznngwke`. iongw 無聲調輸入法拍字 ew 時拵 ew tu tiurhw 四个 siurz lienzsuaw ew `n`字母.

### 輕聲

輕聲 chitfez 名詞是 tuey 北京話 le kongy ew. 事實上台語 ew 輕聲 siw glottal stop, kahf 北京話 ew 輕聲無仝. 今仔 chiamwsiz chiurhy 輕聲 chitfe 名詞 laiz piaufsiw 台語 ew glottal stop.

Phahysngy thangz kai chury 切聲，英語 hurywchury cut-off tone, truncated tone, ahwsiw interruptive tone.

### 母音 er, or, ea

Burzhuatftow kuatftingw che sannz ez 字母 behf anfchuann hunzphuey how sannz ez burzkangwkhuany ew 腔口。Khuanny 台語書寫系統 ew 發展 chiahf laiz 決定。

宜蘭腔母音 "ea". Camzkhur 英國話 ew pear。
