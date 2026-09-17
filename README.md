# シフト＆給与管理

GitHub Pages 用ファイルです。

## 公開手順
1. GitHubで新しいリポジトリを作成します（例: `shift-payroll`）。
2. このZIPを展開し、`index.html`、`manifest.webmanifest`、`sw.js` をリポジトリ直下へアップロードします。
3. リポジトリの **Settings → Pages** を開きます。
4. **Build and deployment** の Source を **Deploy from a branch** にします。
5. Branch を **main**、フォルダを **/(root)** にして Save します。
6. GitHub Pages に表示されたURLをiPhoneのSafariで開きます。
7. Safariの共有ボタン → **ホーム画面に追加** でアプリ風に起動できます。

## 現在の保存方式
入力データはブラウザの localStorage に保存されます。
そのため、現時点では iPhone と PC のデータは自動同期されません。
端末間同期は次の段階でデータベースを追加する必要があります。
