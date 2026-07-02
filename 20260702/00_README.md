# 心拍指標（RMSSD / SDNN）によるUX評価 — 文献解説集

心拍変動（HRV）の指標である **RMSSD** および **SDNN** を用いて、ユーザー体験（UX）の良し悪しを評価している文献をまとめた解説集です。各文献ごとに個別のマークダウンファイルで詳細解説を作成しています。

## 収録文献一覧

### UX研究でHRVを直接活用している文献
| No. | ファイル | 著者・年 | テーマ |
|-----|---------|---------|--------|
| 01 | [01_Peruzzini_2018_UX_physiological_mixed_prototyping.md](01_Peruzzini_2018_UX_physiological_mixed_prototyping.md) | Peruzzini ら (2018) | 生理データ＋混合プロトタイピングによる製品UX評価 |
| 02 | [02_Quintero_2021_Excite-o-meter_VR.md](02_Quintero_2021_Excite-o-meter_VR.md) | Quintero ら (2021) | VRにHRVを統合するフレームワーク（SDNN vs RMSSDの使い分け） |
| 03 | [03_Czaban_2025_Driving_Simulators_UX.md](03_Czaban_2025_Driving_Simulators_UX.md) | Czaban (2025) | ドライビングシミュレータ研究でRMSSD/SDNNの妥当性を実証 |
| 04 | [04_Shin_2025_Drivers_Emotional_Stability.md](04_Shin_2025_Drivers_Emotional_Stability.md) | Shin ら (2025) | 運転者の情動安定性を生理・表情指標で評価 |
| 05 | [05_Shafi_2026_Flight_Simulation_UX.md](05_Shafi_2026_Flight_Simulation_UX.md) | Shafi ら (2026) | フライトシミュレーション訓練のUX・生理反応・成績 |

### ゲーム／バイオフィードバック系（UX評価とHRVを併用）
| No. | ファイル | 著者・年 | テーマ |
|-----|---------|---------|--------|
| 06 | [06_Lin_2025_BreathRelax.md](06_Lin_2025_BreathRelax.md) | Lin ら (2025) | ゲーム型呼吸システムのUXとリラックス効果 |
| 07 | [07_Wollmann_2016_HRV_Biofeedback_Game.md](07_Wollmann_2016_HRV_Biofeedback_Game.md) | Wollmann ら (2016) | HRVバイオフィードバックゲームのユーザビリティ評価 |
| 08 | [08_Miner_2025_HRV_Biofeedback_XR_Review.md](08_Miner_2025_HRV_Biofeedback_XR_Review.md) | Miner ら (2025) | XR/スクリーン型HRV-BFの系統的レビュー |
| 09 | [09_Kerr_2023_VR_Biofeedback_Stress_UX_RCT.md](09_Kerr_2023_VR_Biofeedback_Stress_UX_RCT.md) | Kerr ら (2023) | VR・モバイルによるストレス管理介入のRCT |

### 指標理解のための基礎文献
| No. | ファイル | 内容 |
|-----|---------|------|
| 10 | [10_Foundational_HRV_Metrics_TaskForce_Shaffer.md](10_Foundational_HRV_Metrics_TaskForce_Shaffer.md) | RMSSD/SDNNの定義・解釈・基準値（Task Force 1996 / Shaffer & Ginsberg 2017） |

### 自動車HMI特化（深堀り）
自動車HMI／ドライバーUX × HRVの文献は、専用フォルダに詳細解説を収録しています。
- [00_README_automotive_HMI.md](00_README_automotive_HMI.md) — 自動車HMI文献集の索引（No.11〜17）
  - Sriranga 2023（車内生理指標レビュー）／Jeong 2018（ジョイスティックHMI）／Riener 2017（Driver in the Loop）／Zhang 2025（35 HRV指標・テイクオーバー）／Cescon & Peruzzini（HMI評価レビュー）／Rasheduzzaman 2023（音声vsタッチ）／Salazar-Calderón 2025（ドライバーモニタリングUX）

### 心拍以外の生理指標（深堀り）
EEG・EDA/GSR・眼球運動・瞳孔・表情筋EMGなど、心拍以外の生理指標でUXを評価する文献は専用フォルダに収録しています。
- [00_README_other_physiological.md](00_README_other_physiological.md) — 心拍以外の生理指標 文献集の索引（No.21〜29）
  - da Silveira 2025（UX/QoEレビュー）／Apraiz Iriarte 2021（生理モニタリングSLR）／Baig & Kavakli 2019（マルチモーダルサーベイ）／Taffese 2017（EEG/EMGレビュー）／Ball & Richardson 2024（アイトラッキング＋生理）／Ren 2024（瞳孔・EEGでロボット顔UX）／Ganglbauer 2009（心理生理手法の実現可能性）／Akan & Berkman 2020（ゲーム生理指標）／Majumder 2025（アイトラッキング＋バイオメトリクス）

## RMSSD / SDNN の基本的な読み方

| 指標 | 反映する神経系 | UXでの一般的な解釈 |
|------|--------------|-------------------|
| **RMSSD** | 副交感神経（迷走神経） | 上昇＝リラックス・快適／低下＝ストレス・緊張 |
| **SDNN** | 交感＋副交感（総合） | 上昇＝自律神経の柔軟性・良好な状態／低下＝負荷 |

> 短時間のUX実験では **RMSSD** が安定して算出でき、快適さ・リラックスの指標として使いやすい。**SDNN** はより長い計測窓が望ましい。

## 備考
- 各ファイルには書誌情報・概要・HRV指標の位置づけ・手法・UX評価への示唆・引用時のポイントを記載しています。
- URLやDOIは各ファイル内に記載しています。引用の際は最新の出版版・アクセス可否をご確認ください。
