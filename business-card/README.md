# BARONDUINO EVERY PCB Business Card

## PCB名刺 — Rev.A1

名刺の券面には肩書・通り名・専門分野など個人を特定し得る情報が含まれるため、**安全な公開用画像の再確認が終わるまで、表面・裏面の画像は掲載しません。**

HEADとBODYの実際の基板画像は、以下のサイズ比較図をご覧ください。

## 実際の基板とサイズ感

![実際のHEAD・BODY基板PNGを使った100円玉・500円玉との同一縮尺比較](../assets/pcb-size-comparison.svg)

*基板は設計データから出力したPNG、硬貨は直径に基づく模式図です。すべて同一縮尺で比較しています。名刺の個人情報を含む券面は掲載していません。*

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

名刺券面画像は、個人情報の除去範囲を再確認するまで公開を停止しています。氏名・連絡先だけでなく肩書、通り名、専門分野、アカウント名等も保護対象です。製造用Gerberは公開しません。

## Trademarks

The NFC Forum Wayfinding Marks is a registered trademark owned by the NFC Forum, Inc.

Arduino is a trademark of Arduino S.r.l.
