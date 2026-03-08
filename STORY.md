# Day010 Story — Tradeoff Path Wizard

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day010専用にテーマをseed固定して再生成時の見た目を安定化
- planning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: decision_wizard
- Mechanic: branching_questionnaire
- Input/Output: step_choices -> path_summary
- Audience Promise: clearer_decisions
- Publish Hook: 質問に答えるだけで判断パスが固まる
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day010｜Tradeoff Path Wizard
段階質問で意思決定パスを確定するウィザード型ツール。（話題:HN Frontpage）
