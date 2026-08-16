# zdeck

iPad / Android から ZBrush を操作するコントローラー用の **導入リポジトリ** です。  
アプリ本体やプラグインのソースはここにはありません。インストール用パッケージだけを置きます。

## いま使えるもの

| パッケージ | 対象 | 入手 |
|-----------|------|------|
| `zdeck-python-win.zip` | ZBrush 2026 / Windows | [Releases](../../releases/latest) |

macOS 用 Python 版と、Python のない ZBrush 2022–2025（ZScript）版は準備中です。

最新の版番号とファイル名は [`latest.json`](./latest.json) を見てください。

## Windows（ZBrush 2026）

1. [Releases](../../releases/latest) から `zdeck-python-win.zip` をダウンロードする
2. 展開する
3. `Install.bat` を実行する
4. 画面の案内に従う（自己診断に失敗したらインストールは成功扱いになりません）
5. ZBrush を再起動する

システムに Python を入れる必要はありません。zip に embeddable CPython が入っています。

## アプリ

モバイルアプリはストア公開準備中です。開発ビルドの手順は開発リポジトリ側のドキュメントを参照してください。

## 問題が起きたとき

インストーラや接続の不具合は、このリポジトリの Issues に ZBrush の版・OS・自己診断の文言を添えてください。
