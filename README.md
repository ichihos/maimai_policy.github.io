# まいまい京都 プライバシーポリシーサイト

まいまい京都アプリのプライバシーポリシーを公開するための静的サイトです。

## 📋 概要

このサイトは、まいまい京都アプリが収集・利用する個人情報について、ユーザーに透明性を提供するためのプライバシーポリシーページです。

## 🚀 GitHub Pages での公開方法

### 1. GitHubリポジトリの作成

```bash
# リポジトリを初期化
cd /Users/hoshos/projects/maimai_policy
git init

# ファイルを追加
git add .
git commit -m "Initial commit: Privacy policy site"

# GitHubにリポジトリを作成後、リモートを追加
git remote add origin https://github.com/[ユーザー名]/maimai_policy.git
git branch -M main
git push -u origin main
```

### 2. GitHub Pages の設定

1. GitHubのリポジトリページにアクセス
2. **Settings** タブをクリック
3. 左サイドバーの **Pages** をクリック
4. **Source** セクションで以下を選択：
   - Branch: `main`
   - Folder: `/ (root)`
5. **Save** をクリック

### 3. 公開URLの確認

設定後、数分でサイトが公開されます。URLは以下の形式になります：

```
https://[ユーザー名].github.io/maimai_policy/
```

## 📁 ファイル構成

```
maimai_policy/
├── index.html      # プライバシーポリシーのメインページ
├── styles.css      # スタイルシート
└── README.md       # このファイル
```

## 🎨 デザイン特徴

- **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応
- **モダンなUI**: グラデーション背景と洗練されたカラースキーム
- **読みやすさ重視**: 適切な行間、フォントサイズ、コントラスト
- **印刷対応**: 印刷時にも適切に表示されるスタイル

## 📝 内容の更新

プライバシーポリシーの内容を更新する場合：

1. `index.html` を編集
2. `最終更新日` を更新
3. 変更をコミットしてプッシュ

```bash
git add index.html
git commit -m "Update privacy policy"
git push
```

変更は数分以内にGitHub Pagesに反映されます。

## 🔒 プライバシーポリシーの主な内容

- アカウント情報の収集と利用
- 位置情報・歩数データの取り扱い
- 地図メモ機能のデータ管理
- パーソナライズ機能のための情報利用
- ユーザーの権利（アクセス、訂正、削除など）
- データ保護のセキュリティ対策

## 📧 お問い合わせ

プライバシーポリシーに関するお問い合わせ：
- メール: maimaikyoto.app@gmail.com

## 📄 ライセンス

© 2025 Ichi Hosotsuji. All rights reserved.
