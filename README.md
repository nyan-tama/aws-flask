
# アプリケーション名
よくある3層構造のWEBアプリケーションです。
このアプリケーションはFlaskを使用し、PostgreSQLデータベースに挨拶を保存するシンプルなWebアプリケーションです。

## 特徴

- FlaskベースのWebアプリケーション
- PostgreSQLデータベースを使用
- Dockerで容易にセットアップ可能

## 始め方

### 前提条件

- Dockerがインストールされていること
- Docker Composeが利用可能であること

### インストール手順

1. プロジェクトをクローンする：

git clone [リポジトリURL]

2. Docker Composeを使用してアプリケーションとデータベースを起動する：

cd [プロジェクトディレクトリ]
docker-compose up -d

3. アプリケーションが起動したら、ブラウザで `http://localhost:5000` にアクセスする。

### 使用方法

#### 新しい挨拶の追加

1. ブラウザで `http://localhost:5000` にアクセスする。
2. 表示されたフォームに挨拶の名前を入力し、`Submit` ボタンをクリックする。
3. 入力した挨拶が下のリストに表示される。

#### 挨拶リストの表示

- トップページにアクセスすると、データベースに保存されているすべての挨拶が表示されます。

## 技術スタック

- フロントエンド：HTML, CSS
- バックエンド：Flask (Python)
- データベース：PostgreSQL
- コンテナ化：Docker, Docker Compose


