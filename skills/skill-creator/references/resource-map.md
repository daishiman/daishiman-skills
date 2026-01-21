# Progressive Disclosure リソースマップ

リソースは**必要な時のみ**読み込む。このファイルは全リソースの詳細な読み込み条件を定義する。

---

## agents/

| Agent | 読み込み条件 | 責務 |
|-------|-------------|------|
| [interview-user.md](.claude/skills/skill-creator/agents/interview-user.md) | collaborativeモード時 | 要件ヒアリング・抽象度判定 |
| [interview-execution-mode.md](.claude/skills/skill-creator/agents/interview-execution-mode.md) | orchestrateモード時 | 実行モード選択ヒアリング |
| [delegate-to-codex.md](.claude/skills/skill-creator/agents/delegate-to-codex.md) | Codex委譲時 | Codexへのタスク委譲手順 |
| [analyze-request.md](.claude/skills/skill-creator/agents/analyze-request.md) | createモード時 | ユーザー要求の分析 |
| [extract-purpose.md](.claude/skills/skill-creator/agents/extract-purpose.md) | 要求分析後 | スキル目的の抽出 |
| [define-boundary.md](.claude/skills/skill-creator/agents/define-boundary.md) | 目的定義後 | スコープ・境界の定義 |
| [define-trigger.md](.claude/skills/skill-creator/agents/define-trigger.md) | 目的定義後 | 発動条件の定義 |
| [select-anchors.md](.claude/skills/skill-creator/agents/select-anchors.md) | 目的定義後 | 参考文献・アンカーの選定 |
| [design-workflow.md](.claude/skills/skill-creator/agents/design-workflow.md) | ワークフロー設計時 | Phase構成・フロー設計 |
| [plan-structure.md](.claude/skills/skill-creator/agents/plan-structure.md) | 構造計画時 | ディレクトリ・ファイル構成計画 |
| [design-update.md](.claude/skills/skill-creator/agents/design-update.md) | updateモード時 | 既存スキル更新計画 |
| [improve-prompt.md](.claude/skills/skill-creator/agents/improve-prompt.md) | improve-promptモード時 | プロンプト品質改善 |
| [analyze-script-requirement.md](.claude/skills/skill-creator/agents/analyze-script-requirement.md) | スクリプト要件分析時 | スクリプト要件の抽出 |
| [design-script.md](.claude/skills/skill-creator/agents/design-script.md) | スクリプト設計時 | スクリプト設計仕様作成 |
| [design-custom-script.md](.claude/skills/skill-creator/agents/design-custom-script.md) | カスタムスクリプト時 | 24タイプ外の独自スクリプト設計 |
| [generate-code.md](.claude/skills/skill-creator/agents/generate-code.md) | コード生成時 | テンプレートからコード生成 |
| [design-variables.md](.claude/skills/skill-creator/agents/design-variables.md) | 変数設計時 | テンプレート変数定義 |
| [analyze-feedback.md](.claude/skills/skill-creator/agents/analyze-feedback.md) | 改善分析時 | フィードバックデータ解釈 |
| [design-self-improvement.md](.claude/skills/skill-creator/agents/design-self-improvement.md) | 改善計画時 | 改善提案の設計 |
| [save-patterns.md](.claude/skills/skill-creator/agents/save-patterns.md) | パターン保存時 | patterns.mdへのパターン記録 |

---

## references/

