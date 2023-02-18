# 上下文有關文法 (Context-Sensitive Grammar)

音節 ew 上下文敏感文法

* I 初聲子音
* V 母音
* Z 鼻音化
* F 終聲子音
* T 聲調

* 初 -> b | c | ch | g | h | j | k | kh | l | m | n | ng | p | ph | s | t | th
* 母 -> a | i | u | e | o | ur | or | er | ir | ar
* 準 -> m | n | ng
* 鼻 -> m | n | ng
* 束 -> k | p | t | kk | pp | tt
* 輕 -> h | hh
* 入 -> f | y | w | x
* 舒 -> f | y | w | x | z

## VT

Syllable -> V T
V -> 母 | 準
T -> 舒 | 空

## VZT

Syllable -> V Z T
V -> 母
Z -> 化
T -> 舒 | 空

## VF

Syllable -> V F
V -> 準
F -> 輕

## VFT

Syllable -> V F T
V -> 母
F -> 鼻 | 束 | 輕
T -> 入 | 舒 | 空
母F -> 母鼻 | 母束
鼻T -> 鼻舒
束T -> 束入
輕T -> 輕入

## VFFT

Syllable -> V F F T
V -> 母
F -> 鼻
F -> 輕
T -> 入

## VZFT

Syllable -> V Z F T
V -> 母
Z -> 化
F -> 束
T -> 入 | 空

## IVT

Syllable -> I V T
I -> 初
V -> 母
T -> 舒 | 空

## IVZT

Syllable -> I V Z T
I -> 初
V -> 母
Z -> 化
T -> 舒 | 空

## VZFT

Syllable -> V Z F T
I -> 初
V -> 母
Z -> 化
F -> 束
T -> 入 | 空

## IVFT

Syllable -> I V F T
I -> 初
V -> 母
F -> 鼻 | 束 | 輕
T -> 入 | 舒 | 空
母F -> 母鼻 | 母束
鼻T -> 鼻舒
束T -> 束入
輕T -> 輕入

## IVFFT

Syllable -> I V F F T
I -> 初
V -> 母
F -> 鼻
F -> 輕
T -> 入 | 空

## IFT

Syllable -> I F T
I -> 初
F -> 鼻
T -> 入 | 空

## IFFT

Syllable -> I F F T
I -> 初
F -> 鼻
F -> 輕
T -> 入 | 空
