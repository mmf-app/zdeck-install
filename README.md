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

版番号・チェックサム: [`latest.json`](./latest.json)  
macOS / ZBrush 2022–2025（ZScript）は準備中。

※ GitHub の **Source code (zip)** はリポジトリのコピーです。インストールには使いません。

### インストール

1. `zdeck-python-win-setup.exe` をダウンロード  
2. 実行（SmartScreen →「詳細情報」→「実行」）  
3. 画面の案内に従う（自己診断失敗時はインストール失敗）  
4. ZBrush が開いていたら一度終了して開き直す  

Python の別途インストールは不要。

### 接続

1. スマホ / タブレットを PC と同じ Wi-Fi にする  
2. zdeck アプリを開く  
3. PC を選ぶ（出なければ再検索、または IP 入力）  
4. 操作が届かないとき  
   - **2026**: ZBrush を再起動  
   - **2022–2025（準備中）**: Zplugin → **Start zdeck** を一度押す  

### アプリ

ストア公開準備中。それまでは開発ビルドを利用（手順は開発リポジトリ参照）。

### 不具合

Issues に ZBrush の版・OS・自己診断の文言を添えてください。

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

\* GitHub **Source code (zip)** is just a repo archive — not the installer.

### Install

1. Download `zdeck-python-win-setup.exe`  
2. Run it (SmartScreen → **More info** → **Run anyway**)  
3. Follow the wizard (failed self-diagnosis = failed install)  
4. If ZBrush was open, quit and reopen it  

No separate Python install required.

### Connect

1. Phone / tablet on the same Wi-Fi as the PC  
2. Open the zdeck app  
3. Select the PC (or search again / enter IP)  
4. If connected but nothing happens  
   - **2026**: restart ZBrush  
   - **2022–2025 (soon)**: Zplugin → **Start zdeck** once  

### App

Store release in preparation. Use a development build until then (see the development repo).

### Issues

File an Issue with ZBrush version, OS, and any installer self-diagnosis text.
