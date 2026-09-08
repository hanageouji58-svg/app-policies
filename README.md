# app-policies

スクワット判定員（表示名）の公開ポリシーサイト原稿です。

## 現在の状態

2026年9月8日時点では、Play Consoleの公開デベロッパー連絡先を認証済みConsoleで確認できていないため、GitHubの公開リポジトリとGitHub Pagesは作成していません。このローカル原稿には公開前のプレースホルダーが残っています。

公開前に、次の値と外部サービスの仕様を確定してください。

- 運営者名、サポートメール、サポートURL
- プライバシーポリシーURL、アカウント削除URL
- PanelPowerのプライバシーURL、保持期間、削除完了条件
- 制定日

## 公開予定のURL

- https://hanageouji58-svg.github.io/app-policies/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/privacy/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/account-deletion/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/support/

## サイトの方針

画像、外部フォント、Cookie、アクセス解析、広告、トラッキング、JavaScriptは使用していません。HTMLとCSSだけで表示し、モバイル幅でも読みやすいようにしています。

.github/workflows/pages.yml はGitHub公式のPages Actionsを使う構成です。公開リポジトリを作成して値を確認した後、Pagesの公開元をGitHub Actionsに設定して使用します。Play Consoleのアカウント削除URLには、アプリを再インストールしなくても削除依頼を開始できる、機能する外部ページを登録してください。

このサイトの内容は、Squatdegrees本体のコード監査と docs/google_play/ の原稿に基づきます。PanelPower側のFunctions、Firestore Rules、保持期間、バックアップ、削除完了条件は別管理のため、確認前に断定しません。