| Reference | 読み込み条件 | 内容 |
|-----------|-------------|------|
| [overview.md](.claude/skills/skill-creator/references/overview.md) | 初回/概要確認時 | skill-creator全体概要 |
| [core-principles.md](.claude/skills/skill-creator/references/core-principles.md) | 設計判断時 | 設計原則・哲学 |
| [interview-guide.md](.claude/skills/skill-creator/references/interview-guide.md) | collaborativeモード時 | ユーザーインタビュー手法 |
| [abstraction-levels.md](.claude/skills/skill-creator/references/abstraction-levels.md) | 抽象度判定時 | L1-L3レベル詳細 |
| [execution-mode-guide.md](.claude/skills/skill-creator/references/execution-mode-guide.md) | orchestrateモード時 | モード選択フローチャート |
| [codex-best-practices.md](.claude/skills/skill-creator/references/codex-best-practices.md) | Codex利用時 | Codex活用ベストプラクティス |
| [creation-process.md](.claude/skills/skill-creator/references/creation-process.md) | createモード時 | スキル作成プロセス詳細 |
| [update-process.md](.claude/skills/skill-creator/references/update-process.md) | updateモード時 | スキル更新プロセス詳細 |
| [script-types-catalog.md](.claude/skills/skill-creator/references/script-types-catalog.md) | スクリプトタイプ選択時 | 24タイプ詳細カタログ |
| [runtime-guide.md](.claude/skills/skill-creator/references/runtime-guide.md) | ランタイム設定時 | node/python/bash別ガイド |
| [variable-template-guide.md](.claude/skills/skill-creator/references/variable-template-guide.md) | 変数設計時 | テンプレート構文ガイド |
| [api-integration-patterns.md](.claude/skills/skill-creator/references/api-integration-patterns.md) | API系スクリプト時 | API統合パターン集 |
| [workflow-patterns.md](.claude/skills/skill-creator/references/workflow-patterns.md) | ワークフロー設計時 | 実行パターン・分岐 |
| [skill-structure.md](.claude/skills/skill-creator/references/skill-structure.md) | 構造計画時 | ディレクトリ構造仕様 |
| [naming-conventions.md](.claude/skills/skill-creator/references/naming-conventions.md) | ファイル命名時 | 命名規則・形式 |
| [output-patterns.md](.claude/skills/skill-creator/references/output-patterns.md) | 出力設計時 | 出力形式・パターン |
| [quality-standards.md](.claude/skills/skill-creator/references/quality-standards.md) | 品質検証時 | 品質基準・チェック項目 |
| [feedback-loop.md](.claude/skills/skill-creator/references/feedback-loop.md) | フィードバック設計時 | フィードバックループ設計 |
| [self-improvement-cycle.md](.claude/skills/skill-creator/references/self-improvement-cycle.md) | 自己改善時 | 改善サイクル詳細 |
| [patterns.md](.claude/skills/skill-creator/references/patterns.md) | 成功/失敗パターン参照時 | 蓄積されたパターン集 |
| [script-commands.md](.claude/skills/skill-creator/references/script-commands.md) | スクリプト実行時 | 全スクリプトの実行コマンド詳細 |
| [library-management.md](.claude/skills/skill-creator/references/library-management.md) | 依存関係追加時 | PNPM依存関係管理ガイド |
| [resource-map.md](.claude/skills/skill-creator/references/resource-map.md) | リソース詳細確認時 | このファイル（全リソースマップ） |

---

## scripts/

すべてのスクリプトは決定論的処理（100%精度）。共通ユーティリティは `utils.js` に集約。

| カテゴリ | スクリプト | 責務 |
|----------|-----------|------|
| **共通** | [utils.js](.claude/skills/skill-creator/scripts/utils.js) | EXIT_CODES, getArg, resolvePath, parseFrontmatter等 |
| モード判定・初期化 | [detect_mode.js](.claude/skills/skill-creator/scripts/detect_mode.js) | モード自動判定 |
| | [detect_runtime.js](.claude/skills/skill-creator/scripts/detect_runtime.js) | ランタイム判定 |
| | [init_skill.js](.claude/skills/skill-creator/scripts/init_skill.js) | スキル初期化・package.json生成 |
| 生成系 | [generate_skill_md.js](.claude/skills/skill-creator/scripts/generate_skill_md.js) | SKILL.md生成 |
| | [generate_agent.js](.claude/skills/skill-creator/scripts/generate_agent.js) | エージェント生成 |
| | [generate_script.js](.claude/skills/skill-creator/scripts/generate_script.js) | スクリプト生成 |
| | [generate_dynamic_code.js](.claude/skills/skill-creator/scripts/generate_dynamic_code.js) | 動的コード生成 |
| 検証系 | [validate_all.js](.claude/skills/skill-creator/scripts/validate_all.js) | 全体検証 |
| | [validate_structure.js](.claude/skills/skill-creator/scripts/validate_structure.js) | 構造検証 |
| | [validate_links.js](.claude/skills/skill-creator/scripts/validate_links.js) | リンク検証 |
| | [validate_schema.js](.claude/skills/skill-creator/scripts/validate_schema.js) | スキーマ検証 |
| | [validate_workflow.js](.claude/skills/skill-creator/scripts/validate_workflow.js) | ワークフロー検証 |
| | [validate_plan.js](.claude/skills/skill-creator/scripts/validate_plan.js) | プラン検証 |
| | [quick_validate.js](.claude/skills/skill-creator/scripts/quick_validate.js) | 簡易検証 |
| 更新・分析 | [analyze_prompt.js](.claude/skills/skill-creator/scripts/analyze_prompt.js) | プロンプト分析 |
| | [apply_updates.js](.claude/skills/skill-creator/scripts/apply_updates.js) | 更新適用 |
| | [update_skill_list.js](.claude/skills/skill-creator/scripts/update_skill_list.js) | スキルリスト更新 |
| Codex連携 | [check_prerequisites.js](.claude/skills/skill-creator/scripts/check_prerequisites.js) | 前提条件確認 |
| | [assign_codex.js](.claude/skills/skill-creator/scripts/assign_codex.js) | Codex割当 |
| 自己改善 | [log_usage.js](.claude/skills/skill-creator/scripts/log_usage.js) | 使用ログ記録 |
| | [collect_feedback.js](.claude/skills/skill-creator/scripts/collect_feedback.js) | フィードバック収集 |
| | [apply_self_improvement.js](.claude/skills/skill-creator/scripts/apply_self_improvement.js) | 自己改善適用 |
| 依存関係 | [install_deps.js](.claude/skills/skill-creator/scripts/install_deps.js) | 依存関係インストール |
| | [add_dependency.js](.claude/skills/skill-creator/scripts/add_dependency.js) | 依存関係追加 |

