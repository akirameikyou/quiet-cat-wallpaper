# 気配の猫 — 配布ページ

Androidライブ壁紙「気配の猫」の試作APKを配布するためのGitHub Pagesです。
作品リポジトリとは分けて、配布物（APK）だけをここに置いています。

- 公開ページ: https://akirameikyou.github.io/quiet-cat-wallpaper/
- ダウンロード: `app-debug.apk`

## 更新のしかた（差し替え）

新しいAPKができたら、同じ手順で差し替えるだけです。リンクは変わりません。

1. Android Studioで新しい `app-debug.apk` をビルドする。
2. このフォルダの `app-debug.apk` を新しいものに上書きコピーする。
3. `index.html` のバージョン表記（`試作 v0.1` と `?v=0.1`）を上げる。
4. commit して push する。

## 注意

- 署名なしのdebug版です。端末側で「提供元不明のアプリを許可」が必要です。
- 通信・広告・個人情報の収集・権限要求はありません。
