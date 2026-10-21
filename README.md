# 公開写真しあげる君

学校だよりや学校ホームページに載せる写真を、プライバシーに配慮しながら加工する、**HTML単体で動く写真編集ツール**です。

- 写真のトリミング
- 全体・部分的なぼかしとモザイク（ブラシ・四角・楕円）
- 輪転機印刷を想定したモノクロ・高コントラスト・新聞風の網点加工
- 明るさ・コントラスト・網点サイズ等のスライダー調整
- JPEG / PNG / WebP で保存
- 元に戻す：Mac `⌘ Z` / Windows `Ctrl + Z`、やり直す：`⌘ Shift + Z` / `Ctrl + Shift + Z`

## 使い方

[ブラウザで使う（GitHub Pages）](https://ken-tak-steam.github.io/koukaishashin_shiagerukun/)

[HTMLファイルのダウンロード用ページ](https://ken-tak-steam.github.io/koukaishashin_shiagerukun/download.html)

[HTMLソース（GitHub）](./index.html)

`index.html` をダウンロードして、Chrome・Safari・Edgeなどで開いてください。画像データはブラウザ内で処理し、アプリから外部送信しません。外部ライブラリや通信は不要です。

GitHub Pagesをまだ有効にしていない場合、上の公開ページは表示されません。GitHubの **Settings → Pages → Deploy from a branch → main / (root) → Save** で公開できます。

## ファイル構成

- `index.html` — アプリ本体（これ1つでオフライン動作）
- `download.html` — HTMLファイルをダウンロードするページ
- `LICENSE` — 著作権・利用条件
- `README.md` — この案内

## ライセンス

© 2026 **タカクラケンタロウ（Takakura Kentaro）**。著作権は放棄しません。非営利での使用・改変・再配布は可能ですが、著作権およびライセンス条件の表示を保持してください。商用利用は別途許諾が必要です。学校や非営利団体が参加費・教材費を徴収することだけでは商用利用とはみなしません。詳細は [LICENSE](./LICENSE) をご確認ください。

## 注意

顔や名札、背景の個人情報が見えないか、**保存画像を拡大して必ず確認**してください。ぼかし・モザイクは完全な匿名化を保証しません。元写真の管理や掲載同意にもご注意ください。
