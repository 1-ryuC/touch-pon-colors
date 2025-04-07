# 開発ワークフロー

## 開発環境の設定が完了しました。以下のファイルが追加されています：

- DEVELOPMENT_WORKFLOW.md - チケット駆動型開発のワークフロー詳細
- .github/ISSUE_TEMPLATE/feature_request.md - 機能実装用Issueテンプレート
- .github/ISSUE_TEMPLATE/bug_report.md - バグ報告用Issueテンプレート
- .github/PULL_REQUEST_TEMPLATE.md - PRテンプレート

## 具体的な開発の流れ

### Issueの作成:

1. リポジトリの「Issues」タブから新しいIssueを作成
2. 適切なテンプレート（機能実装またはバグ報告）を選択
3. タスクの詳細を記入し、ラベルを付与


### ブランチの作成:

- issue-[番号]-[簡単な説明]形式でブランチを作成
- 例: issue-12-implement-game-manager


### 実装:

- Claude Codeを使用してコードを実装
- コミットメッセージには関連するIssue番号を含める
- 例: feat: Implement GameManager base structure #12


### プルリクエスト:

- 実装完了後、PRを作成
- PRテンプレートに従って詳細を記入
- 関連するIssueとの連携を明記（closes #12など）


### マージ:

- レビュー後、問題なければmainブランチにマージ
- Issueは自動的にクローズされる



## Claudeとの効率的な協働

### コンテキストの提供:

- 現在取り組んでいるIssueの番号や詳細を説明
- 関連するコードファイルがある場合は内容を共有


### 具体的な指示:

- 「〇〇クラスのメソッドを実装してください」のように具体的に依頼
- リポジトリの構造を説明し、コードの保存場所を明確にする


### 継続性の維持:

- 前回の会話からの重要な情報を要約して共有
- 過去に解決した課題や決定事項を参照