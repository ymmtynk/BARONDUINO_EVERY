# Hardware — HEAD / BODY

**設計資料に基づく概要（試作検証前の項目を含みます）**

## HEAD — Rev.A10

- MCU: Microchip ATmega4809、VQFN-48、6 × 6 mm、0.4 mmピッチ
- 電源: 5 V
- 側面端子: 24端子（2.54 mm系の接続を想定）
- 裏面接点: 5点（+5V、RX、TX、GND、UPDI）
- LED: D13経由
- 開発・書き込み時はBODYと接続

## BODY — Rev.A3

- CH552GによるUSB通信・SerialUPDIインターフェース
- USB Type-C
- 5個のポゴピンによるHEAD接続
- 基板寸法: 31 × 28 × 1.6 mm（設計資料）
- PWR / HEAD / PROG / MON表示LED

HEADとBODYの端子接続・書き込み方法は、ファームウェアと実機の確認後に詳細を掲載します。

## PCB名刺

[基板名刺の詳細](../business-card/README.md)をご覧ください。

**注記**：設計データは更新される場合があります。製造・実装の前にリビジョンを確認してください。
