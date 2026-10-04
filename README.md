# zdeck

**日本語** · [English](#english)

zdeck は、iPad / Android から ZBrush を手元で操作するためのコントローラーです。  
このページでは、PC 側に入れるソフトウェアの入手とセットアップだけを案内します（アプリ本体のソースコードはありません）。

---

## 日本語

### できること

同じ Wi-Fi 上のスマホやタブレットから、ブラシサイズやよく使う操作を ZBrush に送れます。まずは Windows + ZBrush 2026 向けのセットアップをご利用ください。

### ダウンロード

| ファイル | 対象 |
|---------|------|
| [`zdeck-python-win-setup.exe`](../../releases/latest) | ZBrush 2026 / Windows |

最新の版番号・チェックサムは [`latest.json`](./latest.json) にあります。  
macOS 版や、ZBrush 2022–2025（ZScript）向けは準備中です。

### PC へのインストール（約 2 分）

1. 上のリンクから `zdeck-python-win-setup.exe` をダウンロードします  
2. 実行します（SmartScreen が出たら「詳細情報」→「実行」）  
3. 画面の案内に従います。途中の自己診断に失敗した場合は、インストールは完了扱いになりません  
4. インストール中に ZBrush を開いていた場合は、一度終了してから開き直してください  

Python を別途入れる必要はありません。必要なランタイムはインストーラに含まれています。

### アプリからつなぐ

1. スマホ / タブレットを **PC と同じ Wi-Fi** にします  
2. zdeck アプリを開きます  
3. 表示された PC を選びます。見つからないときは再検索するか、PC の IP を入力します  
4. つながっているのに操作が届かないときは:
   - **ZBrush 2026**: ZBrush を一度終了して開き直す  
   - **ZBrush 2022–2025（準備中）**: Zplugin → **Start zdeck** を一度押す  

### モバイルアプリについて

ストア公開の準備を進めています。公開までのあいだは、開発用ビルドをご利用ください（手順は開発リポジトリ側のドキュメントを参照）。

### うまくいかないとき

Issues に、ZBrush の版・OS・インストーラに表示された自己診断の文言を添えてお知らせください。できるだけ早く確認します。

---

<a id="english"></a>

## English

zdeck lets you drive ZBrush from an iPad or Android device on the same Wi‑Fi.  
This repository is only for **PC install packages** — not the app source code.

### What you get

Control brush size and everyday ZBrush actions from your tablet or phone. The Windows + ZBrush 2026 setup is available now.

### Download

| File | For |
|------|-----|
| [`zdeck-python-win-setup.exe`](../../releases/latest) | ZBrush 2026 / Windows |

Version numbers and checksums live in [`latest.json`](./latest.json).  
macOS and ZBrush 2022–2025 (ZScript) builds are coming soon.

### Install on your PC (~2 minutes)

1. Download `zdeck-python-win-setup.exe` from the link above  
2. Run it (if SmartScreen appears, choose **More info** → **Run anyway**)  
3. Follow the wizard. If self-diagnosis fails, the install is treated as unsuccessful  
4. If ZBrush was open during install, quit it fully and open it again  

No separate Python install is required — the runtime ships inside the installer.

### Connect from the app

1. Put your phone or tablet on the **same Wi‑Fi** as the PC  
2. Open the zdeck app  
3. Pick your PC from the list (or search again / enter the PC IP)  
4. If you are connected but nothing moves in ZBrush:
   - **ZBrush 2026**: quit ZBrush and launch it again  
   - **ZBrush 2022–2025 (coming soon)**: press **Start zdeck** once under Zplugin  

### About the mobile app

We are preparing store releases. Until then, use a development build (see the development repository docs).

### Need help?

Open an Issue with your ZBrush version, OS, and any self-diagnosis text from the installer. We will take a look as soon as we can.
