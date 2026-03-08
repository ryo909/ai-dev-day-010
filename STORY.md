# Day010 Story — API Error Narrator

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day010専用にテーマをseed固定して再生成時の見た目を安定化
- devtools用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: incident_triage
- Mechanic: keyword_extraction
- Input/Output: error_log_paste -> triage_steps
- Audience Promise: faster_first_response
- Publish Hook: 障害調査の最初の10分を短縮
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
Day010｜API Error Narrator
API障害の初動切り分けを1分で始めるためのログ整理ツール。（話題:HN Frontpage）
