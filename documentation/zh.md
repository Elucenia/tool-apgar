<!-- ELUCENIA technical documentation · apgar · zh · no clinical/professional/rights approval -->

# Apgar 评分

[条件、来源与许可](https://elucenia.org/zh/tools/apgar)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 心率

`fc`

- `0` — 无
- `1` — \< 100 次心搏/分钟
- `2` — ≥ 100 次心搏/分钟

### 呼吸努力

`resp`

- `0` — 无
- `1` — 缓慢、不规则
- `2` — 良好，哭声响亮

### 肌张力

`tonus`

- `0` — 松弛
- `1` — 轻度屈曲
- `2` — 主动运动

### 反射反应

`reflexo`

- `0` — 无反应
- `1` — 皱眉
- `2` — 哭、咳嗽或打喷嚏

### 颜色

`cor`

- `0` — 发绀或苍白
- `1` — 躯干红润、四肢发绀
- `2` — 全身粉红

## 方法版本

Apgar 1953：5体征0–2；AAP/ACOG 2015于1/5 min随访，\<7重复

## 已记录的公式

五体征，各0至2：心率、呼吸用力、肌张力、反射应激性、肤色。总分0至10，出生1、5分钟评分；若5分钟\<7，每5分钟重复至20分钟。

## 限制与适用人群

Apgar评分记录新生儿的状况及其对复苏的反应；它不决定复苏的初始步骤，不能诊断窒息，也不能单独预测个体死亡或神经系统结局。复苏期间的评分不等同于自主呼吸时的评分。早产、母亲用药以及检查评估的变异可能影响结果。

## 参考文献

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

令人放心（7至10）


### 2

中度异常（4至6）

如果5分钟时仍持续，则每5分钟重新评估一次，直至出生20分钟。


### 3

令人放心（7至10）


### 4

Apgar低分（0至3）

复苏应已开始。5分钟时Apgar ≤ 5：采集脐血气，并每5分钟继续评估一次，直至20分钟。

