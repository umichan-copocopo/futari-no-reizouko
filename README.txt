# ふたりの冷蔵庫（試作版）

## 内容
- 週間献立、買い物リスト、食品在庫、日用品メモ
- 入力やチェックなどの操作に対応
- 現時点では端末ごとのブラウザ内に保存されます。複数端末間の共有はまだありません。
- ホーム画面への追加用のPWAファイルを含みます。

## GitHub Pagesへの公開
1. GitHubで新しいリポジトリを作成（PublicでOK。秘密情報は入れない）。
2. このフォルダ内のファイル（index.html, manifest.json, sw.js, icon.svg）をリポジトリ直下にアップロード。
3. Settings → Pages → Build and deployment → Deploy from a branch → Branch: main / Folder: /(root) → Save。
4. 表示されたURLをSafariで開く。

## 注意
Firebaseの設定や認証情報はまだ含みません。共有機能を追加する際は、データベースのルールを設定してから接続します。
