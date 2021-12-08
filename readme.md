# lax.jsのデモ

## 環境
- gulp 4.0.2
  - sassコンパイル
  - image 圧縮
  - svg 最適化
- webpack 5.64.1
  - js バンドル 圧縮 最適化
- babel 7.16.0
  - js es6最適化
- browserSync
  - ライブリロード

## メモ
- タスクランナーはテーマに設置してあるのでテーマディレクトリで起動する
- `sudo yarn` or `npm install`で環境作成
- node_modulesがpermission errorの場合は `sudo chmod 777 [node_modulesのパス]`で権限を変更すればOK

### npm scripts
- `npm run dev` or `yarn dev` 開発モード
- `npm run build` or `yarn build` 本番モードでビルド

### gulp タスク
- `npx gulp` or `yarn gulp` gulp起動