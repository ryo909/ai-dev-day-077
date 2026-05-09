# Day077 Story — Pan Size Ratio Converter

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day077専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: pan_ratio_convert
- Mechanic: swap_compare
- Input/Output: recipe_rows -> ratio_cards
- Audience Promise: 作り始める前に失敗しにくい量へ直せる。
- Publish Hook: 元の型と手元の型を入れるだけで、分量倍率と注意点がすぐ見える。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day077｜型サイズ換算カード
型違いのレシピ分量を直すためのツールです。
