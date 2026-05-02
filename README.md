# むすひ｜LP

埼玉・所沢の黄土よもぎ蒸し専門サロン「むすひ」の公式ランディングページです。

GitHub Pages で公開可能な、静的HTML・CSS・JavaScript 完結型のシンプルなLPです。

---

## 📁 ファイル構成

```
/
├── index.html       … LP本体（HTML / CSS / JS をすべて含む）
├── README.md        … このファイル
└── images/          … 画像ファイル一式
    ├── logo.png             … メインロゴ（白抜き）
    ├── ogp.jpg              … OGP画像（SNSシェア用）
    ├── favicon.ico          … 標準ファビコン
    ├── favicon-16.png       … ファビコン 16×16
    ├── favicon-32.png       … ファビコン 32×32
    ├── favicon-48.png       … ファビコン 48×48
    ├── apple-touch-icon.png … iOS ホーム画面アイコン
    ├── icon-192.png         … PWA アイコン
    ├── icon-512.png         … PWA アイコン
    ├── hero.jpg             … ファーストビュー背景
    ├── image-02.jpg         … コンセプト写真
    ├── image-03.jpg         … メニュー｜よもぎ蒸し
    ├── image-04.jpg         … メニュー｜漢方よもぎ蒸し
    ├── image-05.jpg         … メニュー｜発酵よもぎ蒸し
    ├── image-06.jpg         … ペア蒸し
    ├── image-07.jpg         … 産霊蒸し（妊活ペア）
    ├── image-08.jpg         … こだわり①素材
    ├── image-09.jpg         … こだわり②黄土
    ├── image-10.jpg         … こだわり③お水
    ├── image-11.jpg         … 流れ①ご来店
    ├── image-12.jpg         … 流れ②カウンセリング
    ├── image-13.jpg         … 流れ③よもぎの調合
    ├── image-14.jpg         … 流れ④お着替え
    ├── image-15.jpg         … 流れ⑤蒸し体験
    ├── image-16.jpg 〜 21.jpg … Instagram風グリッド6枚
    ├── image-22.jpg         … アクセス（入口 or 地図）
    ├── image-23.jpg         … 最終CTA背景
    └── image-band.jpg       … 中盤のフルブリード帯
```

---

## 🚀 公開方法（GitHub Pages）

### 初回セットアップ

1. GitHubで新しいリポジトリを作成（例：`musuhi-yomogi-lp`）
2. このフォルダの中身（`index.html` / `README.md` / `images/`）をリポジトリにアップロード
3. リポジトリの **Settings → Pages** を開く
4. **Source** で `Deploy from a branch` を選択
5. **Branch** を `main`（または `master`）／フォルダを `/ (root)` に設定
6. **Save** をクリック
7. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

### 独自ドメインを使う場合

1. リポジトリのルートに `CNAME` ファイルを追加し、ドメイン名（例：`www.musuhi-yomogi.com`）を1行記入
2. ドメインのDNS設定で、`A` レコードまたは `CNAME` レコードをGitHub Pagesに向ける
3. **Settings → Pages → Custom domain** にドメインを入力し、`Enforce HTTPS` を有効化

