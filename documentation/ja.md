<!-- ELUCENIA technical documentation · apgar · ja · no clinical/professional/rights approval -->

# Apgarスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/apgar)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 心拍数

`fc`

- `0` — なし
- `1` — \< 100 拍/分
- `2` — ≥ 100 拍/分

### 呼吸努力

`resp`

- `0` — なし
- `1` — 遅く不規則
- `2` — 良好，力強い啼泣

### 筋緊張

`tonus`

- `0` — 弛緩
- `1` — 多少の屈曲
- `2` — 活発な動き

### 反射反応

`reflexo`

- `0` — 反応なし
- `1` — 顔をしかめる
- `2` — 啼泣、咳、くしゃみ

### 色

`cor`

- `0` — チアノーゼまたは蒼白
- `1` — 体幹はピンク色、四肢にチアノーゼ
- `2` — 全身がピンク色

## 方法の版

Apgar 1953：5徴候0–2、AAP/ACOG 2015の1/5 minと\<7で反復

## 記載された計算式

5徴候、各0～2：心拍、呼吸努力、筋緊張、反射反応、皮膚色。合計0～10を1・5分に評価。5分で\<7なら5分ごとに20分まで反復。

## 限界・対象集団

アプガースコアは新生児の状態と蘇生への反応を記録するものです。蘇生の初期手順を決定するものではなく、仮死を診断するものでも、それだけで個人の死亡や神経学的転帰を予測するものでもありません。蘇生中に付けられたスコアは自発呼吸中のスコアと同等ではありません。早産、母体への薬剤投与、診察評価のばらつきは結果に影響し得ます。

## 参考文献

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

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

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

安心できる（7～10）


### 2

中等度異常（4～6）

5分で持続する場合は、20分齢まで5分ごとに再評価する。


### 3

安心できる（7～10）


### 4

Apgar低値（0～3）

蘇生はすでに開始されているはずである。5分時Apgar ≤ 5：臍帯血ガスを採取し、20分まで5分ごとに評価を継続する。

