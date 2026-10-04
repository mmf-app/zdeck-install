# zdeck

**日本語** · [English](#english)

iPad / Android から ZBrush を操作するコントローラー。  
このリポジトリは PC 向けインストールパッケージのみ（ソースコードは含みません）。

---

## 日本語

### ダウンロード

| ファイル | 対象 |
|---------|------|
| [`zdeck-python-win-setup.exe`](../../releases/latest) | ZBrush 2026 / Windows |

バージョン番号・チェックサム: [`latest.json`](./latest.json)  
macOS / ZBrush 2022–2025（ZScript）は準備中。

### インストール

1. `zdeck-python-win-setup.exe` をダウンロード  
2. 実行（SmartScreen →「詳細情報」→「実行」）  
3. 画面の案内に従う  
4. ZBrush が開いていたら一度終了して開き直す  

### 接続

1. スマホ / タブレットを PC と同じ Wi-Fi に接続する  
2. zdeck アプリを開く  
3. PC を選ぶ（出なければ再検索、または IP 入力）  
4. 操作が届かないとき  
   - **2026**: ZBrush を再起動  
   - **2022–2025（準備中）**: Zplugin → **Start zdeck** を一度押す  

### アプリ

ストア公開予定です。

- [App Store](https://www.apple.com/jp/app-store/)
- [Google Play](https://play.google.com/store)

### 不具合

報告は [Issues](../../issues) へ。次を含めてください。

```
- OS:
- ZBrush バージョン:
- zdeck インストーラ / アプリのバージョン:
- 再現手順:
- 期待する結果:
- 実際の結果:
- 自己診断やエラーの文言（あれば）:
```

---

<a id="english"></a>

## English

Controller for ZBrush from iPad / Android.  
This repo hosts **PC install packages only** (no app source).

### Download

| File | Target |
|------|--------|
| [`zdeck-python-win-setup.exe`](../../releases/latest) | ZBrush 2026 / Windows |

Version / checksums: [`latest.json`](./latest.json)  
macOS and ZBrush 2022–2025 (ZScript): coming soon.

### Install

1. Download `zdeck-python-win-setup.exe`  
2. Run it (SmartScreen → **More info** → **Run anyway**)  
3. Follow the wizard  
4. If ZBrush was open, quit and reopen it  

### Connect

1. Connect your phone / tablet to the same Wi-Fi as the PC  
2. Open the zdeck app  
3. Select the PC (or search again / enter IP)  
4. If connected but nothing happens  
   - **2026**: restart ZBrush  
   - **2022–2025 (soon)**: Zplugin → **Start zdeck** once  

### App

Store release planned.

- [App Store](https://www.apple.com/app-store/)
- [Google Play](https://play.google.com/store)

### Issues

Report via [Issues](../../issues). Please include:

```
- OS:
- ZBrush version:
- zdeck installer / app version:
- Steps to reproduce:
- Expected result:
- Actual result:
- Self-diagnosis or error text (if any):
```
