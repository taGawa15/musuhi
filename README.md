# むすひ｜公式LP

埼玉・所沢の黄土よもぎ蒸し専門サロン「むすひ」の公式ランディングページです。
**和モダン × 濃紅** をテーマに、温かさと上質さを両立したデザインで構成された、GitHub Pages 公開用の静的サイトです。

---

## ファイル構成

```
/
├── index.html        … LP本体（HTML / CSS / JavaScript をすべて1ファイルに内包）
├── README.md         … このファイル
├── index.backup.html … 旧デザイン版バックアップ（公開時は削除可）
└── images/
    ├── logo.png             … メインロゴ（ヘッダー・フッター・最終CTAで使用）
    ├── favicon.png          … ブラウザタブ用ファビコン
    ├── apple-touch-icon.png … iOS ホーム画面アイコン
    ├── ogp.jpg              … OGP画像（SNSシェア用 1200×630）
    ├── hero.jpg             … ファーストビュー全面背景
    ├── image-02.jpg         … コンセプト写真
    ├── image-03.jpg 〜 05.jpg … メニュー3種（よもぎ蒸し / 漢方 / 発酵）
    ├── image-06.jpg / 07.jpg … ペア蒸し / 産霊蒸し
    ├── image-08.jpg 〜 10.jpg … こだわり3項目（素材 / 黄土 / 水）
    ├── image-11.jpg 〜 15.jpg … 施術の流れ 5ステップ
    ├── image-23.jpg          … 最終CTA背景
    └── image-band.jpg        … 中盤の世界観帯（フルブリード）
```

`index.html` 単体で完結する設計のため、追加のCSSファイル・JSファイルはありません。

---

## デザイン概要

| 項目 | 内容 |
|---|---|
| **テーマ** | 和モダン × 濃紅 — 夜のお社で焚かれる炭火のような、深い赤と金の温もり |
| **ベース背景** | 生成り `#F5EFE6`（純白を避け紙の温度感を演出） |
| **メインカラー（CTA）** | 濃紅 `#7A1E1E` |
| **サブカラー** | 黄土 `#C89A64` |
| **アクセント** | 金 `#D4AF37`（hairline・小アイコンのみ） |
| **女性的差し色** | 淡桜 `#F4D6D6` |
| **本文** | 墨 `#1C1C1C` |
| **見出しフォント** | Shippori Mincho / Noto Serif JP（明朝） |
| **本文フォント** | Noto Sans JP |
| **数字・英字** | Cormorant Garamond |
| **フッター・最終CTA** | 濃紅深 `#5A1414` の反転セクション |

---

## 公開方法（GitHub Pages）

### 初回セットアップ

