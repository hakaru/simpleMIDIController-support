---
layout: article
title: "Virtual MIDIでアプリ間連携"
date: 2026-03-06
lang: ja
---

# Virtual MIDIでアプリ間連携

外部デバイスがなくても大丈夫。SimpleMidiControllerの**Virtual MIDI**機能を使えば、同じiPhone/iPad上の他のアプリにMIDI信号を送ることができます。

## どんな場面で使える？

- **GarageBand**や**AUM**などのDAWアプリをコントロール
- シンセサイザーアプリの音色をリアルタイム操作
- エフェクトアプリのパラメータ調整

外部ハードウェアがなくても、iPhone/iPad一台で完結するMIDIワークフローが実現します。

## 設定方法

1. SimpleMidiControllerの設定画面で**Virtual MIDI**を有効化
2. コントロール先のアプリ（DAW、シンセなど）を開く
3. そのアプリのMIDI入力設定で「**SimpleMidiController**」を選択

これだけで、SimpleMidiControllerのボタンやスライダーの操作が、ターゲットアプリにリアルタイムで反映されます。

## 活用例

**GarageBandでの使用**: SimpleMidiControllerをGarageBandのMIDI入力として設定すれば、画面上のパッドやスライダーでGarageBandの音源を演奏・コントロールできます。

**ライブパフォーマンス**: 複数のアプリを組み合わせたセットアップで、SimpleMidiControllerを統一的なコントロールサーフェスとして活用できます。

## Bluetooth/USB MIDIとの併用

Virtual MIDIは他の接続方法と同時に使用できます。たとえば、Bluetooth MIDIで外部シンセを操作しながら、同時にVirtual MIDIでiPad上のDAWにもMIDIを送る、といった使い方も可能です。

---

[App Storeでダウンロード](https://apps.apple.com/app/simplemidicontroller/id1460601046)
