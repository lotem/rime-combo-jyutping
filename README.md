# 宮保粵拼

配方： ℞ **lotem/rime-combo-jyutping**

[Rime](https://rime.im) 輸入方案：宮保粵拼

## 簡介

[宮保拼音][1] 是由 [居戎氏][2] 設計、在標準電腦鍵盤上多鍵並擊輸入拼音的方法。

*並擊* （chord-typing）是指：同時按下鍵盤上的多個按鍵。

宮保拼音的設計思路和實現方法可推廣到古漢語和各種漢語方言。

本方案——宮保粵拼，以《[分韻撮要][3]》記錄的清初粵語聲母、韻母爲基礎，增刪音韻以適應現代粵語。

[1]: https://github.com/rime/rime-combo-pinyin
[2]: https://github.com/lotem
[3]: https://ytenx.org/pyonh/

### 指法演示

  - 〈宫保粤拼「七指禅」并击，出鞘！〉[嗶哩嗶哩](https://www.bilibili.com/video/BV1UfY3z7EUf/)

### 鍵盤佈局

「七指禪」佈局，不用小拇指，不用左手大拇指，其他七指用標準盲打指法。

    c  l  d  t     o  u -u -t
    s  h  g  k     e  i -i -k
    z  f  b  p    oe yu  m -p
               aa

右手拇指操作空格鍵，表示元音 `aa`。

`-i -u -k -t -p` 等表示韻尾。

### 並擊鍵位

聲母：

  - `f b = m`
  - `l d = n`
  - `h g = ng`

  - `s g = gw`
  - `s k = kw`
  
  - `s h = w`
  - `c l = j`
  - `z f = 零聲母`
  
輸入音節 `aa`, `m`, `ap` 須與零聲母並擊。
單擊這些韻母鍵則會輸入空格、逗號、句號。 

韻母：

  - `i -i = ei`
  - `u -u = ou`
  
韻尾：
  
  - ` m -p = -m`
  - `-u -t = -n`
  - `-i -k = -ng`
  
韻尾可與 `aa, e, o, oe/eo, i, u, yu` 等元音並擊。
若不與元音並擊，表示元音 `a` 加韻尾。

活用鍵位：

元音 `e, o, oe` 與韻尾並擊指法不便時，可改用 `aa` 與 `i, u, yu` 並擊。

  - `aa + i = e`
  - `aa + u = o`
  - `aa + yu = oe/eo`
  
鼻韻母：

`m, ng` 用對應的並擊聲母輸入。

另設有一個鼻韻母——右手半區的 `m` 鍵，可與聲母並擊，通常省略。

### 學習資料

  - [宮保拼音教程](https://github.com/rime/home/wiki/ComboPinyin)
  - [宮保拼音鍵位練習](https://rime.io/typewriter/)

    按 <kbd>ESC</kbd> <kbd>TAB</kbd> 選擇「宮保粵拼」輸入方案。

## 安裝

本方案依賴粵拼 `jyutping` 輸入方案。 

  - [粵拼](https://github.com/rime/rime-jyutping) ℞ **`jyutping`**
