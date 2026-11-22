# ai_cpu_live_sim

村人CPUが本物の人間のように暮らす村で、プレイヤー自身も村人の一員として活動する3Dゲーム。

## このリポジトリについて

- **GitHub には文書(`README.md` と `docs/`)だけを置く。** プログラムは送らない(`.gitignore` で、文書以外をすべて除外している)。
- プログラムはローカルにだけある。

## 構成(ローカル)

| 場所 | 内容 |
| --- | --- |
| `ai_cpu/` | 村人CPUの頭脳。行動の決め方・内部パラメータ。**ゲームにも描画にも依存しない**ので、他のゲームに持ち出せる |
| `docs/` | 設計・決めたこと・試行錯誤の記録(GitHub に送る) |
| `services.md` | 別のゲーム(ふるさと百代記)で使ったサービスの一覧。**参考資料**。このゲームの構成ではない。GitHub には送らない |

(ゲーム本体のフォルダは、作り始めたらここに足す。)

## 文書の案内

- [docs/00-concept.md](docs/00-concept.md) … 何を作るか・まだ決めていないこと
- [docs/01-architecture.md](docs/01-architecture.md) … 全体の作り・性能の考え方
- [docs/ai_cpu/design.md](docs/ai_cpu/design.md) … ai_cpu の設計
- [docs/decisions.md](docs/decisions.md) … 決めたことの記録
- [docs/journal.md](docs/journal.md) … 作業履歴・試行錯誤
