# 心拍以外の生理指標によるUX評価 — 文献解説集

心拍・HRV（RMSSD/SDNN）**以外**の生理指標を用いて、ユーザー体験（UX）・ユーザビリティを評価している文献の詳細解説集です。脳波（EEG）、皮膚電気活動（EDA/GSR）、眼球運動（アイトラッキング）、瞳孔測定（Pupillometry）、表情筋EMG、サーマルイメージングなどを対象とします。

## 対象となる主な生理指標

| 指標 | 略称 | 主に測るもの | UXでの用途 |
|------|------|------------|-----------|
| 脳波 | EEG | 脳の電気活動 | 認知負荷・注意・情動・エンゲージメント |
| 皮膚電気活動 | EDA / GSR | 発汗による皮膚電気変化 | 情動的覚醒・ストレス反応 |
| 眼球運動 | Eye tracking | 注視点・視線移動 | 視覚的注意・探索効率・混乱箇所 |
| 瞳孔測定 | Pupillometry | 瞳孔径の変化 | 認知負荷・覚醒・情動 |
| 表情筋筋電 | Facial EMG | 表情筋の活動 | 情動価（快/不快）の高感度検出 |
| サーマル | Thermal imaging | 皮膚温度変化 | ストレス・情動（非接触） |

## 収録文献一覧

### レビュー・サーベイ（分野の全体像）
| No. | ファイル | 著者・年 | 主な指標 |
|-----|---------|---------|---------|
| 21 | [21_daSilveira_2025_Physiological_UX_QoE_Review.md](21_daSilveira_2025_Physiological_UX_QoE_Review.md) | da Silveira ら (2025) | 眼球運動・表情・サーマル・EEG・GSR（UX/QoEレビュー） |
| 22 | [22_ApraizIriarte_2021_Physiological_Monitoring_UX_SLR.md](22_ApraizIriarte_2021_Physiological_Monitoring_UX_SLR.md) | Apraiz Iriarte ら (2021) | EEG・EMG・GSR（生理モニタリングSLR） |
| 23 | [23_Baig_Kavakli_2019_PsychoPhysiological_Survey.md](23_Baig_Kavakli_2019_PsychoPhysiological_Survey.md) | Baig & Kavakli (2019) | EEG・GSR/EDA（マルチモーダルサーベイ、被引用105） |
| 24 | [24_Taffese_2017_EEG_EMG_UX_Review.md](24_Taffese_2017_EEG_EMG_UX_Review.md) | Taffese (2017) | EEG・EMG（UX研究レビュー） |
| 27 | [27_Ganglbauer_2009_Psychophysiological_UX_Feasibility.md](27_Ganglbauer_2009_Psychophysiological_UX_Feasibility.md) | Ganglbauer ら (2009) | EDA・瞳孔（実現可能性、被引用105） |

### 実証研究・実務事例
| No. | ファイル | 著者・年 | 主な指標 |
|-----|---------|---------|---------|
| 25 | [25_Ball_Richardson_2024_EyeTracking_Physiological_UX.md](25_Ball_Richardson_2024_EyeTracking_Physiological_UX.md) | Ball & Richardson (2024) | アイトラッキング・瞳孔・EDA |
| 26 | [26_Ren_2024_Robot_Facial_Pupillometry_EEG.md](26_Ren_2024_Robot_Facial_Pupillometry_EEG.md) | Ren ら (2024) | 瞳孔・EEG（ロボット顔デザインのUX） |
| 28 | [28_Akan_Berkman_2020_Game_Physiological_Measures.md](28_Akan_Berkman_2020_Game_Physiological_Measures.md) | Akan & Berkman (2020) | EDA・表情筋EMG・眼球運動・瞳孔（ゲームUX） |
| 29 | [29_Majumder_2025_EyeTracking_Biometric_Engagement.md](29_Majumder_2025_EyeTracking_Biometric_Engagement.md) | Majumder (2025) | アイトラッキング・EEG・GSR（エンゲージメント・認知負荷） |

## 指標選定の要点（文献からの総括）

- **EDA/GSR** は導入が容易で情動的覚醒の計測に有用 → 心拍と並ぶ実務的第一選択肢（Baig & Kavakli 2019, Ganglbauer 2009）。
- **アイトラッキング** は視覚的注意・UIの混乱箇所の特定に最適（Ball & Richardson 2024, Majumder 2025）。
- **表情筋EMG** は情動価（快/不快）を高感度で検出（Taffese 2017, Akan & Berkman 2020）。
- **EEG** は認知負荷・注意の評価に強いが、セットアップが複雑（da Silveira 2025, Taffese 2017）。
- **瞳孔測定** は情報量が多いが、照明など環境要因の影響を受けやすい（Ganglbauer 2009, Ball & Richardson 2024）。
- **複数指標の併用（マルチモーダル）** が、単一指標の弱点を補い頑健なUX評価につながる（全レビュー共通）。

> **注意**: EEG・眼球運動・表情・サーマルは高感度な一方でセットアップや解釈が複雑です。GSR/EDAは比較的導入しやすく、UX評価の入口として推奨されます。目的（認知負荷か情動か注意か）に応じて指標を選定してください。

## 関連
- [00_README.md](00_README.md) — 心拍指標（RMSSD/SDNN）によるUX評価 文献集
- [00_README_automotive_HMI.md](00_README_automotive_HMI.md) — 自動車HMI特化の文献集
