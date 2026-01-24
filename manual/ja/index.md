---
layout: default
title: "SimpleMidiController ユーザーマニュアル"
description: "SimpleMidiController - iPhone/iPad用MIDIコントローラアプリの完全ガイド"
lang: ja
---

# SimpleMidiController ユーザーマニュアル

SimpleMidiControllerへようこそ。iPhone/iPad用のMIDIコントローラアプリです。このマニュアルでは、すべての機能を説明し、MIDIセットアップを最大限に活用するお手伝いをします。

---

## 目次

1. [はじめに](#はじめに)
2. [MIDI接続](#midi接続)
3. [コントローラインターフェース](#コントローラインターフェース)
4. [設定](#設定)
5. [ヒントとコツ](#ヒントとコツ)

---

## はじめに

### 初回起動時

SimpleMidiControllerを初めて開くと、Bluetoothへのアクセス許可を求められる場合があります。これはBluetooth MIDI接続に必要です。

### メイン画面の概要

メイン画面は、ライブパフォーマンスやスタジオ使用に最適な直感的なMIDIコントロールを提供します。

---

## MIDI接続

SimpleMidiControllerは3つの接続方法をサポートしています：

### Bluetooth MIDI

1. MIDIデバイスがBluetooth MIDIペアリングモードになっていることを確認
2. SimpleMidiControllerを開く
3. アプリが利用可能なBluetooth MIDIデバイスを検出
4. タップして接続

**Bluetoothのトラブルシューティング：**
- iPhone/iPadのBluetoothをOFF→ONに切り替え
- MIDIデバイスを再起動
- 干渉を避けるためデバイスを近づける
- 他のアプリが同じMIDIデバイスに接続していないか確認

### USB MIDI

以下を使用してUSB MIDIデバイスに接続：
- Lightning to USBカメラアダプタ（古いiPhone/iPad用）
- USB-C（新しいデバイス用）

USB MIDIデバイスは接続時に自動的に検出されます。

### Virtual MIDI

同じデバイス上の他のアプリにMIDIを送信：
1. 設定でVirtual MIDIを有効化
2. ターゲットアプリ（DAW、シンセアプリなど）でMIDI入力として「SimpleMidiController」を選択

---

## コントローラインターフェース

### コントロールの種類

SimpleMidiControllerは様々なユースケースに対応するコントロールタイプを提供：

- **ボタン**: ノートオン/オフまたはコントロールチェンジメッセージを送信
- **スライダー**: 連続的なコントロールチェンジ値を送信
- **パッド**: ベロシティ感度付きトリガー

### カスタマイズ

各コントロールで以下を設定可能：
- MIDIチャンネル（1-16）
- コントロール番号またはノート
- 値の範囲

---

## 設定

### MIDI設定

- **MIDIチャンネル**: すべてのコントロールのデフォルトチャンネル
- **ベロシティカーブ**: 応答感度の調整
- **Virtual MIDI**: Virtual MIDIポートの有効/無効

### Bluetooth設定

- **自動接続**: 最後に使用したデバイスに自動的に再接続
- **デバイスリスト**: ペアリング済みBluetooth MIDIデバイスの表示と管理

---

## ヒントとコツ

### 最高のパフォーマンスのために

1. **Bluetoothを賢く使う**: 最高のレイテンシーのためにデバイス間を1〜2メートル以内に
2. **干渉を減らす**: Wi-Fiルーターやなど3.0ハブから離れる
3. **バッテリーをチェック**: どちらかのデバイスの低バッテリーはBluetoothパフォーマンスに影響
4. **未使用アプリを閉じる**: 安定性向上のためシステムリソースを確保

### トラブルシューティング

**Bluetoothデバイスが見つからない**
- デバイスがペアリングモードになっていることを確認
- iPhone/iPadのBluetoothをOFF→ONに切り替え
- MIDIデバイスを再起動
- 他のアプリがデバイスを使用していないか確認

**レイテンシーが高い**
- デバイス間の距離を縮める
- 干渉源を避ける
- 最低レイテンシーにはUSB MIDIを使用

**許可が拒否された**
- iOS設定 → プライバシーとセキュリティ → Bluetoothに移動
- SimpleMidiControllerの許可を有効化

---

## サポート

お困りですか？[サポートページ](/support/)をご覧いただくか、support@hakaru.netまでお問い合わせください。

---

*SimpleMidiController - 音楽をコントロール。*
