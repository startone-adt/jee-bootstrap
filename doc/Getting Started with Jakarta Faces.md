# Getting Started with Jakarta Faces
## Jakarta Faces について
&emsp;Jakarta Faces は、Java Web アプリケーションのユーザー インターフェイスの作成を簡素化するフレームワーク。MVC (モデル - ビュー - コントローラー) アーキテクチャに準拠しており、ビューは UI コンポーネントを表し、アプリケーションロジックはコントローラーとモデルレイヤーに存在する。

### Jakarta Faces を構成するコンポーネント
|コンポーネント|説明|
|---|---|
|UI コンポーネント|ボタン、入力フィールド、テーブル、ドロップダウン メニューなど、アプリケーションのユーザインターフェイスを作成するために使用される視覚要素|
|マネージドビーン|アプリケーションのビジネスロジックを管理し、UI コンポーネントと対話する。マネージド Bean は、ユーザ入力の処理、データの処理、アプリケーション内のナビゲーションの制御を担当する|
|ナビゲーションルール|ユーザがアプリケーション内のさまざまなビューまたはページ間を移動する方法を定義する|
|Facelets Templates|Facelets は Web ページのレイアウトと構造を定義するために Jakarta Faces で使用されるテンプレート言語。テンプレートは、アプリケーション内の複数のページの構造を再利用可能な方法で定義する|
|構成ファイル|Jakarta Faces アプリケーションには、アプリケーションのマネージドビーン、ナビゲーションルール、リソースマッピングに関するメタデータを含む faces-config.xml などの構成ファイルが含まれる場合がある|
|Validators and Converters|ユーザ入力を検証し、異なる形式間でデータを変換するための組み込みの検証機能とコンバータ|
|アプリケーションデプロイメント記述子|Jakarta Faces アプリケーションのデプロイメント設定とサーブレットマッピングを指定する構成ファイル (web.xml)|

## 始める