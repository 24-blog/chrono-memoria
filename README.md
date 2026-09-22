[![License](https://img.shields.io/github/license/24-blog/chrono-memoria)](LICENSE)


## 過去に進む時計 (PWA)

文字通り時計の針を反転させるだけの時計アプリ。なんの役にも立ちません。

| File name | 
|---|
| `index.html` | 
| `manifest.json` | 
| `service-worker.js` | 
| `icon-192.png` |
| `icon-512.png` | 
| `icon-512-maskable.png` |
| `apple-touch-icon.png` |

GitHub Pagesにそのまま置ける構成です。リポジトリ直下(または任意のサブディレクトリ)にこれらのファイルをコピーしてください。

 - HTTPS環境(GitHub Pagesは対応済み)でないとservice workerは登録されません。
 - サブディレクトリ配下に置く場合、manifest.jsonの `start_url` / `scope` はそのままの相対パスで機能します。(index.htmlと同じ階層に置く前提)
 - 起点(E)は `localStorage` に保存されます。ブラウザ/端末別となります。(サーバー同期はしません)
 - アイコンはこの時計のデザイントークン(brass/verdigris/ink)に合わせて生成した簡易版です。


⚠️COPYRIGHT<br>
Textual commentary written by the repository owner is
licensed under CC BY-NC-ND 4.0.