1. GitHub で新しいリポジトリを作成（例：`musuhi-lp`）
2. このフォルダの中身（`index.html` / `README.md` / `images/`）をリポジトリにアップロード
3. リポジトリの **Settings → Pages** を開く
4. **Source** で `Deploy from a branch` を選択
5. **Branch** を `main`、フォルダを `/ (root)` に設定 → **Save**
6. 数分後 `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

### 独自ドメインを使う場合

1. リポジトリのルートに `CNAME` ファイルを追加し、ドメイン名を1行記入（例：`musuhi-yomogi.com`）
2. ドメインのDNS設定で、GitHub Pages 用の A レコード or CNAME レコードを設定
3. **Settings → Pages → Custom domain** にドメインを入力し、`Enforce HTTPS` を有効化

公式ドキュメント：[Configuring a custom domain for your GitHub Pages site](https://docs.github.com/ja/pages/configuring-a-custom-domain-for-your-github-pages-site)

### 更新時のフロー

1. ローカルで `index.html` または `images/` 配下を編集
2. `git add` → `git commit` → `git push`
3. 数分以内に公開URLに反映（CDNキャッシュの都合で5〜10分かかる場合あり）

---

## 画像差し替えガイド

各画像は `images/` 配下に**同名で上書き**すれば差し替え完了です。HTMLの修正は不要です。

### 画像一覧と推奨サイズ

| ファイル名 | 配置 | 推奨サイズ | アスペクト比 |
|---|---|---|---|
| `hero.jpg` | ファーストビュー全面背景 | 1920×1080以上 | 16:9 |
| `image-02.jpg` | コンセプトセクション | 1600×900 | 16:9 |
| `image-03.jpg` | メニュー｜よもぎ蒸し | 1200×900 | 4:3 |
| `image-04.jpg` | メニュー｜漢方よもぎ蒸し | 1200×900 | 4:3 |
| `image-05.jpg` | メニュー｜発酵よもぎ蒸し | 1200×900 | 4:3 |
| `image-06.jpg` | ペア蒸し | 1200×750 | 16:10 |
| `image-07.jpg` | 産霊蒸し（妊活ペア） | 1200×750 | 16:10 |
| `image-08.jpg` 〜 `10.jpg` | こだわり3項目 | 1200×900 | 4:3 |
| `image-11.jpg` 〜 `15.jpg` | 施術の流れ 5ステップ | 800×600 | 4:3 |
| `image-23.jpg` | 最終CTA背景 | 1920×1080 | 16:9 |
| `image-band.jpg` | 中盤の世界観帯 | 2400×840 | 横長 |
| `ogp.jpg` | SNSシェア用OG画像 | **1200×630固定** | 1.91:1 |
| `logo.png` | ヘッダー・フッター・最終CTAロゴ | 透過PNG・縦長可 | — |
| `favicon.png` | ブラウザタブアイコン | 512×512 推奨 | 1:1 |
| `apple-touch-icon.png` | iOSホーム画面アイコン | 180×180 推奨 | 1:1 |

### 写真のトーン推奨

- **暖色寄り・低彩度・浅い被写界深度**で統一すると世界観が崩れません
- 黒過ぎる写真はサイトの濃紅背景セクションに馴染まないため避ける
- 女性が主語の写真を主役に（健康系男性写真は使用しない）

---

## CTA・リンク差し替えガイド

公開前に **必ず差し替えるべき** リンク・項目を一覧化しています。

### 差し替え必須項目

| # | 場所 | 現在の値 | 差し替えるべき値 | 検索キーワード |
|---|---|---|---|---|
| 1 | **OGP `og:url`** | `https://example.com/` | 実際の公開URL | `example.com` |
| 2 | **LINE公式アカウントリンク**（フローティングCTA内） | `href="#"` (`data-placeholder="LINE公式URL未設定"`) | LINE公式アカウントURL | `LINE公式URL未設定` |
| 3 | **お客様の声（3件）** | ダミーテキスト | 実際のレビュー文 | `ダミーテキスト` |

### 既設リンク（差し替え時のみ修正）

| 場所 | 種類 | 現在の値 |
|---|---|---|
| 予約ボタン全箇所 | 予約システム | `https://airrsv.net/musuhi-yomogi/calendar` |
| 電話ボタン全箇所 | 電話番号 | `tel:07036431133`（070-3643-1133） |
| Instagramフォローリンク | SNS | `https://www.instagram.com/musuhi_yomogi/` |
| Instagram埋め込み投稿 | 6投稿の `data-instgrm-permalink` | `instagram.com/p/...` を6件指定 |
| Googleマップ埋め込み | iframe `src` | 住所文字列ベース（API key不要） |

### エディタ一括置換キーワード

```
example.com                       … OGP og:url
airrsv.net/musuhi-yomogi/calendar … 予約システムURL
07036431133                       … 電話（tel: リンク用）
070-3643-1133                     … 電話（表示用）
musuhi_yomogi                     … Instagram ID
LINE公式URL未設定                  … LINE プレースホルダの目印
ダミーテキスト                     … お客様の声の差し替え目印
```

---

## 公開前 最終チェックリスト

公開前に以下をすべて確認してください。

### コンテンツ

- [ ] OGP `og:url` を本番URLに変更
- [ ] LINE公式アカウントURL（`href="#"` プレースホルダ）を設定
- [ ] お客様の声3件をリアルなレビューに差し替え（`ダミーテキスト` 注記も削除）
- [ ] 価格・営業時間・電話番号・住所が最新であることを確認
- [ ] Instagram埋め込み投稿6件が現役であることを確認

### 画像

- [ ] `hero.jpg` 〜 `image-23.jpg` の全画像が指定の世界観に合っているか確認
- [ ] `ogp.jpg` を 1200×630 で作成（SNSシェア時の見栄え確認）
- [ ] `favicon.png` / `apple-touch-icon.png` がブランドロゴに統一されているか確認

### 動作

