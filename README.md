# MilkTimer サポートページ / Support Pages

このディレクトリには、MilkTimerアプリのApp Store申請用サポートページとプライバシーポリシーが含まれています。

This directory contains the support pages and privacy policy for the MilkTimer app for App Store submission.

## ファイル構成 / File Structure

- `index.html` - アプリのサポートページ / App support page
- `privacy-policy.html` - プライバシーポリシー / Privacy policy
- `README.md` - このファイル / This file

## GitHub Pagesの設定方法 / GitHub Pages Setup

### 1. GitHubリポジトリにプッシュ / Push to GitHub Repository

```bash
cd /Users/akihiromac/claudecode/MilkTimer
git add Support/
git commit -m "Add support pages for App Store submission"
git push origin main
```

### 2. GitHub Pagesを有効化 / Enable GitHub Pages

1. GitHubリポジトリページにアクセス: https://github.com/ahashimoto-dev/MilkTimer
2. **Settings** タブをクリック
3. 左サイドバーから **Pages** を選択
4. **Source** セクションで以下を設定:
   - Branch: `main`
   - Folder: `/Support`
5. **Save** ボタンをクリック

### 3. 公開URLの確認 / Verify Published URL

設定後、数分以内に以下のURLでサイトが公開されます:

```
https://ahashimoto-dev.github.io/MilkTimer/
```

プライバシーポリシーページ:
```
https://ahashimoto-dev.github.io/MilkTimer/privacy-policy.html
```

### 4. App Storeでの使用 / Use in App Store

App Store Connectでアプリを登録する際、以下の情報を入力してください:

- **サポートURL / Support URL**: `https://ahashimoto-dev.github.io/MilkTimer/`
- **プライバシーポリシーURL / Privacy Policy URL**: `https://ahashimoto-dev.github.io/MilkTimer/privacy-policy.html`

## 更新方法 / How to Update

サポートページを更新する場合:

1. HTMLファイルを編集
2. 変更をコミット&プッシュ
3. GitHub Pagesが自動的に更新されます（通常数分以内）

## 注意事項 / Notes

- お問い合わせフォームのURL (`YOUR_FORM_ID`) を実際のGoogle FormのIDに置き換えてください
- App Store公開後、`index.html`のダウンロードセクションを更新してください
- プライバシーポリシーに変更があった場合は、最終更新日を更新してください

## デザイン / Design

- カラースキーム: 薄ピンクグラデーション (#FFF0F5 → #FFE4E1)
- アプリのUIと統一されたデザイン
- レスポンシブデザイン対応（モバイル・デスクトップ両対応）
- 日本語・英語バイリンガル対応

## 参考 / Reference

このサポートページは以下を参考に作成されました:
- https://ahashimoto-dev.github.io/Emo-ToDo-Support/
