# Tシャツ応募 (ハムカップ / Nコレ京都2026)

「Tシャツ応募.zip」から展開した応募デザイン画像一式です。

## 中身

`images/` フォルダに、6.jpg 〜 23.jpg の計18枚の画像が入っています。
いずれも「ハムカップ」ブランドの各種デザイン案(村の背景、キャラクター構図違いなど)で、
「Nコレ京都2026」のロゴが入っています。

## 使い方(GitHubへのアップロード手順)

1. このzipをダウンロードして展開してください。
2. GitHub上で新しいリポジトリを作成します(例: `tshirt-entry`)。
3. 展開したフォルダの中身(`README.md` と `images/`)を、作成したリポジトリのルートにそのまま追加してください。
4. ローカルでコミット & プッシュ:

   ```bash
   git init
   git add .
   git commit -m "Add T-shirt design entries"
   git branch -M main
   git remote add origin https://github.com/<あなたのユーザー名>/<リポジトリ名>.git
   git push -u origin main
   ```

   もしくはGitHubのWeb UI (「Add file」→「Upload files」) からドラッグ&ドロップでもアップロードできます。

5. プッシュ後、リポジトリの `images/` フォルダから各画像を直接見てもらえます。
