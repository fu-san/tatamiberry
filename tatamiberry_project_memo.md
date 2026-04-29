# 🍓 Tatamiberry プロジェクトメモ

> このファイルをくーちゃん（Claude）に渡すと、すぐに状況を把握して作業を再開できます。

---

## プロジェクト概要

**ブランド名:** Tatamiberry  
**オーナー:** ふうさん（fu-san）  
**目的:** 畳縁（たたみべり）を使ったオリジナル小物の販売・Airbnb体験ゲスト向けに、選んだ伝統文様の意味をスマホで見られるWebページを提供する  
**ターゲット:** 主に海外のAirbnbゲスト（英語表記が基本）

---

## GitHubリポジトリ

- **リポジトリ:** https://github.com/fu-san/tatamiberry
- **GitHub Pages（公開URL）:** https://fu-san.github.io/tatamiberry/
- **GitHubユーザー名:** fu-san
- **最終更新:** 2026年4月28日

---

## ページ構成（全8ページ）

| ファイル名 | 役割 | 内容 |
|---|---|---|
| `index.html` | Welcomeページ | ブランド紹介・「Choose Your Pattern」ボタンでselect.htmlへ |
| `select.html` | パターン選択ページ | 6つの文様アイコンをタップして各ページへ |
| `seigaiha.html` | 青海波ページ | 文様の意味・願い |
| `asanoha.html` | 麻の葉ページ | 文様の意味・願い |
| `shippo.html` | 七宝ページ | 文様の意味・願い |
| `ichimatsu.html` | 市松ページ | 文様の意味・願い |
| `sakura.html` | 桜ページ | 文様の意味・願い |
| `karakusa.html` | 唐草ページ | 文様の意味・願い |

---

## 各文様の内容（英語テキスト）

> **構成ルール:** 各ページは **Meaning（意味）** と **Wish（願い）** の2セクション構成。Messageセクションは廃止。

### 🌊 Seigaiha（青海波）
- **Meaning:** This pattern represents calm waves and a peaceful life.
- **Wish:** May your life flow gently like endless waves.

### 🌿 Asanoha（麻の葉）
- **Meaning:** This pattern represents growth, protection, and healthy development.
- **Wish:** May you grow strong and shine in your own way.

### ⭕ Shippo（七宝）
- **Meaning:** This pattern represents harmony, connection, and endless relationships.
- **Wish:** May wonderful connections surround you always.

### ◼ Ichimatsu（市松）
- **Meaning:** This pattern represents prosperity and the hope for a bright future.
- **Wish:** May your future be filled with joy and success.

### 🌸 Sakura（桜）
- **Meaning:** This pattern represents beauty, new beginnings, and the cycle of life.
- **Wish:** May each day bring you new happiness.

### 🌿 Karakusa（唐草）
- **Meaning:** This pattern depicts vines spreading and intertwining in all directions, and its tenacious vitality makes it an auspicious design symbolizing "longevity, prosperity, and abundant offspring."
- **Wish:** May your connections continue to grow and bring lasting happiness.

---

## デザインのポイント

- **カラー:** やさしいピンク（メイン）・グリーン（サブ）・クリーム（アクセント）
- **キャラクター:** 花凜ちゃん（はなりんちゃん）→ `hanarin_smile.png` として保存済み
- **フォント:** 丸ゴシック系・明朝体など、やさしい印象のもの
- **文様表示:** 丸い形で大きく表示してインパクトを出す
- **ページ構成の統一:** 各文様ページは「Meaning → Wish」の **2セクション構成**（旧：3セクション構成 Meaning/Wish/Message）
- **言語:** 英語メイン（日本語サブタイトル）
- **スマホサイズ:** 1080px × 1920px を基準に設計

---

## 文様ページの制作フロー（ふうさん＋くーちゃん分担）

| 担当 | 作業内容 |
|---|---|
| くーちゃん | HTML作成・文様アイコンの丸型グラデーション円を用意（文様スペースを空けておく） |
| ふうさん | Canvaで文様の画像を作り、HTMLの丸い円の上に配置して完成させる |

- 唐草（karakusa.html）の丸型アイコンは、現在グラデーションのみ（文様なし）の状態でHTMLに組み込み済み。ふうさんがCanvaで唐草文様を追加する予定。

---

## 新しい文様を追加するときのルール

1. **ファイル名:** 文様名の英語ローマ字（例: `uroko.html`, `kikkou.html`）
2. **select.html** のリストにも追加する
3. **テキスト構成:** Meaning / Wish の **2セクション**で英語で書く（Messageは不要）
4. **デザイン:** 既存ページのスタイルを踏襲（カラー・レイアウト統一）
5. **文様画像:** くーちゃんがHTML内に空の丸型グラデーション円を用意 → ふうさんがCanvaで文様を追加

---

## 追加候補の伝統文様（将来的に）

- 鱗（うろこ / Uroko）
- 亀甲（きっこう / Kikkou）
- 矢絣（やがすり / Yagasuri）
- 籠目（かごめ / Kagome）
- 麻の葉つなぎ、その他

---

## 作業の引き継ぎメモ

- GitHub Pagesは正常稼働中（https://fu-san.github.io/tatamiberry/）
- 市松（ichimatsu）のアイコンSVGを修正したコミットあり（2026/4/26）
- `karakusa.html`（個別ページ）→ GitHub上に編集済み・**未コミット**（グラデーション円のみ、文様スペースあり）
- `select.html`（一覧ページ）→ GitHub上はまだ元のまま（唐草カードの文様SVGが残っている）。次回要対応。
- Canvaテンプレート（7〜8ページ仕様書）も作成済み

---

## くーちゃんへの作業開始時のお願い

このメモと一緒に「今日やりたいこと」を教えてくれれば、すぐに作業を始められます！  
例：「karakusa.htmlをGitHubにコミットしたい」「select.htmlの唐草カードを直したい」など