公式ドキュメント：[Configuring a custom domain for your GitHub Pages site](https://docs.github.com/ja/pages/configuring-a-custom-domain-for-your-github-pages-site)

### 更新時

1. ローカルで `index.html` または `images/` 配下のファイルを編集
2. `git commit` → `git push` で反映
3. 数分以内に公開URLに反映されます（キャッシュの都合で5〜10分かかる場合あり）

---

## 🖼️ 画像差し替え箇所

各画像は `images/` フォルダに同名で上書きすれば差し替え完了です。**ファイル名は変更しないでください**（HTMLと整合が取れなくなります）。

### 写真が必要な箇所

| ファイル名 | 配置 | 推奨サイズ | 状態 |
|:---|:---|:---|:---|
| `hero.jpg` | ファーストビュー全面背景 | 1920×1080以上 (16:9) | 🟡 仮（プレースホルダ） |
| `image-02.jpg` | コンセプトセクション | 1600×900 (16:9) | 🟡 仮 |
| `image-03.jpg` | メニュー｜よもぎ蒸し | 1200×900 (4:3) | ✅ 実画像 |
| `image-04.jpg` | メニュー｜漢方よもぎ蒸し | 1200×900 (4:3) | ✅ 実画像 |
| `image-05.jpg` | メニュー｜発酵よもぎ蒸し | 1200×900 (4:3) | ✅ 実画像 |
| `image-06.jpg` | ペア蒸し | 1200×750 (16:10) | ✅ 実画像 |
| `image-07.jpg` | 産霊蒸し（妊活ペア） | 1200×750 (16:10) | ✅ 実画像 |
| `image-08.jpg` | こだわり①素材 | 1200×900 (4:3) | 🟡 仮 |
| `image-09.jpg` | こだわり②黄土 | 1200×900 (4:3) | 🟡 仮 |
| `image-10.jpg` | こだわり③お水 | 1200×900 (4:3) | ✅ 実画像（要高解像度版差替推奨） |
| `image-11.jpg` 〜 `image-15.jpg` | 施術の流れ 5ステップ | 800×600 (4:3) | 🟡 仮 |
| `image-16.jpg` 〜 `image-21.jpg` | Instagram風グリッド 6枚 | 1080×1080 (1:1) | 🟡 仮 |
| `image-22.jpg` | アクセス（入口写真 or 地図） | 1200×900 (4:3) | 🟡 仮 |
| `image-23.jpg` | 最終CTA背景 | 1920×1080 (16:9) | 🟡 仮 |
| `image-band.jpg` | 中盤の世界観帯 | 2400×840 (横長) | 🟡 仮 |
| `ogp.jpg` | SNSシェア用OG画像 | 1200×630 | ✅ ロゴ入り |
| `logo.png` | ロゴ（白抜きPNG・透過） | 1738×2299 | ✅ |

### 差し替え時の注意点

- **JPEGで保存**（透過が必要な場合のみPNG）
- **ファイル名は完全一致**で（小文字・拡張子も含む）
- 1ファイル **500KB以下** を目安に圧縮（[TinyJPG](https://tinyjpg.com/) などで圧縮を推奨）
- 写真の色温度は **暖色系・暗め**で統一すると世界観が崩れません

---

## 🔗 CTAリンク差し替え箇所

`index.html` 内で、外部URL・電話番号は以下の箇所にあります。実運用前に必ず確認・差し替えてください。

### ✅ 設定済み（実URL／実電話番号）

| 箇所 | 種類 | 値 |
|:---|:---|:---|
| 予約ボタン（複数箇所） | 予約システム | `https://airrsv.net/musuhi-yomogi/calendar` |
| 電話ボタン（複数箇所） | 電話番号 | `tel:07036431133`（070-3643-1133） |
| Instagramリンク | SNS | `https://www.instagram.com/musuhi_yomogi/` |

### ⚠️ 仮リンク・要差し替え

| 箇所 | 行 | 現在の値 | 差し替え必要な値 |
|:---|:---|:---|:---|
| **OGP `og:url`** | `<meta property="og:url">` | `https://example.com/` | 公開する正規URL |
| **フローティングCTA・LINE** | `.float-cta .float-line` | `href="#"`（プレースホルダ） | LINE公式アカウントURL |

### 検索＆置換のキーワード

エディタで一括置換する際は、以下のキーワードで検索すると差し替え漏れを防げます。

```
airrsv.net/musuhi-yomogi/calendar   … 予約システムURL
07036431133                         … 電話番号（tel: 用）
070-3643-1133                       … 電話番号（表示用）
example.com                         … OGP用 og:url（要変更）
musuhi_yomogi                       … Instagram ID
```

---

## ⚠️ 更新時の注意点

### 文言・コンテンツ修正時

- **料金変更時**：価格は `index.html` の以下5箇所に登場します。漏れなく更新してください。
  1. ヒーローのオファー枠
  2. 各メニューカード（3つ）
  3. ペアメニューカード（2つ）
  4. 料金一覧表（Pricing Summary）
  5. 各CTAボタンのマイクロコピー
- **メニュー追加・廃止時**：メニューカード／ペアカード／料金表の3箇所を整合させてください

### お客様の声

`<section class="voice">` 内に **3件のダミーテキスト**が入っています。実際の声に必ず差し替えてから公開してください（ダミー注記を消すのも忘れずに）。

### キャッシュ対策

GitHub Pages はCDN経由で配信されるため、画像差し替え後に反映が遅い場合があります。**ファイル名にバージョン番号**を付けると確実です：

```html
<!-- 例：キャッシュバスター付き -->
<img src="images/image-03.jpg?v=2">
```

### Google Fonts への依存

LPは Google Fonts（Noto Sans JP / Shippori Mincho）を CDN から読み込んでいます。インターネット接続必須ですが、GitHub Pages 公開環境では問題ありません。**完全オフライン化が必要な場合**は `<link>` タグを削除し、システムフォント（明朝体・ゴシック体）にフォールバックさせてください。

### ダミーテキスト・仮設定の最終チェック

公開前に以下を必ず確認してください：

- [ ] お客様の声 3件を実際のレビューに差し替え（または削除）
- [ ] OGPの `og:url` を本番URLに差し替え
- [ ] LINE公式アカウントURLに差し替え
- [ ] 仮画像（プレースホルダ）を実写真に差し替え
- [ ] 価格・営業時間・電話番号が最新であることを再確認

### ブラウザ対応

- Chrome / Edge / Safari / Firefox：最新版で動作確認済み
- iOS Safari / Android Chrome：最新版で動作確認済み
- IE11：**非対応**（CSS Grid・aspect-ratio 等が動作しません）

### パフォーマンス

- 画像はすべて `loading="lazy"`（ヒーロー除く）で遅延読み込み
- ヒーロー画像は `fetchpriority="high"` で優先読み込み
- CLS（レイアウトシフト）対策として全画像に `width` / `height` 属性を付与済み

---

## 🛠️ 技術的な特徴

- 外部フレームワーク不使用（Vanilla HTML/CSS/JS）
- モバイルファースト設計（768px / 1024px / 480px ブレークポイント）
- ダークテーマ＋ゴールドアクセント
- 明朝体（Shippori Mincho）×ゴシック体（Noto Sans JP）の和モダンタイポグラフィ
- IntersectionObserver によるスクロール連動フェードイン
- バニラJSによるFAQアコーディオン／モバイルメニュー／フローティングCTA

---

## 📞 お問い合わせ

LP関連のご相談・修正依頼は、運営者までご連絡ください。

**むすひ**
〒359-1122 埼玉県所沢市寿町25-7 CENTRAL GINZA 201
Tel. 070-3643-1133（10:00 - 20:00 / 不定休）
Instagram: [@musuhi_yomogi](https://www.instagram.com/musuhi_yomogi/)
