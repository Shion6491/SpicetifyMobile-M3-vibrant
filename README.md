# Shion Vibrant

M3-Vibrant の色設計と、背景画像つき透過テーマ「Shion」を統合した Spicetify テーマ。
主に Android 版 Spicetify パッチ（Morphe）での利用を想定しています。PC 版 Spicetify でも使えます。

## 特徴

- **17 のカラースキーム** — M3-Vibrant の14スキームに、Shion の Nord／Base／Light を追加
- **背景画像** — `background.jpg` を差し替えるだけで変更可能。面が半透明になり、画像が透けて見える
- **Nord は実機調整済み** — ホーム／設定／サイドタブのすべてで文字が読めるよう、text／subtext のコントラストを調整済み

## 収録スキーム

| スキーム | 系統 |
| :-- | :-- |
| `Nord` | Shion（調整済み・既定） |
| `pumpkin-dark` / `pumpkin-light` | M3-Vibrant |
| `github-dark` / `github-light` | M3-Vibrant |
| `atom-one-dark` / `atom-one-light` | M3-Vibrant |
| `rose-dark` / `rose-light` | M3-Vibrant |
| `sepia-dark` / `sepia-light` | M3-Vibrant |
| `green-dark` / `green-light` | M3-Vibrant |
| `navy-dark` / `navy-light` | M3-Vibrant |
| `Base` / `Light` | Shion |

## 使い方（Android / Morphe）

1. Spicetify Marketplace の Themes から「Shion Vibrant」を選ぶ
2. 好みのカラースキームを選ぶ

背景画像を変えたい場合は、このリポジトリの `background.jpg` を同名で差し替えて、テーマを適用し直してください。

## 注意

- Android ではテーマの効き方は「色＋背景画像」が中心です。`user.css` に含まれる PC 版向けの装飾（ホバーアニメーション等）は Android では動作しません。
- 背景画像の上では、スキームによって文字が沈む場合があります。その場合は text／subtext の値を明るめに調整してください（Nord が調整例です）。

## クレジット

- カラースキームと `user.css` の大部分は [M3-Vibrant](https://github.com/luoshenshi/M3-Vibrant)（by Kenzx / luoshenshi, MIT License）をベースにしています
- 背景画像まわりと Nord スキームは [Spicetify-shion-theme](https://github.com/Shion6491/Spicetify-shion-theme) から引き継いでいます

## License

MIT License（詳細は `LICENSE` を参照）
