# 動物診断

心理学のビッグファイブ（5因子モデル）をもとにした、12種類の動物に分類する性格診断Webツールです。
15問の質問に答えると、5軸スコアとレーダーチャート、相性、性格の傾向などを表示します。

- 形態：静的Webサイト（単一HTMLファイル / ビルド工程なし）
- 言語：日本語
- 外部フレームワーク不使用（バニラJS）

## ローカルで動かす

`index.html` をブラウザで開くだけで動作します。

## 公開（GitHub Pages）

リポジトリ直下に `index.html` があるので、追加のワークフローなしで公開できます。
Settings → Pages → Build and deployment → Source を「Deploy from a branch」、Branch を `main` / `/(root)` に設定して保存してください。
