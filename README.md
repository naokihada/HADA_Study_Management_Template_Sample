# HADA Study Management Template — Sample 1

対応Templateバージョン: `1.0.0`

第2種電気工事士を題材にした、HADA Study Management Templateの架空サンプルです。

含まれる例:

- 筆記試験の学習記録
- 技能試験の学習計画
- Epic / Sprint / Issue / Subtask
- 試験日程の箇条書き表示
- Assessmentと正答率
- 年別写真フォルダの構造

すべて架空データです。実在の学習者、試験会場、予約情報、写真は含みません。

## Try it

```text
python tools/study_cli.py validate
python tools/study_cli.py calendar
python tools/study_cli.py photos
python tools/study_cli.py summary
python tools/study_cli.py domain-status
python tools/study_cli.py domain-change --to soulcalibur-6
python tools/study_cli.py ai-reset
python -m unittest discover -s tests -v
```

高校受験のSample 2は、別のサンプルプロジェクトとして将来追加します。

## Related guides

一覧は [Usage guide index](docs/guides/README.md) にもまとめています。

### Games

- [Soulcalibur VI（ソウルキャリバー6）](docs/guides/soulcalibur-6.md) — 対戦、練習、リプレイ、課題、ランクを記録する旗艦例。
- [Tekken 8（鉄拳8）](docs/guides/tekken-8.md) — キャラクター対策、確定反撃、コンボ、対戦傾向を管理。
- [Dead or Alive 6（デッド オア アライブ6）](docs/guides/dead-or-alive-6.md) — ホールド、読み合い、壁際などの課題を記録。
- [Pokkén Tournament（ポッ拳）](docs/guides/pokken-tournament.md) — フェイズ、キャラクター別練習、対戦結果を管理。
- [Fortnite（フォートナイト）](docs/guides/fortnite.md) — モード、順位、撃破原因、エイム・建築を振り返る。
- [Tetris（テトリス）](docs/guides/tetris.md)、[Tetris 99（テトリス99）](docs/guides/tetris-99.md)、[Puyo Puyo Tetris（ぷよぷよテトリス）](docs/guides/puyo-puyo-tetris.md) — 操作、判断、スコアを追跡。
- [Pokémon GO（ポケモンGO）](docs/guides/pokemon-go.md) — 捕獲、レイド、イベント、PvP、長期目標を記録。

### Exams and study

- [High school entrance（高校受験）](docs/guides/high-school-entrance.md) — 最大3年間の学習、志望校、定期試験、模試、出願日程を管理。
- [University entrance（大学受験）](docs/guides/university-entrance.md) — 大学・学部・方式、共通テスト、個別試験、出願を追跡。
- [Second-class electrician（第二種電気工事士）](docs/guides/second-class-electrician.md) — 学科と技能、作業時間、欠陥、写真レビューを記録。
- [First-class electrician（第一種電気工事士）](docs/guides/first-class-electrician.md) — 学科・技能・関連資格への継続学習を管理。
- [Hazardous materials qualifications（危険物取扱者 乙4・乙5・甲種）](docs/guides/hazardous-materials.md) — 区分別の試験、法令、性質・消火の学習を整理。
- [Art practical examination（美大実技試験）](docs/guides/art-practical-exam.md) — デッサン、色彩、構成、面接、講評、作品写真を記録。

### Hobbies and life work

- [Motorcycle maintenance（バイク趣味・メンテナンス）](docs/guides/motorcycle-maintenance.md) — 走行、整備、費用、部品、車検・保険を記録。
- [Jogging（ジョギング）](docs/guides/jogging.md)、[Swimming（水泳）](docs/guides/swimming.md) — 距離、時間、ペース、タイム、疲労、目標を継続管理。
- [Pet growth and care（ペット成長・健康記録）](docs/guides/pet-growth.md) — 体重、食事、行動、通院、成長の変化を記録。
- [Cooking and recipe practice（料理・レシピ）](docs/guides/cooking.md)、[Daily meal planning（毎日の献立）](docs/guides/meal-planning.md) — レシピ、献立、実施結果、改善点を蓄積。
- [Anime diary（アニメ感想記録）](docs/guides/anime-diary.md) — 視聴日、作品情報、一言コメント、感想を保存。

### Research and creation

- [Nature walk and plant observation（散歩・草花観察）](docs/guides/nature-walk.md)、[Photo journal（写真日記）](docs/guides/photo-journal.md) — 観察や写真を日付単位で記録。
- [Summer research（夏休みの自由研究）](docs/guides/summer-research.md) — 観察・実験を先に記録し、後から研究レポートへ整理。
- [Creative idea log（創作・漫画アイデア帳）](docs/guides/creative-idea-log.md) — 漫画などの着想、人物、世界観、資料を蓄積。

### General operations

- [General Prompt Catalog（一般用途のプロンプト集）](docs/guides/prompt-catalog.md) — 日次記録、週次レビュー、計画、変更、安全確認に使う共通プロンプト。
- [Mobile photo workflow（モバイル写真運用）](docs/guides/mobile-photo-workflow.md) — 携帯写真を手動で年別フォルダへ取り込む方法。

このSampleの実データは第2種電気工事士の架空例です。Soulcalibur VIなどの他用途は、同じテンプレートを設定変更して利用するガイド例として掲載しています。

## Disclaimer and freedom of use

このSample、テンプレート、設定例、プロンプト例に含まれる勉強内容、ゲーム攻略、料理、献立、栄養推定、草花同定、健康関連の例は、ChatGPTのAIがインターネット上の情報を参照して自動的に作成・整理したものを含みます。作者の特別な思想や個別指導の結果を示すものではなく、作者は内容の正確性、最新性、適合性を保証しません。

合格、成績向上、ランク向上、技能向上、健康改善、栄養改善、料理の成功、植物同定その他の結果や効果は保証されません。試験日、制度、ゲーム仕様、レシピ、健康・栄養情報などは、利用者自身が公式情報や専門家へ確認してください。写真やAI出力だけで医療、食事療法、薬、安全、緊急対応の判断をしないでください。

利用者は、ライセンスと適用法令の範囲で、自由に使用、改変、拡張、再構成できます。利用者自身のデータ、プライバシー、著作権、安全、AIサービスへの入力、判断と結果については利用者が責任を負います。詳細は [DISCLAIMER.md](DISCLAIMER.md) を参照してください。
