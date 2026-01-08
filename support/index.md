# simpleMIDIController Support / サポート

最終更新日 / Last updated: 2026-01-07

---

## お問い合わせ / Contact
## GitHub で不具合報告 / Report on GitHub

GitHub の Issue から不具合報告・要望を受け付けています（GitHub アカウントが必要です）。  

- New issue: [Create an issue](https://github.com/hakaru/simpleMIDIController-support/issues/new/choose)
- Issues: [View all issues](https://github.com/hakaru/simpleMIDIController-support/issues)


### 注意 / Important
GitHub Issues は公開ページです。個人情報や公開したくない内容は記載しないでください。  
非公開での連絡はメールをご利用ください：support@hakaru.net

不具合報告・ご質問は、下記メールアドレスまでご連絡ください。

- Email: [support@hakaru.net](mailto:support@hakaru.net)

可能であれば、メール本文に以下を含めてください（コピーして使えます）。

- App version（アプリのバージョン）:
- iOS/iPadOS version:
- Device model:
- MIDI device model (Bluetooth MIDI):
- Steps to reproduce（再現手順）:
- Expected result（期待した結果）:
- Actual result（実際の結果）:

---

## よくある質問 / FAQ

### Q1. このアプリは何をするアプリですか？
**simpleMIDIController** は、iPhone/iPad を **MIDI コントローラ**として使用するためのアプリです。
Bluetooth MIDI、USB MIDI、または Virtual MIDI port を通じて、シンセサイザーやDAWを操作できます。

**simpleMIDIController** is a MIDI controller app for iPhone and iPad.
Control synthesizers and DAWs via Bluetooth MIDI, USB MIDI, or Virtual MIDI port.

---

### Q2. Bluetooth の許可が必要ですか？
はい。Bluetooth MIDI デバイスを **検出・接続**するために Bluetooth を使用します。  
Bluetooth の許可を拒否すると、デバイス検出や接続ができない場合があります。

Yes. The app uses Bluetooth to discover and connect to Bluetooth MIDI devices. If Bluetooth permission is denied, device discovery/connection may not work.

---

### Q3. Bluetooth 許可を拒否してしまいました。戻せますか？
iOS/iPadOS の設定から変更できます。

1. **設定** → **プライバシーとセキュリティ**  
2. **Bluetooth**（またはアプリ個別の権限画面）  
3. **simpleMIDIController** を許可

You can re-enable permission in iOS/iPadOS Settings:
1) Settings → Privacy & Security  
2) Bluetooth  
3) Enable for simpleMIDIController

※表示や項目名は OS バージョンにより多少異なる場合があります。

---

### Q4. Bluetooth MIDI デバイスが見つかりません / 接続できません
次を順にお試しください。

- iPhone/iPad の Bluetooth を一度 OFF → ON
- MIDI デバイス側の電源入れ直し、Bluetooth MIDI モードの確認
- iPhone/iPad とデバイスを近づける（干渉を避ける）
- 他アプリが同じ MIDI デバイスへ接続していないか確認
- iPhone/iPad を再起動

Try the following:
- Toggle Bluetooth OFF/ON on your iPhone/iPad  
- Restart the MIDI device and confirm it is in Bluetooth MIDI mode  
- Move devices closer to avoid interference  
- Ensure no other app is connected to the same MIDI device  
- Restart your iPhone/iPad

---

### Q5. 遅延が大きい / 途切れる
Bluetooth は環境の影響を受けます。以下が効果的なことがあります。

- 距離を短くする（1〜2m程度）
- Wi-Fi ルーターやUSB3.0ハブ等の干渉源から離す
- 低電池状態を避ける（端末・デバイス双方）
- 可能なら他のBluetooth機器を減らす

Bluetooth performance depends on the environment:
- Reduce distance (around 1–2 meters)  
- Avoid interference sources (Wi-Fi routers, USB 3.0 hubs, etc.)  
- Avoid low battery states  
- Reduce other active Bluetooth devices if possible

---

### Q6. どんな情報を送れば早く解決しますか？
以下があると調査が早くなります。

- アプリのバージョン
- iOS/iPadOS バージョン
- 端末機種
- Bluetooth MIDI デバイス名・型番
- 再現手順（できれば動画/スクショは任意）

---

## Privacy Policy / プライバシーポリシー

プライバシーポリシーはこちら：  
- [Privacy Policy / プライバシーポリシー](../privacy/)

---

## 免責 / Disclaimer

本ページおよび本アプリの情報は、予告なく変更される場合があります。  
本アプリの利用により生じた損害について、法令で認められる範囲で責任を負いかねます。

Information on this page and in the app may change without notice.  
To the extent permitted by law, we are not liable for damages resulting from use of the app.
