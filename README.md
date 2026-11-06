# task-crud-practice

## 概要
COACHTECH 教材 Tutorial 11-2「タスク管理APIのCRUD実装」で作成した成果物です。タスク管理APIのCRUD操作を実装しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- REST API（CRUD）
- API Resources、FormRequest（バリデーション）

## 学んだこと
- REST API の CRUD 実装（GET / POST / PUT / DELETE）と HTTP ステータスコードの使い分け
- apiResource ルートを使った5つのアクションを一括定義する方法

## 動作確認
Postmanを使って各エンドポイントにリクエストを送信し、動作確認を行います。以下の動作が正常に行われているのを確認してください。

- GET /api/tasksでタスク一覧が取得できる（200）
- POST /api/tasksでタスクを作成できる（201）
- GET /api/tasks/{id}でタスク詳細が取得できる（200）
- PUT /api/tasks/{id}でタスクを更新できる（200）
- DELETE /api/tasks/{id}でタスクを削除できる（204）
- バリデーションエラー時に422が返る
- 存在しないタスクにアクセスすると404が返る
