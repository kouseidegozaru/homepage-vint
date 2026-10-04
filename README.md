# homepage-vint

松本市浅間温泉のネイル&トータルビューティーサロン **Vint.** と姉妹店 **grace** のランディングページです。
写真を余白なしで画面幅いっぱいに敷き、アイボリーの地に中央揃えの見出しとロゴのゴールドを効かせた、明るく上品なデザインです。

## フォント

- STIX Two Text（ロゴのベース書体）— 英数字・本文・ボタン・ラベル
- Shippori Mincho — 和文の見出し・本文
- Crimson Pro — 大きな英字見出し（Athelas の無料代替）

いずれも Google Fonts（SIL Open Font License）から読み込んでいます。

## 構成

- `index.html` — ページ本体（ヒーロー / コンセプト / ギャラリー / 代表紹介 / 店舗案内 / アクセス・予約導線）
- `css/style.css` — スタイル
- `assets/logo.jpg` — ロゴ原本（黒地）
- `assets/logo.png` — ロゴの透過版（金。原本から黒地を抜いて作成）
- `assets/logo-light.png` — ロゴの透過版（白。ヒーローの写真の上で使用）
- `assets/card.jpg` — 名刺画像（地図・連絡先の参照元）
- `assets/photos/` — 掲載写真（Instagram @vint_nail_beauty_salon の投稿から取得）
  - ヒーロー — 6秒ごとにフェードで切り替わるスライド（PC は1枚のスライドに2枚を左右に並べ、スマホは左側の1枚のみ）。組み合わせは index.html の `.hero-slide`
  - `concept-1.jpg` — コンセプト下の全幅の写真帯
  - `gallery-1.jpg` 〜 `gallery-4.jpg` — ギャラリー（4列。キャプションは index.html の figcaption）
  - `concept-2.jpg` — 代表紹介の左半分
  - `gallery-5.jpg` — 現在は未使用（フットネイル）

ビルドやバックエンドは不要です。`index.html` をブラウザで開くか、GitHub Pages などの静的ホスティングにそのまま配置してください。

## 未反映の情報

- LINE 公式アカウントのリンク（名刺のQRコードから取得できなかったため未掲載）
- 営業時間・定休日・メニュー／料金
- サロン内観・代表・各店舗の写真（Instagram の最新投稿に該当する写真がなかったため未掲載）