- [ ] PC（Chrome / Safari / Edge / Firefox）で表示崩れなし
- [ ] スマホ（iOS Safari / Android Chrome）で表示崩れなし
- [ ] 固定予約バー（モバイル）がスクロールで出現するか
- [ ] FAQアコーディオン・モバイルメニューが開閉するか
- [ ] 全CTAボタンが意図したリンク先に飛ぶか

### SEO

- [x] `<title>` 設定済み — `むすひ｜埼玉・所沢の黄土よもぎ蒸し専門サロン｜初回体験 ¥3,000〜`
- [x] `<meta name="description">` 設定済み（約120文字）
- [x] OGP `og:type` `og:title` `og:description` `og:image` 設定済み
- [x] Twitter Card `summary_large_image` 設定済み
- [ ] **`og:url` を本番URLに差し替え（必須）**
- [ ] Search Console / Google Analytics の設置（必要に応じて）

---

## 技術的な特徴

- **フレームワーク不使用** — Vanilla HTML / CSS / JavaScript のみ（ビルド不要）
- **モバイルファースト設計** — ブレークポイント `480 / 600 / 768 / 1024 / 1280px`
- **CSS変数で全カラー管理** — `:root` 内の `--color-*` を編集すれば全体配色を一括変更可能
- **明朝体（Shippori Mincho）× ゴシック体（Noto Sans JP）** の和モダンタイポグラフィ
- **IntersectionObserver** によるスクロール連動フェードイン
- **アクセシビリティ対応** — `:focus-visible` 金リング、`prefers-reduced-motion` 配慮
- **CLS対策** — 全画像に `width` / `height` 属性付与、ヒーローは `fetchpriority="high"`
- **遅延読み込み** — ヒーロー以外の画像は `loading="lazy"`

### 外部依存（GitHub Pages公開時も問題なし）

| リソース | 用途 | 必須？ |
|---|---|---|
| Google Fonts (Cormorant Garamond / Noto Sans JP / Shippori Mincho) | フォント読み込み | 推奨（オフライン化可） |
| Instagram embed.js | 投稿の埋め込み描画 | Instagram投稿表示時のみ |
| Google Maps（API key不要・iframe方式） | アクセスマップ | 任意（差し替え可） |

すべて HTTPS 配信で、GitHub Pages（HTTPS強制）と問題なく連携します。

---

## 更新時の注意点

### 文言の整合性

**料金変更時**は以下5箇所を必ず同時に更新してください：
1. ヒーローのオファー枠（`.hero-offer`）
2. 各メニューカード3つ（`.menu-card`）
3. ペアメニューカード2つ（`.pair-card`）
4. 料金一覧表（`.pricing-summary`）
5. 各CTAボタン直下のマイクロコピー

**メニューの追加・廃止時**は「メニューカード／ペアカード／料金表」の3箇所を整合させてください。

### キャッシュ対策

GitHub Pages は CDN 経由で配信されるため、画像差し替え後の反映が遅い場合があります。**ファイル名にバージョン番号**を付けると確実です：

```html
<!-- 例：キャッシュバスター -->
<img src="images/image-03.jpg?v=2">
```

### Google Fonts のオフライン化（任意）

LP は Google Fonts を CDN 経由で読み込んでいます。完全オフライン化や読み込み速度を優先する場合は、`<head>` 内の `<link>` 行を削除し、CSS変数 `--serif` / `--sans` のフォールバック（游明朝・游ゴシック）に頼る運用も可能です。

### バックアップファイル

`index.backup.html` は旧デザイン版です。本番公開時は削除してください（残っていても誤動作はしませんが、検索インデックスから除外するため `robots.txt` で `Disallow: /index.backup.html` を追加してもよいでしょう）。

### ブラウザ対応

- Chrome / Edge / Safari / Firefox（最新版）：完全対応
- iOS Safari 14+ / Android Chrome（最新版）：完全対応
- IE11：**非対応**（CSS Grid・aspect-ratio・CSS変数を使用）

---

## お問い合わせ

LP関連のご相談・修正依頼は、運営者までご連絡ください。

**むすひ｜黄土よもぎ蒸し専門サロン**
〒359-1122 埼玉県所沢市寿町25-7 CENTRAL GINZA 201
Tel. 070-3643-1133（10:00 - 20:00 / 不定休）
Instagram: [@musuhi_yomogi](https://www.instagram.com/musuhi_yomogi/)
