---
name: store-event-scout
description: 店舗傾向やイベント日程・狙い目を整理する。店舗名・イベント・日替わり・設定投入傾向・並びの相談のときに使う。
---

# 店舗・イベント調査

## 手順

1. `knowledge/stores/README.md` で**よく行く店・たまに行く店**の優先度を確認
2. `knowledge/stores/` と `knowledge/events/` を確認
3. プレイブックを参照:
   - `playbooks/store-scouting.md` … 全体方針
   - `playbooks/information-sources.md` … 情報源
   - `playbooks/x-event-analysis.md` … X告知×過去結果
   - `playbooks/seat-number-analysis.md` … 台番・末尾
4. 店舗の **X告知** と **みんレポ等の過去結果** を突合（当日情報は Web 検索）
5. 台番・末尾の癖は `knowledge/stores/` の観測ログを優先、なければデータサイトから考察
6. 推測は「確定 / 有力 / 可能性 / 不明」に分ける
7. 実践向けに「今日の仮説」と「観測ポイント」を短く返す

## 店舗提案のルール

- **優先度1（よく行く店）から提案を組み立てる**（ベルシティ元住吉・マルハン鶴見・PIA綱島）
- 旧イベ・データが別店に有利でも、訪問頻度が低い店を最優先にしない
- アビバ綱島は**たまに行く**扱い。カレンダー一致時のみ候補に上げる

## 出力テンプレ

```markdown
## 店舗仮説
- ...

## イベント読み（X・旧イベ）
- 確定: ...
- 有力: ...

## 台番・末尾
- 有力: ...
- 可能性: ...

## 狙い目
1. ...

## 観測ポイント
- ...

## 注意
- 未確認情報はここに明示
```

## 記録

- 新しい傾向 → `knowledge/stores/<店舗>.md`
- 特定日の告知と結果 → `knowledge/events/YYYY-MM-DD-<店舗>.md`
- テンプレは `knowledge/stores/_template.md` `knowledge/events/_template.md`
