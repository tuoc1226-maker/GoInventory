# 在庫管理アプリ

## 概要
本プロジェクトは、倉庫内の製品の追跡、整理、および管理を最適化するために設計されたWebアプリケーションです。バックエンドはGoとPostgreSQLで構築され、フロントエンドはReactとTypeScriptを使用して開発されています。

## スクリーンショット
![imsscreenshot](https://github.com/user-attachments/assets/73eb210e-dbd1-4700-9c68-02b63d0ea3a2)

## 使用技術

### バックエンド
- **Go**: シンプルさと効率性を重視して設計された、静的型付けのコンパイル型プログラミング言語。
- **PostgreSQL**: 信頼性とパフォーマンスの高さで定評のある、強力なオープンソースのオブジェクト関係データベースシステム。
- **Echo**: 使いやすさと拡張性を考慮して設計された、Go用の高性能かつミニマルなWebフレームワーク。
- **github.com/golang-jwt/jwt/v5**: セキュアな認証を実現するための、JSON Web Tokens (JWT) のGo実装。
- **github.com/jackc/pgx/v4**: 効率的かつ機能豊富なデータベース操作を提供する、Go用PostgreSQLドライバおよびツールキット。
- **github.com/labstack/gommon**: ロギング、カラー出力、バイト操作ユーティリティなどを含む、Go用の共通パッケージ群。

### フロントエンド
- **React**: Facebookおよび個人開発者・企業のコミュニティによって保守されている、ユーザーインターフェース構築用JavaScriptライブラリ。
- **TypeScript**: JavaScriptをベースに強力な型システムを導入したプログラミング言語。あらゆる規模の開発において優れたツールサポートを提供します。
- **Tailwind CSS**: カスタムユーザーインターフェースを迅速に構築するための、ユーティリティファーストなCSSフレームワーク。
- **js-cookie**: Cookieを扱うための、シンプルで軽量なJavaScript API。 ## はじめに

### 前提条件
- Go 1.23.0 以降
- Node.js 14.x 以降
- Postgres 12 以降

### インストール

1. **リポジトリのクローン:**
```
sh
git clone https://github.com/tuoc1226-maker/GoInventory.git
cd yourproject
```

2. **バックエンドのセットアップ:**
```
sh
cd server
go mod download
go build -o ./ims cmd/imsapi/main.go
```

3. **フロントエンドのセットアップ:**
```
sh
cd client
npm install
npm run dev
```

### アプリケーションの実行

1. **バックエンドの起動:**
```
sh
cd server
./ims
```

2. **フロントエンドの起動:**
```
sh
cd client
npm run dev
```

## ライセンス
本プロジェクトは MIT ライセンスの下で公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。