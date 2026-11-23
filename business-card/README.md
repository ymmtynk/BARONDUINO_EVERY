# BARONDUINO EVERY PCB Business Card

## PCB名刺 — Rev.A1

公開用の表面画像は、氏名・肩書・専門分野・連絡先・アカウント情報をダミー表記に置き換えています。裏面は元の基板画像です。

## 基板名刺の表面・裏面

**表面（個人情報を匿名化）**

<a href="images/RevA1_top_anonymized.png"><img src="images/RevA1_top_anonymized.png" alt="BARONDUINO EVERY PCB名刺 Rev.A1 表面（匿名化済み）" width="400"></a>

**裏面**

<a href="images/RevA1_bottom.png"><img src="images/RevA1_bottom.png" alt="BARONDUINO EVERY PCB名刺 Rev.A1 裏面" width="400"></a>

画像をクリックすると拡大できます。基板の外形・ミシン目・配線・ロゴは元の設計画像に準拠しています。

## 実際の基板とサイズ感

![実際のHEAD・BODY基板PNGを使った100円玉・500円玉との同一縮尺比較](../assets/pcb-size-comparison.svg)

*基板は設計データから出力したPNG、硬貨は直径に基づく模式図です。すべて同一縮尺で比較しています。*

**A business card that is also a circuit board.**

BARONDUINO EVERYの設計思想を、一枚のプリント基板に凝縮したPCB名刺です。切り離せるHEADとBODY、QRコード、NFCタグ、LEDを備えています。

## 構成 — Rev.A1（設計資料）

- 外形: 91 × 55 mm、角R2.5 mm、FR-4、厚さ0.8 mm、2層
- 仕上げ: マットブラックのソルダーレジスト、白色シルク、ENIG（金色の露出銅箔）
- HEAD: Rev.A10、BODY: Rev.A3
- NFC: NT3H2111（NTAG I²C plus 1k）、基板パターンアンテナ
- LED: NFCの電界から得られる電力を利用し、通信時の点灯を意図した回路

**NFCの共振調整・LED電流・通信時の点灯は試作確認が必要です。**

## 製作資料

- [組立ガイド](assembly.md)
- [部品表](bom.md)
- [NFCの仕様と設定](nfc.md)

名刺は部品未実装でも配布されます。部品実装には微細な表面実装部品（0402、0.4 mmピッチQFN等）の作業経験・設備が必要です。

## カスタムPCB名刺という可能性

名刺の氏名・所属・連絡先などの表示内容を差し替え、HEAD・BODY・NFCの共通設計を活かした個別仕様のPCB名刺も構想できます。ただし、**現時点で受注製作サービスを提供しているという案内ではありません**。製作条件・費用・権利関係・個人情報の取り扱いは別途検討が必要です。

## プライバシーと公開範囲

表面画像は個人情報に該当する氏名・連絡先・肩書・通り名・専門分野・アカウント名を匿名化した公開用PNGです。裏面は元画像を掲載しています。製造用Gerberは公開しません。

## Trademarks

The NFC Forum Wayfinding Marks is a registered trademark owned by the NFC Forum, Inc.

Arduino is a trademark of Arduino S.r.l.
