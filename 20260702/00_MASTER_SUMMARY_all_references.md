# 生理指標によるUX評価 — 全文献まとめ（01〜29）

心拍指標（RMSSD/SDNN）を起点に、自動車HMI・心拍以外の生理指標まで収集した全文献の一覧です。
番号は付与順で、18〜20は欠番（カテゴリ間の予約枠）です。

- **総本数**: 26本（01〜10、11〜17、21〜29）
- **カテゴリ**: A. 心拍/HRV（01〜10）｜B. 自動車HMI（11〜17）｜C. 心拍以外の生理指標（21〜29）

---

## 全体一覧表

| No. | 著者・年 | タイトル（短縮） | 種別 | 主な生理指標 | 対象ドメイン | 主眼 | ファイル |
|-----|---------|----------------|------|------------|------------|------|---------|
| 01 | Peruzzini ら (2018) | 生理データ＋混合プロトタイピングでUX分析 | 実証/方法論 | HRV(SDNN,RMSSD)・HR・EDA | 製品設計(HCD) | 早期プロトタイプのUX定量化 | [01](01_Peruzzini_2018_UX_physiological_mixed_prototyping.md) |
| 02 | Quintero ら (2021) | Excite-o-meter：VRに心拍統合 | ツール/実証 | HRV(SDNN,RMSSD) | VR/XR | SDNN vs RMSSDの使い分け | [02](02_Quintero_2021_Excite-o-meter_VR.md) |
| 03 | Czaban (2025) | ドライビングシミュレータのUX研究 | 博士論文 | HRV(RMSSD,SDNN) | 自動車/運転 | RMSSD/SDNNの妥当性・信頼性を実証 | [03](03_Czaban_2025_Driving_Simulators_UX.md) |
| 04 | Shin ら (2025) | 運転者の情動安定性評価 | 実証 | HRV(SDNN,RMSSD)・表情 | 自動車/運転 | 高ストレスでHRV低下 | [04](04_Shin_2025_Drivers_Emotional_Stability.md) |
| 05 | Shafi ら (2026) | フライトシミュレーション訓練 | 実証 | HRV(MeanNN,SDNN,RMSSD) | 航空/訓練 | 生理×UX(VRNQ)×成績 | [05](05_Shafi_2026_Flight_Simulation_UX.md) |
| 06 | Lin ら (2025) | BreathRelax：ゲーム型呼吸 | 実証 | HRV(RMSSD,SDNN,pNN50) | ヘルスケア/ゲーム | UXとリラックス効果の両立 | [06](06_Lin_2025_BreathRelax.md) |
| 07 | Wollmann ら (2016) | HRVバイオフィードバックゲーム | 実証 | HRV | ヘルスケア/ゲーム | ユーザビリティ×満足度 | [07](07_Wollmann_2016_HRV_Biofeedback_Game.md) |
| 08 | Miner ら (2025) | XR/画面型HRV-BFの比較 | 系統的レビュー | HRV(SDNN,coherence,RMSSD) | XR/ヘルスケア | メディア差とUX・HRV効果 | [08](08_Miner_2025_HRV_Biofeedback_XR_Review.md) |
| 09 | Kerr ら (2023) | VR・モバイルのストレス管理介入 | RCT | HRV | デジタルヘルス | 有効性＋良好UXを実証 | [09](09_Kerr_2023_VR_Biofeedback_Stress_UX_RCT.md) |
| 10 | Task Force(1996)/Shaffer(2017) | HRV指標の定義・基準値 | 基礎/標準 | HRV(SDNN,RMSSD,pNN50) | 全般 | 指標の定義・解釈・基準値 | [10](10_Foundational_HRV_Metrics_TaskForce_Shaffer.md) |
| 11 | Sriranga ら (2023) | 車内生理指標とセンサ | 系統的レビュー | HR・HRV・RR | 自動車HMI | 作業負荷モニタリング/指標感度 | [11](11_Sriranga_2023_InVehicle_Physiological_MWL_Review.md) |
| 12 | Jeong ら (2018) | ジョイスティック運転HMI評価 | 実証 | HRV(ECG由来) | 自動車HMI | HMI負荷をHRVで弁別 | [12](12_Jeong_2018_Joystick_HMI_Workload.md) |
| 13 | Riener ら (2017) | Driver in the Loop | 書籍章/方法論 | HRV ほか | 自動車HMI | センシング＋FBのベストプラクティス | [13](13_Riener_2017_Driver_in_the_Loop.md) |
| 14 | Zhang ら (2025) | 35のHRV指標でテイクオーバー予測 | 実証 | HRV(35指標) | 自動運転HMI | 有効指標の実証的選別 | [14](14_Zhang_2025_HRV_Takeover_Automated_Driving.md) |
| 15 | Cescon & Peruzzini | HMIのUX評価手法・標準 | 系統的レビュー | HRV ほか生理指標 | HMI全般 | 評価手法・ツール・標準の整理 | [15](15_Cescon_Peruzzini_HMI_UX_Evaluation_Review.md) |
| 16 | Rasheduzzaman (2023) | 車載IVI 音声 vs タッチ | 実証/比較 | HRV ほか | 自動車HMI | モダリティ比較の文脈依存性 | [16](16_Rasheduzzaman_2023_Voice_vs_Touch_IVI.md) |
| 17 | Salazar-Calderón ら (2025) | ドライバーモニタリングのUX | 系統的レビュー | HRV・眼球運動 ほか | 自動車HMI | 枠組み・実装・UX側面 | [17](17_SalazarCalderon_2025_Driver_Monitoring_UX_Review.md) |
| 21 | da Silveira ら (2025) | 生理データによるUX/QoE | 系統的レビュー | 眼球運動・表情・EEG・GSR・サーマル | 全般 | 非心拍を含む全体像 | [21](21_daSilveira_2025_Physiological_UX_QoE_Review.md) |
| 22 | Apraiz Iriarte ら (2021) | 生理モニタリングによるUX評価 | 系統的レビュー(SLR) | EEG・EMG・GSR | 全般 | 実務適用のマッピング | [22](22_ApraizIriarte_2021_Physiological_Monitoring_UX_SLR.md) |
| 23 | Baig & Kavakli (2019) | 心理生理計測サーベイ | サーベイ | EEG・GSR/EDA ほか | マルチモーダル | GSR/EDAが有力と結論 | [23](23_Baig_Kavakli_2019_PsychoPhysiological_Survey.md) |
| 24 | Taffese (2017) | EEG・EMGのUX活用 | 修士論文/レビュー | EEG・EMG | 全般 | 脳波・筋電の適用と課題 | [24](24_Taffese_2017_EEG_EMG_UX_Review.md) |
| 25 | Ball & Richardson (2024) | アイトラッキング＋生理 | 書籍章 | 眼球運動・瞳孔・EDA | 全般 | 視覚的注意＋情動/負荷 | [25](25_Ball_Richardson_2024_EyeTracking_Physiological_UX.md) |
| 26 | Ren ら (2024) | ロボット顔のUX知覚 | 実証 | 瞳孔・EEG・EDA・EMG | HRI/ロボット | 主観×生理の一致で評価 | [26](26_Ren_2024_Robot_Facial_Pupillometry_EEG.md) |
| 27 | Ganglbauer ら (2009) | 心理生理手法の実現可能性 | 方法論 | EDA・瞳孔 ほか | 全般 | 使える指標/限界の整理 | [27](27_Ganglbauer_2009_Psychophysiological_UX_Feasibility.md) |
| 28 | Akan & Berkman (2020) | ゲームUXの生理指標 | 書籍章 | EDA・表情筋EMG・眼球運動・瞳孔 | ゲーム | 情動体験の多面計測 | [28](28_Akan_Berkman_2020_Game_Physiological_Measures.md) |
| 29 | Majumder (2025) | アイトラッキング＋バイオメトリクス | 実証/事例 | 眼球運動・EEG・GSR | Web/ダッシュボード | エンゲージメント・認知負荷 | [29](29_Majumder_2025_EyeTracking_Biometric_Engagement.md) |