---

## assets/

### テンプレート（基本）

| Asset | 読み込み条件 | 用途 |
|-------|-------------|------|
| [skill-template.md](.claude/skills/skill-creator/assets/skill-template.md) | SKILL.md生成時 | 新規スキルのSKILL.mdテンプレート |
| [agent-template.md](.claude/skills/skill-creator/assets/agent-template.md) | エージェント生成時 | Task仕様書形式テンプレート |
| [agent-task-template.md](.claude/skills/skill-creator/assets/agent-task-template.md) | タスク特化エージェント生成時 | タスク実行用エージェント |

### テンプレート（ランタイム別）

| Asset | 読み込み条件 | 用途 |
|-------|-------------|------|
| [base-node.js](.claude/skills/skill-creator/assets/base-node.js) | runtime=node時 | Node.jsベーステンプレート |
| [base-python.py](.claude/skills/skill-creator/assets/base-python.py) | runtime=python時 | Pythonベーステンプレート |
| [base-bash.sh](.claude/skills/skill-creator/assets/base-bash.sh) | runtime=bash時 | Bashベーステンプレート |
| [base-typescript.ts](.claude/skills/skill-creator/assets/base-typescript.ts) | runtime=bun/deno時 | TypeScriptベーステンプレート |

### テンプレート（機能別）

| Asset | 読み込み条件 | 用途 |
|-------|-------------|------|
| [script-generator-template.js](.claude/skills/skill-creator/assets/script-generator-template.js) | 生成系スクリプト時 | コード生成スクリプト用 |
| [script-validator-template.js](.claude/skills/skill-creator/assets/script-validator-template.js) | 検証系スクリプト時 | バリデーション用 |
| [script-task-template.js](.claude/skills/skill-creator/assets/script-task-template.js) | タスク実行スクリプト時 | 汎用タスク実行用 |

### テンプレート（フィードバック用）

| Asset | 読み込み条件 | 用途 |
|-------|-------------|------|
| [logs-template.md](.claude/skills/skill-creator/assets/logs-template.md) | スキル作成時 | LOGS.mdの初期テンプレート |
| [evals-template.json](.claude/skills/skill-creator/assets/evals-template.json) | スキル作成時 | EVALS.jsonの初期テンプレート |
| [patterns-template.md](.claude/skills/skill-creator/assets/patterns-template.md) | スキル作成時 | references/patterns.mdの初期テンプレート |

### タイプ別テンプレート（24タイプ）

スクリプトタイプ選択後、該当タイプのみ読み込む。

| カテゴリ | タイプ（type-{name}.md） |
|----------|-------------------------|
| API関連 | api-client, webhook, scraper, notification |
| データ処理 | parser, transformer, aggregator, file-processor |
| ストレージ | database, cache, queue |
| 開発ツール | git-ops, test-runner, linter, formatter, builder |
| インフラ | deployer, docker, cloud, monitor |
| 統合 | ai-tool, mcp-bridge, shell |
| 汎用 | universal |

---

## schemas/

JSON Schema形式。[validate_schema.js](.claude/skills/skill-creator/scripts/validate_schema.js)で検証。

| カテゴリ | スキーマ | 読み込み条件 |
|----------|---------|-------------|
| コア | mode, agent-definition, workflow | モード判定/エージェント生成/ワークフロー設計時 |
| create | purpose, boundary, trigger, anchors, structure-plan | 各Phase完了時 |
| collaborative | interview-result | インタビュー完了後 |
| update | update-plan | 更新計画後 |
| improve-prompt | prompt-analysis, prompt-improvement | 分析/改善計画後 |
| orchestrate | execution-mode, codex-task, codex-result | モード選択/Codex実行前後 |
| スクリプト | script-definition, script-type, runtime-config, variable-definition, dependency-spec, environment-spec | スクリプト生成各Phase |
| 実行 | execution-result, feedback-record | 実行完了/フィードバック記録時 |
