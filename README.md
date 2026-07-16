# 勝ちスロ君（kachisulokun）

iPhoneのCursorアプリからチャットで使う、スロット実践中の相談用リポジトリ。

## できること

- 店舗・イベント傾向の整理
- 機種の基本情報（ゾーン・示唆・打ち方要点）
- 実践共有を受けた設定期待値・ゾーン・ヤメ判断の確認

## iOSからの使い方

1. Cursorアプリでこのリポジトリを開く
2. チャットで状況を投げる（短文でOK）

例:

```
今○○ジャグラー 420G、さっきCZ落としてリセット相当。
設定狙いで入ってる。続ける？
```

```
△△店、今日は設定公開デー。何から見る？
```

```
□□の天井と天国ゾーンだけ教えて
```

3. エージェントが `knowledge/` を参照して短く返す
4. まとまった内容は `sessions/` や `knowledge/` に残せる

## フォルダ構成

| パス | 用途 |
|------|------|
| `AGENTS.md` | エージェントの役割・口調 |
| `.cursor/rules/` | 常時適用の相談ルール |
| `.cursor/skills/` | 実践相談・機種調べ・店舗調査の手順 |
| `knowledge/machines/` | 機種スペック・ゾーン |
| `knowledge/stores/` | 店舗傾向 |
| `knowledge/events/` | イベント |
| `knowledge/events/calendar.md` | 旧イベ日付カレンダー（今日どこ打つ？の即答用） |
| `sessions/` | 実践ログ |
| `sessions/ledger.md` | 収支台帳（実践1回ごとに1行追記） |
| `playbooks/` | ゾーン確認・設定読み・偵察の手順書 |
| `playbooks/information-sources.md` | 情報源カタログ（みんレポ・X・DMM等） |
| `playbooks/x-event-analysis.md` | X告知×過去イベント結果の考察 |
| `playbooks/seat-number-analysis.md` | 台番・末尾の癖考察 |

## 最初にやること

1. よく打つ機種を `knowledge/machines/_template.md` から作成
2. 通う店舗を `knowledge/stores/_template.md` から作成
3. あとは実践中にチャットするだけで育つ

## 注意

- ここは相談・記録用。勝率保証ではない
- 店舗規約や法令に反する行為の助言はしない