---

## カテゴリ別サマリー

### A. 心拍／HRV（RMSSD・SDNN）でのUX評価（01〜10）
- **中核テーマ**: ストレス・認知負荷・リラックスをHRVで客観化し、UXの良し悪しを評価。
- **指標の使い分け**: 短時間評価は RMSSD が安定、SDNN はより長い計測窓が望ましい（02, 10）。
- **エビデンスの幅**: 方法論提案（01）〜 RCT（09）〜 系統的レビュー（08）〜 基礎/標準（10）まで網羅。
- **代表的知見**: 良好なUX＝ストレス少＝RMSSD/HRV維持・上昇、という解釈枠組み。

### B. 自動車HMI × 生理指標でのUX評価（11〜17）
- **中核テーマ**: 車載HMI操作・自動運転の作業負荷/ストレスを生理指標で評価。
- **重要な注意点**: RMSSDの感度は自動化レベル・タスクに依存し、常に有意差が出るとは限らない（11）。
- **指標選定**: 35のHRV指標を比較して有効指標を選別（14）。
- **実務課題**: 運転中は体動・振動のアーティファクトが多く、前処理と計測窓設計が重要。

### C. 心拍以外の生理指標でのUX評価（21〜29）
- **中核テーマ**: EEG・EDA/GSR・眼球運動・瞳孔・表情筋EMG・サーマルによるUX評価。
- **実務的第一選択**: GSR/EDA は導入容易かつ情動的覚醒の計測に有用（23, 27）。
- **注意配分**: アイトラッキングは視覚的注意・UIの混乱箇所特定に最適（25, 29）。
- **情動価**: 表情筋EMGが快/不快を高感度に検出（24, 28）。

