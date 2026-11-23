# PCB Business Card — Parts List (Rev.A1)

出典: BARONDUINO_BUSINESS_CARD_RevA1_BOM.csv（設計資料）。**DNP = 実装しない部品**。

| ブロック | 主な部品 | 数量 | 備考 |
| --- | --- | ---: | --- |
| HEAD | ATmega4809 VQFN-48 | 1 | 6 × 6 mm / 0.4 mmピッチ |
| HEAD | 100 nF / 0402 | 3 | H_C1–C3 |
| HEAD | 4.7 µF / 0603 | 1 | H_C4 |
| HEAD | LED / 0402 | 1 | H_D1 |
| HEAD | 1 kΩ / 0402 | 1 | H_R1 |
| BODY | CH552G / SOP-16 | 1 | B_U1 |
| BODY | USB4085-GF-A | 1 | USB-C |
| BODY | DIPポゴピン | 5 | B_P1–P5 |
| BODY | PTC 500 mA / 1206 | 1 | B_F1 |
| BODY | PRTR5V0U2X / SOT-143 | 1 | B_D1 |
| BODY | B5819WS / SOD-323 | 1 | B_D2 |
| BODY | 表示LED / 0402 | 4 | 緑・青・橙・赤 |
| NFC | NT3H2111W0FHKH / XQFN8 | 1 | N_U1 |
| NFC | 220 nF / 0402 | 1 | N_C1 |
| NFC | 赤/橙LED / 0402 | 1 | N_D1、Vf ≤ 2 Vの想定 |
| NFC | 抵抗 / 0402 | 1 | N_R1、約330 Ωの暫定値 |
| NFC | 同調用コンデンサ / 0402 | 0 | N_C2、DNP |

BODYには上表以外にも抵抗・コンデンサが必要です。**この表は主要部品の概要であり、発注用の完全BOMではありません。** 完全BOMの公開には元CSVの項目整合性と部品型番の確認が必要です。
