## 🐌 概要

- 月毎に、日々の学習内容を簡単に記録しています

  - [2024 年 4 月分](https://github.com/kagomen/TIL/blob/main/2024-04.md)
  - [2024 年 5 月分](https://github.com/kagomen/TIL/blob/main/2024-05.md)
  - [2024 年 6 月分](https://github.com/kagomen/TIL/blob/main/2024-06.md)
  - [2024 年 7 月分](https://github.com/kagomen/TIL/blob/main/2024-07.md)
  - [2024 年 8 月分](https://github.com/kagomen/TIL/blob/main/2024-08.md)

---

## 🏃‍♀️ これまでのまとめ

## 2023 年 12 月

- プログラミング学習開始 💻
- ドットインストールで HTML, CSS, JavaScript, PHP の基礎を学習

## 2024 年 1 月

- ドットインストール「JavaScript でミニアプリをつくろう」を見ながらアプリを制作
  - CSS 部分のみオリジナル
    - [ビンゴシートアプリ](https://kagomen.github.io/BingoSheet/)
    - [カレンダーアプリ](https://kagomen.github.io/Calendar/)
    - [ストップウォッチアプリ](https://kagomen.github.io/Stopwatch/)
    - [ToDo アプリ](https://kagomen.github.io/TodoApp-js/)
- ドットインストールで React と Laravel の基礎を学習

## 2 月

- Astro と microCMS で[個人ブログ](https://kagome.pages.dev/)を制作
  - 運用せず。[Scrapbox](https://scrapbox.io/kagomen/)を継続利用中
- Udemy で React の基礎を学習

## 3 月

- 【継続】Udemy で React の基礎を学習
- 共同プロジェクト [First Contributions JA](https://github.com/kagomen/first-contributions-ja.github.io) に参加
  - チーム開発における GitHub の使い方について学ぶ
    - イシューのたて方
    - プルリク・コードレビューの方法
    - Discussions や Projects の使い方
    - テンプレートの作成方法
    - セマンティックバージョニングについて
  - 考えたことの言語化・伝え方・チームでの立ち振る舞いについて模索
  - アイデア出しは FigJam を使用した

## 4 月

- 【継続】共同プロジェクト [First Contributions JA](https://github.com/kagomen/first-contributions-ja.github.io) に参加
  - [Version1.0.0](https://github.com/first-contributions-ja/first-contributions-ja.github.io/releases/tag/v1.0.0)リリース
- JavaScript で簡単なゲームアプリを 1 から作る
  - [10 秒ストップウォッチゲーム](https://kagomen.github.io/10second-game/)
  - [15 パズルゲーム](https://kagomen.github.io/15puzzle/)

## 5 月

- JavaScript でゲームアプリを 1 から作る
  - [倉庫番ゲーム](https://kagomen.github.io/sokoban/)
    - ビット演算について学ぶ
- モダン JavaScript とその周辺技術を調査
  - Webpack, Babel, npm, Vite, TypeScript などの役割や設定ファイルの記述方法について
- React での Web API の扱い方を簡単なアプリを作りながら学ぶ
  - [Pixabay API を使った画像検索アプリ](https://pixabay-api-app.pages.dev/)
  - [Spotify API を使った音楽検索アプリ](https://spotify-api-app.pages.dev/)
- オリジナルアプリ [リブラク](https://libraku.pages.dev/) の制作に着手

## 6 月

- 【継続】オリジナルアプリ [リブラク](https://libraku.pages.dev/) の制作・v1 のリリース
  - ルーティング(React Router)について学ぶ
  - useContext を利用してキャッシュを行い、キャッシュの仕組みについて学ぶ
  - ReactQuery や useSWR を使用したキャッシュ方法について学ぶ
  - セキュアにデータを扱うために API を建てる
  - React Hook Form と Yup/Zod を使用したフォーム作成を学ぶ
  - Resend を使用したメール送信の方法を学ぶ
    - メールの仕組み（メールサーバや DNS レコードなど）について調査する
- 『プロになるための Web 技術入門』5 章まで
- 『フロントエンドの知識地図』読了

## 7 月

- 【継続】オリジナルアプリ [リブラク](https://libraku.pages.dev/) v2 の制作
  - shadcn/ui を使った UI のコンポーネント化
  - Framer Motion を使って簡単なアニメーションを実装
  - お問い合わせページに Cloudflare Turnstile を追加し、BOT からのメール防止の実装
  - Cloudflare D1, Drizzle ORM, Lucia Auth を使って認証機能を実装
  - 同一オリジンとして Cookie を扱うため、本番環境用のプロキシサーバーを functions, \_routes.json で設定
- Hono, Workers, Pages Functions を調査
- Session ID, Cookie を使った認証の方法を調査
- ハッシュ化, バリデーションについて調査
- OAuth, Open ID Connect, JWT について調査
- Basic 認証, Digest 認証, Bearer 認証について調査
- 練習用リポジトリにて、JWT のアクセストークンとリフレッシュトークンを実装（ブラックリストは未実装）
- React Query の useMutation を使った fetch 処理について調査
- Cookie の設定項目について調査
- 『Web 技術の基本』 読了

## 🚀 これからの予定

## 8 月

- 【継続】オリジナルアプリ [リブラク](https://libraku.pages.dev/) 制作・v2 リリース
  - 利用者番号登録機能の実装
  - お気に入り機能の実装
  - PWA の設定
  - メールアドレス, パスワード変更機能の実装/week3
    - メール検証コードの実装
  - Google ログインの実装/week3
  - レスポンシブデザインの実装/week4
  - リファクタリング, README の整備/week4
- 共同プロジェクト [LGTM Factory](https://github.com/lgtm-factory/lgtm-factory) の開発開始
  - コードレビューを積極的に行う
  - 調査内容を技術記事にする
  - 実装しながら Next.js, TypeScript の基本を学ぶ

## 9 月

- 就活開始
- 【継続】オリジナルアプリ [リブラク](https://libraku.pages.dev/) 制作・v3 リリース
  - 現在地取得 -> 市内の図書館の蔵書を取得
  - お気に入り一覧に図書館の予約ページをリンク
  - PA-API を使って星評価を表示
