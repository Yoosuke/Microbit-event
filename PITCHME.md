# [Micro:bit]("http://microbit.org/")
---
### <ruby>Tutorial<rp>（</rp><rt>チュートリアル</rt><rp>）</rp></ruby>(まずはじめに使い方の説明)
![MicrobitのHPでEnglishを日本語に変更しましょう](./img/JPEG/microbit-1.jpg)
##### [http://microbit.org/](http://microbit.org/)
---
![日本語を選択](./img/JPEG/Japanese.jpg)
---
![Microbit](./img/JPEG/microbit-ja.jpg)
---
![下にスクロールして下さい](./img/JPEG/Letscode-1.jpg)
---
![Let's Codeプログラミングをしようをクリックして下さい](./img/JPEG/Letscode-2.jpg)
---
![基本をクリックして下さい。](./img/JPEG/howtouse-1.jpg)
##### 「<ruby>基本<rp>（</rp><rt>きほん</rt><rp>）</rp></ruby>」をクリックしましょう。
---
![さいしょだけをクリックして下さい。](./img/JPEG/howtouse-2.jpg)
##### 「<ruby>最初<rp>（</rp><rt>さいしょ</rt><rp>）</rp></ruby>だけ」をクリックしましょう。
---
![最初だけのブロックが出来ている](./img/JPEG/howtouse-3.jpg)
##### 次に、また「<ruby>基本<rp>（</rp><rt>きほん</rt><rp>）</rp></ruby>」をクリックしましょう。
---
![文字列を表示しよう](./img/JPEG/howtouse-4.jpg)
##### 「<ruby>文字列<rp>（</rp><rt>もじれつ</rt><rp>）</rp></ruby>を<ruby>表示<rp>（</rp><rt>ひょうじ</rt><rp>）</rp></ruby>」をクリックしましょう。
---
![ブロックをつなげよう](./img/JPEG/howtouse-5.jpg)
##### 「<ruby>文字列<rp>（</rp><rt>もじれつ</rt><rp>）</rp></ruby>を<ruby>表示<rp>（</rp><rt>ひょうじ</rt><rp>）</rp></ruby>」をドラッグして「<ruby>最初<rp>（</rp><rt>さいしょ</rt><rp>）</rp></ruby>だけ」の中に入れよう。
---
![確認しよう](./img/howto/howtouse-6.png)
##### 一回だけ「Hello!」という文字が表示されることを左のシミュレーターで<ruby>確認<rp>（</rp><rt>かくにん</rt><rp>）</rp></ruby>しよう。
---
![ブロックを削除しよう](./img/howto/howtouse-9.png)
##### 左のエリアにドラッグしてブロックを削除しよう。

---
### <ruby>LESSON<rp>（</rp><rt>レッスン</rt><rp>）</rp></ruby>1
#### <ruby>操作方法<rp>（</rp><rt>そうさほうほう</rt><rp>）</rp></ruby>は<ruby>理解<rp>（</rp><rt>りかい</rt><rp>）</rp></ruby>しましたか？
理解ができたところで、実際にmicrobitを自分の思い通りに
動かせるようにプログラムを組んでいきましょう！

---
#### ハードウェアの<ruby>紹介<rp>（</rp><rt>しょうかい</rt><rp>）</rp></ruby>：<ruby>micro:bit<rp>（</rp><rt>マイクロビット</rt><rp>）</rp></ruby>

![説明](./img/microbit_Description.png)
##### マイクロコンピュータと<ruby>入力<rp>（</rp><rt>にゅうりょく</rt><rp>）</rp></ruby>や<ruby>出力<rp>（</rp><rt>しゅつりょく</rt><rp>）</rp></ruby>を<ruby>備<rp>（</rp><rt>そな</rt><rp>）</rp></ruby>えた<ruby>基盤<rp>（</rp><rt>きばん</rt><rp>）</rp></ruby>です。
---
#### <ruby>取扱<rp>（</rp><rt>とりあつか</rt><rp>）</rp></ruby>いの<ruby>注意点<rp>（</rp><rt>ちゅういてん</rt><rp>）</rp></ruby>！ 濡れた手でさわらない

![濡れた手で触るな](http://4.bp.blogspot.com/-ip5liN2Rt1M/WOsvxwQmoBI/AAAAAAABDs0/-ACD8WfMG9gz4YM-UOFSxbvSwoEgVJTUACLcB/s800/hand_dryer_paper.png)
---
#### <ruby>micro:bit<rp>（</rp><rt>マイクロビット</rt><rp>）</rp></ruby>の<ruby>機能紹介<rp>（</rp><rt>きのうしょうかい</rt><rp>）</rp></ruby>⑴ LED
![LED](./img/microbit_LED.png)
#####  <ruby>LED<rp>（</rp><rt>エル イー ディー</rt><rp>）</rp></ruby>:は<ruby>発行<rp>（</rp><rt>はっこう</rt><rp>）</rp></ruby>ダイオード(Light Emitting Diode)という意味です。Micro:bitには25個のLEDがあり、これを使って数字や文字を表現してます。
---
### LESSON1 の目的

- LEDの表示を自分の意図した通りに表現する。
- 「最初だけ」「ずっと」「ミリ秒」を理解する。
- プログラムをmicro:bitに入れて動かす。

---
#### Micro:bitのLEDを制御して色々な表示をしよう
![LED](./img/howto/howtouse-8.png)
##### 「基本」→「ずっと」を<ruby>選<rp>（</rp><rt>えら</rt><rp>）</rp></ruby>んでクリックします。
---
#### アイコンを表示しよう

![アイコンを表示](./img/LESSON1/LESSON-1-1.png)

##### 「アイコンを表示」を選んで「ずっと」ブロックの中に入れ、アイコンをクリックして好きなアイコンを表示するプログラムを作りましょう。
---
### プログラムとは

プログラムは、コンピュータを動かす為に「いつ」「どうする」を書いた命令書みたいなものだよ。

![プログラムとは](./img/LESSON1/LESSON-1-2.png)
---
### やってみよう!
#### ハートがドキドキするアニメーションを作ってみよう！
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;">
<iframe style="display: block; margin: 0px auto;position:absolute;top:0;left:0;width:60%;height:60%;" src="https://makecode.microbit.org/---run?id=_E862qX8ACXFf" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="1"></iframe>
</div>

---
### ヒント

![利用するブロック](./img/LESSON1/LESSON-1-3.png)

---
### プログラムに名前をつけよう。
![名前をつける](./img/LESSON1/LESSON-1-4.png)
- 「クリック」
- 「delete」キーで「題名未設定」を削除
- 「Heart」と入力します。
---
### プログラムを保存しよう。
![保存する](./img/LESSON1/LESSON-1-5.png)
- 上をクリックするとプログラムファイルがダウンロードフォルダに保存される。
---
### プログラムをMicro:bitに入れて動かして見よう！
![保存先](./img/LESSON1/LESSON-1-6.png)

---
### LESSON2 の目的

- 入力条件について理解する
- 変数の使い方が分かる
---

### ボタンを使って、表示する数値を変えてみよう。
![LESSON2-1](./img/LESSON2/LESSON2-1.png)
---
### Aボタンを押すと「0を表示する」を作る

![LESSON2-2](./img/LESSON2/LESSON2-2.png)

---
### 変数を使ってみよう[変数]をクリック
![LESSON2-3](./img/LESSON2/LESSON2-3.png)

---
### 「変数を０にする」をクリック
![LESSON2-4](./img/LESSON2/LESSON2-4.png)

---
### 「変数」を使って数字を表示しよう
![LESSN2-5](./img/LESSON2/LESSON2-5.png)

---
### Aボタンを押して「０」が表示された
![LESSN2-6](./img/LESSON2/LESSON2-6.png)
---
### 変数のイメージ
![LESSN2-7](./img/LESSON2/LESSON2-7.png)

---
### Bボタンを押して表示する数字を増やそう

![LESSN2-8](./img/LESSON2/LESSON2-8.png)
---
### やってみよう！

Aボタンを押すと、数字が増えて
Bボタンを押すと、数字が0になる

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:60%;height:60%;" src="https://makecode.microbit.org/---run?id=_idAh5TMpHLFs" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>
---
### ヒント
![LESSON2-9](./img/LESSON2/LESSON2-9.png)
---
