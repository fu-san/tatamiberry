# 🍓 Tatamiberry プロジェクトメモ（CLAUDE.md）

> **Claude Code用:** このフォルダでClaude Codeを起動すると、このファイルが自動で読み込まれます。
> Coworkでも同じファイルを渡せば、すぐに状況を把握して作業を再開できます。

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

## ページ構成（全12ページ）

| ファイル名 | 役割 | 内容 |
|---|---|---|
| `index.html` | Welcomeページ | ブランド紹介・「Choose Your Pattern」ボタンでselect.htmlへ |
| `select.html` | パターン選択ページ | 10の文様カードをタップして各ページへ |
| `seigaiha.html` | 青海波ページ | 文様の意味・願い |
| `asanoha.html` | 麻の葉ページ | 文様の意味・願い |
| `shippo.html` | 七宝ページ | 文様の意味・願い |
| `ichimatsu.html` | 市松ページ | 文様の意味・願い |
| `sakura.html` | 桜ページ | 文様の意味・願い |
| `karakusa.html` | 唐草ページ | 文様の意味・願い |
| `kikkou.html` | 亀甲ページ | 文様の意味・願い |
| `yabane.html` | 矢羽根ページ | 文様の意味・願い |
| `uroko.html` | 鱗ページ | 文様の意味・願い |
| `kiku.html` | 菊ページ | 文様の意味・願い |

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
- **Meaning:** A pattern of vines growing endlessly. It symbolizes prosperity, longevity, and connections that last.
- **Wish:** May your connections continue to grow and bring lasting happiness.

### 🐢 Kikkou（亀甲）
- **Meaning:** A pattern inspired by a turtle's shell. It symbolizes longevity, good health, and protection.
- **Wish:** May you be blessed with good health and a long, happy life.

### 🏹 Yabane（矢羽根）
- **Meaning:** A pattern made of arrow feathers. It symbolizes growth, moving forward, and achieving goals.
- **Wish:** May you move forward with confidence toward your dreams and goals.

### 🐟 Uroko（鱗）
- **Meaning:** A pattern inspired by fish scales. It symbolizes protection, warding off evil, and new beginnings.
- **Wish:** May you be protected from harm and blessed with a bright new future.

### 🌼 Kiku（菊）
- **Meaning:** A pattern of chrysanthemum flowers. It symbolizes nobility, longevity, and wishing for happiness.
- **Wish:** May happiness continue in your life and your heart be always fulfilled.

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

- 矢絣（やがすり / Yagasuri）
- 籠目（かごめ / Kagome）
- 麻の葉つなぎ、その他

---

## 作業の引き継ぎメモ

- GitHub Pagesは正常稼働中（https://fu-san.github.io/tatamiberry/）
- 市松（ichimatsu）のアイコンSVGを修正したコミットあり（2026/4/26）
- **ローカル完成済み（未プッシュ）:**
  - `karakusa.html` — テキスト更新済み、`karakusa_icon.png` 配置済み
  - `select.html` — 亀甲・矢羽根・鱗・菊のカード追加済み
  - `kikkou.html` / `yabane.html` / `uroko.html` / `kiku.html` — 新規作成済み
  - `kikkou_icon.png` / `yabane_icon.png` / `uroko_icon.png` / `kiku_icon.png` — Python生成済み
- **GitHub上はまだ旧バージョン** → 次回GitHubにpushが必要
- 文様アイコンPNG（1254×1254 RGBA）は `make_icons.py` で再生成可能
- Canvaテンプレート（7〜8ページ仕様書）も作成済み

---

## くーちゃんへの作業開始時のお願い

このメモと一緒に「今日やりたいこと」を教えてくれれば、すぐに作業を始められます！  
例：「karakusa.htmlをGitHubにコミットしたい」「select.htmlの唐草カードを直したい」など
