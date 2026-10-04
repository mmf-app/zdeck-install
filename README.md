# zdeck

iPad / Android から ZBrush を操作するコントローラー用の **導入リポジトリ** です。  
アプリ本体やプラグインのソースはここにはありません。インストール用パッケージだけを置きます。

## いま使えるもの

| パッケージ | 対象 | 入手 |
|-----------|------|------|
| `zdeck-python-win-setup.exe` | ZBrush 2026 / Windows | [Releases](../../releases/latest) |

macOS 用 Python 版と、Python のない ZBrush 2022–2025（ZScript）版は準備中です。

最新の版番号とファイル名は [`latest.json`](./latest.json) を見てください。

## Windows（ZBrush 2026）

1. [Releases](../../releases/latest) から `zdeck-python-win-setup.exe` をダウンロードする
2. 実行する（未署名のときは SmartScreen で「詳細情報」→「実行」）
3. 画面の案内に従う（自己診断に失敗したらインストールは成功扱いになりません）
4. ZBrush を再起動する（インストール中に ZBrush が開いていたら、一度終了してから開き直す）

システムに Python を入れる必要はありません。インストーラに embeddable CPython が入っています。

## アプリからつなぐ

1. スマホ / タブレットを **PC と同じ Wi-Fi** にする
2. zdeck アプリを開く
3. 表示されたホストを選ぶ。出なければ再検索、または PC の IP を入力する
4. つながっても操作が届かないときは:
   - **ZBrush 2026**: ZBrush を一度終了して起動し直す
   - **ZBrush 2022–2025（ZScript）**: Zplugin → **Start zdeck** を一度押す

## アプリ

モバイルアプリはストア公開準備中です。開発ビルドの手順は開発リポジトリ側のドキュメントを参照してください。

## 問題が起きたとき

インストーラや接続の不具合は、このリポジトリの Issues に ZBrush の版・OS・自己診断の文言を添えてください。
