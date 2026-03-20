# Changelog

このファイルは、**印税OS v3.0 Core Specification** の主要な変更履歴を記録します。

本リポジトリは、AIによる著作物アクセスを  
**許諾・ログ・分配** の正規循環へ変換する権利処理OS仕様を扱います。

変更履歴は、思想・仕様・構造・サンプル・検証ルールの進化を追跡できるよう、  
できるだけ明確に記録していきます。

---

## [3.0.0] - 2026-03-21

### Added
- `README.md` を追加
- `CONTRIBUTING.md` を追加
- `LICENSE` を追加
- `CITATION.cff` を追加
- `spec/royalty-os-v3.0-core-spec.yaml` を追加
- `schema/royalty-os-v3.0-core.schema.json` を追加
- `examples/sample-trace-log.yaml` を追加
- `examples/sample-allocation-report.yaml` を追加

### Defined
- 印税OS v3.0 を、AIアクセスを **許諾・ログ・分配** の正規循環へ変換する権利処理OSとして定義
- Qコインを **非換金・非譲渡・内部会計単位** として定義
- AIを利用者または契約主体の **代理エージェント** として扱う原則を定義
- Access / Trace / Royalty の3レイヤー構造を定義
- 安全線と危険線を明文化
- YAML仕様、JSON Schema、サンプルログ、分配レポートの最小構成を公開

### Notes
- v3.0 は完成版ではなく、公開可能な **Core Specification** として位置づける
- 今後は v3.x 系で仕様の微調整、サンプル拡張、検証ルール整備を進める
- v7.0 は将来的な決定版 / Civilization Specification を想定

---

## Versioning Policy

このリポジトリでは、当面次の考え方でバージョンを管理します。

### Major
大きな思想転換、構造変更、または仕様の大幅改訂

例:
- レイヤー構造の変更
- Qコイン定義の根本変更
- 代理エージェント原則の変更

### Minor
互換性を保ちながら行う仕様追加や整理

例:
- 権限フラグの追加
- サンプルファイル追加
- Schema 制約の拡張
- docs の整理

### Patch
軽微な修正

例:
- 誤字修正
- 説明の明確化
- フィールド名の微修正
- サンプル値の補正

---

## Planned

### [3.1.0] - Planned
- `examples/sample-works.yaml` の追加
- README の導線改善
- Schema と examples の整合性向上
- 追加ドキュメントの整理

### [3.2.0] - Planned
- JSON Schema の精緻化
- サンプル分配ケースの拡張
- work / publisher / contract 単位の権限例の追加

### [3.x] - Planned
- ダミーログを用いた分配シミュレーション
- docs の拡張
- 実装者向け補助資料の追加

---

## Notes on History

この changelog は、単なる更新記録ではなく、  
**印税OSの系譜を可視化するログ** でもあります。

思想の震源、仕様の固定、実装の可能性、制度整合の工夫。  
それらがどのように積み上がったかを残すために、この履歴を更新していきます。