---

## 生理指標クイックリファレンス

| 指標 | 主に測るもの | UXでの解釈 | 導入容易性 | 該当文献 |
|------|------------|-----------|-----------|---------|
| RMSSD | 副交感神経活動 | 上昇＝リラックス/快適、低下＝ストレス | 中（短時間で安定） | 01〜14 |
| SDNN | 交感＋副交感（総合） | 上昇＝自律神経の柔軟性/良好 | 中（長め計測が望ましい） | 01〜14 |
| pNN50 | 副交感神経活動 | RMSSDと同傾向 | 中 | 06, 10 |
| EDA/GSR | 情動的覚醒・発汗 | 上昇＝覚醒/ストレス/情動反応 | 高 | 21〜29 |
| EEG | 脳の電気活動 | 認知負荷・注意・情動 | 低（複雑） | 21,22,24,26,29 |
| 眼球運動 | 注視・視線移動 | 視覚的注意・探索効率・混乱 | 中 | 21,25,28,29 |
| 瞳孔測定 | 瞳孔径変化 | 認知負荷・覚醒 | 中（環境要因に弱い） | 25,26,27,28 |
| 表情筋EMG | 表情筋活動 | 情動価（快/不快） | 中 | 22,24,26,28 |
| サーマル | 皮膚温度 | ストレス・情動（非接触） | 中 | 21 |

---

## 種別（研究デザイン）別の分類

| 種別 | 文献番号 |
|------|---------|
| 系統的レビュー/サーベイ | 08, 11, 15, 17, 21, 22, 23 |
| RCT（ランダム化比較試験） | 09 |
| 実証研究 | 01, 02, 04, 05, 06, 07, 12, 14, 16, 26, 29 |
| 書籍章/方法論 | 13, 25, 28 |
| 学位論文 | 03（博士）, 24（修士） |
| 基礎/標準・方法論 | 10, 27 |

---

## ドメイン別インデックス

- **自動車/運転**: 03, 04, 11, 12, 13, 14, 15, 16, 17
- **VR/XR**: 02, 08, 05（フライトシミュレーション）
- **ヘルスケア/バイオフィードバック**: 06, 07, 08, 09
- **ゲーム/エンタメ**: 06, 07, 28
- **ロボット/HRI**: 26
- **Web/ダッシュボード/情報系UI**: 29
- **製品設計(HCD)/全般**: 01, 10, 21, 22, 23, 24, 25, 27

---

## 関連READMEへのリンク
- [00_README.md](00_README.md) — 心拍/HRV文献集の索引（01〜10）
- [00_README_automotive_HMI.md](00_README_automotive_HMI.md) — 自動車HMI文献集（11〜17）
- [00_README_other_physiological.md](00_README_other_physiological.md) — 心拍以外の生理指標文献集（21〜29）

> **注記**: 各解説は検索スニペット・要旨に基づいて構成しています。引用前に原著本文で計測条件・結論の詳細をご確認ください。18〜20は欠番です。
