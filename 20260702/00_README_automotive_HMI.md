# 自動車HMI × HRV（RMSSD / SDNN）によるUX評価 — 文献解説集

心拍変動（HRV）指標である **RMSSD** および **SDNN** を用いて、**自動車HMI（Human-Machine Interface）**やドライバーのユーザー体験（UX）・作業負荷を評価している文献の詳細解説集です。親フォルダの汎用UX文献集を、自動車ドメインに特化して深堀りしたものです。

## 収録文献一覧

### 車内生理計測・ドライバー状態モニタリングのレビュー
| No. | ファイル | 著者・年 | テーマ |
|-----|---------|---------|--------|
| 11 | [11_Sriranga_2023_InVehicle_Physiological_MWL_Review.md](11_Sriranga_2023_InVehicle_Physiological_MWL_Review.md) | Sriranga ら (2023) | 車内生理指標・センサによるドライバー作業負荷モニタリングの系統的レビュー |
| 17 | [17_SalazarCalderon_2025_Driver_Monitoring_UX_Review.md](17_SalazarCalderon_2025_Driver_Monitoring_UX_Review.md) | Salazar-Calderón ら (2025) | ドライバーモニタリングの枠組み・実装・UX側面の系統的レビュー |
| 15 | [15_Cescon_Peruzzini_HMI_UX_Evaluation_Review.md](15_Cescon_Peruzzini_HMI_UX_Evaluation_Review.md) | Cescon & Peruzzini | HMIのUX評価手法・ツール・標準の系統的レビュー |

### HMI設計・操作方式の評価（実証研究）
| No. | ファイル | 著者・年 | テーマ |
|-----|---------|---------|--------|
| 12 | [12_Jeong_2018_Joystick_HMI_Workload.md](12_Jeong_2018_Joystick_HMI_Workload.md) | Jeong ら (2018) | ジョイスティック運転システムのHMIをHRV作業負荷で評価 |
| 16 | [16_Rasheduzzaman_2023_Voice_vs_Touch_IVI.md](16_Rasheduzzaman_2023_Voice_vs_Touch_IVI.md) | Rasheduzzaman (2023) | 車載インフォテインメントの音声 vs タッチ操作の比較 |

### 自動運転・ドライバーセンシングの基盤／指標選定
| No. | ファイル | 著者・年 | テーマ |
|-----|---------|---------|--------|
| 13 | [13_Riener_2017_Driver_in_the_Loop.md](13_Riener_2017_Driver_in_the_Loop.md) | Riener ら (2017) | 自動車センシング・フィードバックのベストプラクティス（Driver in the Loop） |
| 14 | [14_Zhang_2025_HRV_Takeover_Automated_Driving.md](14_Zhang_2025_HRV_Takeover_Automated_Driving.md) | Zhang ら (2025) | 35のHRV指標による自動運転テイクオーバー性能予測 |

## 自動車ドメインにおける RMSSD / SDNN の要点

| 観点 | 知見 |
|------|------|
| **作業負荷（MWL）** | 認知負荷・ストレス増加に伴いHRV（SDNN, RMSSD）が低下（Sriranga 2023, Jeong 2018） |
| **指標の感度** | RMSSDは自動化レベル・タスクによって有意差が出ない場合もある（Sriranga 2023） |
| **指標選定** | 35のHRV指標を比較し、テイクオーバー予測に有効な指標を選別（Zhang 2025） |
| **HMI設計評価** | 負荷の少ないHMIほどストレス関連のHRV変化が小さい（Jeong 2018） |
| **UX統合** | HRVは主観UX評価と組み合わせる客観指標として確立（Cescon & Peruzzini, Riener 2017） |

> **注意**: 運転中は身体動作・振動によるアーティファクトが生じやすいため、車内でのHRV計測は前処理（ノイズ除去）と計測窓の設計が特に重要です。また、RMSSDの感度が文脈依存であることから、複数のHRV指標や他モダリティ（EDA・眼球運動）との併用が推奨されます。

## 関連（他カテゴリの自動車関連文献）
- [03_Czaban_2025_Driving_Simulators_UX.md](03_Czaban_2025_Driving_Simulators_UX.md) — ドライビングシミュレータでRMSSD/SDNNの妥当性を実証
- [04_Shin_2025_Drivers_Emotional_Stability.md](04_Shin_2025_Drivers_Emotional_Stability.md) — 運転者の情動安定性を生理・表情指標で評価
- [10_Foundational_HRV_Metrics_TaskForce_Shaffer.md](10_Foundational_HRV_Metrics_TaskForce_Shaffer.md) — RMSSD/SDNNの定義・基準値
