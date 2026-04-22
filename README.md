# Only One Delivery — Landing Page

## ファイル構成

```
/
├── index.html                          ← メインのLP（only_one_delivery_lp.htmlをリネーム）
├── netlify.toml                        ← Netlify設定
├── only_one_delivery_2lines.svg        ← ロゴSVG
├── hero_gift.png                       ← ヒーロー背景画像
├── pexels-rdne-7580812.jpg            ← 退職祝い
├── pexels-jonathan-valdes-(...).jpg   ← 誕生日プレゼント
├── pexels-quang-vuong-(...).jpg       ← 結婚祝い
├── pexels-helenalopes-27086849.jpg    ← 出産祝い
├── candice-picard-(...).jpg           ← 記念日ギフト
├── mattia-revelant-(...).jpg          ← 卒業・入学祝い
├── pexels-mikhail-nilov-8307717.jpg   ← 長寿・敬老ギフト
└── pexels-eva-belsanova-(...).jpg     ← CTA背景
```

## デプロイ手順

### 1. GitHubリポジトリを作成
1. github.com にログイン
2. 「New repository」をクリック
3. リポジトリ名：`only-one-delivery`
4. Public を選択
5. 「Create repository」

### 2. ファイルをアップロード
1. 「uploading an existing file」をクリック
2. 全ファイルをドラッグ＆ドロップ
3. ⚠️ `only_one_delivery_lp.html` → `index.html` にリネームしてアップロード
4. 「Commit changes」

### 3. Netlifyでデプロイ
1. app.netlify.com にログイン（GitHubアカウントで）
2. 「Add new site」→「Import an existing project」
3. 「GitHub」を選択
4. `only-one-delivery` リポジトリを選択
5. Build command：空欄のまま
6. Publish directory：`.`（ドット）
7. 「Deploy site」

### 4. 独自ドメインの設定（任意）
1. Netlify管理画面 → 「Domain settings」
2. 「Add custom domain」
3. `onlyonedelivery.jp` など

## LINE URLの更新
`index.html` 内の `https://lin.ee/XXXXXXX` を
実際のLINEアカウントURLに変更してください。
