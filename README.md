# ai_cpu_live_sim

村人CPUが本物の人間のように暮らす村で、プレイヤー自身も村人の一員として活動する3Dゲーム。

## このリポジトリについて

- **GitHub には文書(`README.md` と `docs/`)だけを置く。** プログラムは送らない(`.gitignore` で、文書以外をすべて除外している)。
- プログラムはローカルにだけある。

## 構成(ローカル)

| 場所 | 内容 |
| --- | --- |
| `ai_cpu/` | 村人CPUの頭脳。行動の決め方・内部パラメータ。**ゲームにも描画にも依存しない**ので、他のゲームに持ち出せる |
| `game/` | 3D試作(Three.js + Vite)。[動かし方](docs/02-prototype.md) |
| `docs/` | 設計・決めたこと・試行錯誤の記録(GitHub に送る) |
| `services.md` | 別のゲーム(ふるさと百代記)で使ったサービスの一覧。**参考資料**。このゲームの構成ではない。GitHub には送らない |

## 文書の案内

- [docs/00-concept.md](docs/00-concept.md) … 何を作るか・まだ決めていないこと
- [docs/01-architecture.md](docs/01-architecture.md) … 全体の作り・性能の考え方
- [docs/02-prototype.md](docs/02-prototype.md) … 3D試作の動かし方・測定結果・課題
- [docs/03-sleep.md](docs/03-sleep.md) … 睡眠の個性(早起き・夜更かし・ショート/ロングスリーパー・昼寝好き)
- [docs/04-economy.md](docs/04-economy.md) … コンビニ・食料品・お金・ポーズ
- [docs/05-crime-and-police.md](docs/05-crime-and-police.md) … 家で寝る・マナー・犯罪・警察
- [docs/06-feelings.md](docs/06-feelings.md) … 対人感情・説教・喧嘩・追い詰められた犯人・警察の収入
- [docs/07-good-deeds.md](docs/07-good-deeds.md) … 良い行動(ゴミ拾い・寄付・贈り物・交換)・罰金と逮捕のばれ方
- [docs/08-jobs.md](docs/08-jobs.md) … 職業(会社員・畜産家・店員・フリーター・警官)・定員・給料・転職
- [docs/09-layout-player-talk.md](docs/09-layout-player-talk.md) … 村の配置・プレイヤー(1人称・CPU と同じ行動)・対話
- [docs/11-appearance.md](docs/11-appearance.md) … 村人の顔・髪・頭の形(人ごとに違う組み合わせ)
- [docs/10-sfx-replacement.md](docs/10-sfx-replacement.md) … 効果音を、効果音ラボの音に差し替える(割り当て済みと、足りない音)
- [docs/ai_cpu/design.md](docs/ai_cpu/design.md) … ai_cpu の設計
- [docs/decisions.md](docs/decisions.md) … 決めたことの記録
- [docs/journal.md](docs/journal.md) … 作業履歴・試行錯誤
