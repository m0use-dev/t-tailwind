# tailwind(テールウィンド)学習
## 概要
### tailwindとは
tailwindは、オープンソースのCSSフレームワーク

### メリット
- 自分で記述するCSSを減らせる
- ビルド時に使用していないCSSがビルドされない、容量を削減できる
- jsに依存しない(Bootstrapは依存あり)

### デメリット
- ビルドが必要
- HTMLのクラス記述が長くなる

***

## 環境構築
### npmの初期化
```sh
npm init -y
```

### tailwindcss
```sh
npm install -D tailwindcss
```

### tailwindcssの設定ファイル作成
```sh
npx tailwindcss init
```

### 自動ビルド
```sh
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```


## おすすめコンポーネント一覧
https://tailblocks.cc/

https://wickedblocks.dev/

## 参考サイト
### 公式サイト
https://tailwindcss.com/


### 利用者爆増中 初めてでもわかるTailwind CSS入門 基礎編
https://reffect.co.jp/html/tailwindcss-for-beginners

### チートシート
https://flowbite.com/tools/tailwind-cheat-sheet/
