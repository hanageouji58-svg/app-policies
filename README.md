# app-policies

スクワット判定員（表示名）の公開ポリシーサイト原稿です。

## 現在の状態

2026年9月14日時点の公開情報を反映する原稿です。PanelPowerの共通アカウント削除について、通常のクラウドデータとFirebase Authを削除した後も、削除済みデータの復活防止用fenceを期限を設けず保持する実装を確認しています。未確認のバックアップ消去時期や架空のPanelPower URLは掲載していません。

公開後も、次の外部サービスの仕様は確認できた時点で更新してください。

- PanelPowerのバックアップ消去時期と、fence以外の運用上の保持期間
- バックアップからの消去時期

## 公開URL

- https://hanageouji58-svg.github.io/app-policies/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/privacy/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/account-deletion/
- https://hanageouji58-svg.github.io/app-policies/squatdegrees/support/

## サイトの方針

画像、外部フォント、Cookie、アクセス解析、広告、トラッキング、JavaScriptは使用していません。HTMLとCSSだけで表示し、モバイル幅でも読みやすいようにしています。

.github/workflows/pages.yml はGitHub公式のPages Actionsを使う構成です。公開リポジトリを作成して値を確認した後、Pagesの公開元をGitHub Actionsに設定して使用します。Play Consoleのアカウント削除URLには、アプリを再インストールしなくても削除依頼を開始できる、機能する外部ページを登録してください。

このサイトの内容は、Squatdegrees本体のコード監査、PanelPowerのPR #9でmergeされた削除実装、Squatdegreesの `docs/google_play/` 原稿に基づきます。確認できたfenceの保存項目・目的・無期限保持は明記し、バックアップ消去時期など未確認事項は断定しません。
