# 感情（喜び・驚き）の生理・表情評価 — 文献解説集

ユーザーの**うれしさ（喜び・満足・delight）**や**驚き（surprise）**といった感情、
とりわけ**ポジティブ感情の生理・表情評価**に関する文献の詳細解説です。
自動車HMIのUX評価（感情面）を強化するための根拠として収集しました。
番号は 31〜38 を付与しています（既存 01〜30 の続き）。

---

## 31. Braun, Weber & Alt (2021): 感情的自動車UI — ドライバー感情研究と車内感情調整のレビュー
- **タイトル**: Affective Automotive User Interfaces – Reviewing the State of Driver Affect Research and Emotion Regulation in the Car
- **出典**: *ACM Computing Surveys (CSUR)*, 2021 / 被引用約145
- **URL**: https://dl.acm.org/doi/abs/10.1145/3460938
- **要点**: 車内でのドライバー感情（ポジ/ネガ両方）を検出し、**感情調整（emotion regulation）**
  によって安全性とUXを高める研究を包括レビュー。感情検出の生理・表情・音声手法と、
  車が感情に介入する設計を体系化。**自動車HMIで「うれしさ・驚き」を扱う際の中核レビュー**。
- **UXへの示唆**: ポジティブ感情の喚起・維持がUX向上と安全に寄与するという枠組みを提供。

## 32. Zepf ら (2020): インテリジェント車両のためのドライバー感情認識サーベイ
- **タイトル**: Driver Emotion Recognition for Intelligent Vehicles: A Survey
- **出典**: *ACM Computing Surveys*, 2020 / 被引用約330
- **URL**: https://dl.acm.org/doi/abs/10.1145/3388790
- **要点**: 車載文脈でのドライバー感情認識を、生理信号・表情・音声など多面的に整理。
  刺激の種類によって生理反応の強さが変わることを指摘。**感情認識の指標・手法選定の定番サーベイ**。
- **UXへの示唆**: 喜び・驚きを含む感情を、非接触の表情や生理指標で認識する技術的選択肢を提示。

## 33. Höfling ら (2020): 自動表情コーディング vs 心理生理指標 — 感情価と覚醒の比較
- **タイトル**: Read My Face: Automatic Facial Coding versus Psychophysiological Indicators of Emotional Valence and Arousal
- **出典**: *Frontiers in Psychology*, 2020 / 被引用約108
- **URL**: https://www.frontiersin.org/articles/10.3389/fpsyg.2020.01388/full
- **要点**: カメラによる**自動表情コーディング（FR）**と、**表情筋EMG（大頬骨筋・皺眉筋）**・
  EDAなどの心理生理指標を直接比較。表情筋EMGの差分（zygomaticus − corrugator）が
  感情価を、EDAが覚醒を反映することを示す。**非接触の表情解析がEMGをどこまで代替できるか**
  を検証した重要文献。
- **UXへの示唆**: 「うれしさ＝大頬骨筋活動↑」「驚き＝覚醒(EDA)↑」を、非接触カメラでも
  ある程度捉えられる根拠。負担の少ない感情計測の裏付け。

## 34. Hazlett & Benedek (2007): 感情価の計測によるソフトウェアUXの理解
- **タイトル**: Measuring Emotional Valence to Understand the User's Experience of Software
- **出典**: *International Journal of Human-Computer Studies*, 2007 / 被引用約129
- **URL**: https://www.sciencedirect.com/science/article/pii/S1071581906001868
- **要点**: **大頬骨筋（smiling muscle）の表情筋EMG**が、ソフトウェア使用時のポジティブな
  感情価と正相関することを実証。UX（使っていて楽しい/満足）を生理的に測る古典的事例。
- **UXへの示唆**: 「うれしさ」をzygomaticus EMGで定量化できることの直接的根拠。

## 35. Partala, Surakka & Vanhala (2006): 表情からの感情体験のリアルタイム推定
- **タイトル**: Real-time Estimation of Emotional Experiences from Facial Expressions
- **出典**: *Interacting with Computers*, 2006 / 被引用約90
- **URL**: https://academic.oup.com/iwc/article-abstract/18/2/208/742643
- **要点**: **大頬骨筋EMGと体験された感情価（valence）に正の線形関係**を確認。生理反応から
  ユーザー感情をリアルタイム推定する枠組みを提示。
- **UXへの示唆**: インタラクション中の「うれしさ」の時系列変化を追える。イベント（HMI操作・
  サプライズ演出）ごとの感情反応の評価に有効。

## 36. Gjoreski ら (2022): ウェアラブルデバイスによる表情筋EMGの感情モニタリング
- **タイトル**: Facial EMG Sensing for Monitoring Affect Using a Wearable Device
- **出典**: *Scientific Reports* (Nature), 2022 / 被引用約50
- **URL**: https://www.nature.com/articles/s41598-022-21456-1
- **要点**: メガネ型など**装着感の少ないウェアラブル**に表情筋EMG（zygomaticus, corrugator,
  orbicularis 等）を統合し、感情価・覚醒を計測。特殊な貼付電極なしで感情モニタリングを実現。
- **UXへの示唆**: 「低装着感で感情価を測る」実装の根拠。非接触カメラ解析と併せ、負担の
  少ない感情計測の選択肢を広げる。

## 37. Di Tecco (2025): 表情からUXへ — ユーザー感情が知的システム設計を規定する
- **タイトル**: From Facial Expressions to User Experience (UX): How User Emotions Define the Design of Intelligent Systems
- **出典**: *IEEE Access*, 2025
- **URL**: https://ieeexplore.ieee.org/abstract/document/11300855/
- **要点**: **表情認識（FER）**を軸に、ユーザー感情をUX評価・システム設計に結びつける枠組み。
  心拍・表情マイクロ表現などの心理生理変化を統合。分析中で**「驚き（surprise）」が
  検出表情の80%超**を占めたと報告し、驚き検知の重要性を示す。
- **UXへの示唆**: 「驚き」を含む感情をUX指標として設計に反映する最新の枠組み。

## 38. Wang & Song (2021): 生理計測に基づく感情的コンピュータゲーム体験の開発モデル
- **タイトル**: A Model for Developing Emotional Computer Game Experiences Based on Physiological Measurements
- **出典**: Proc. 2021 Int. Conf.（ACM）
- **URL**: https://dl.acm.org/doi/abs/10.1145/3478472.3478477
- **要点**: EEG・**表情筋EMG**・GSRを用い、**大頬骨筋の活動が興奮・幸福（excitement, happiness）**
  を示すことを利用して、感情的なゲーム体験を設計するモデルを提案。
- **UXへの示唆**: ポジティブ感情（うれしさ・興奮）を生理指標でUX設計に組み込む実践例。
  エンタメ性のある車載体験（サプライズ演出など）の評価に応用可能。

---

## ポジティブ感情・驚きの生理/表情サイン（まとめ）

| 感情 | 主な生理・表情サイン | 計測指標 | 根拠 |
|------|--------------------|---------|------|
| うれしさ/満足（正の感情価） | 大頬骨筋（zygomaticus, 笑筋）の活動上昇 | 表情筋EMG／カメラ表情解析(AU6/12) | [33][34][35][36][38] |
| 不快/フラストレーション（負の感情価） | 皺眉筋（corrugator）の活動上昇 | 表情筋EMG／カメラ表情解析(AU4) | [24][33] |
| 驚き（surprise） | 覚醒の急上昇、眉上げ・目見開き、瞬間的心拍変化 | EDA位相性反応・表情(AU1/2/5)・HR | [32][33][37] |
| 興奮/エンゲージメント | 覚醒上昇＋正の感情価 | EDA＋zygomaticus EMG | [28][38] |

> **感情の2次元モデル**: 感情は「感情価（valence: 快−不快）」と「覚醒（arousal: 高−低）」の
> 2軸で捉えるのが定石（Höfling 2020 [33]）。**感情価＝表情筋EMG/表情解析**、
> **覚醒＝EDA・心拍**という役割分担が有効。うれしさ＝高valence、驚き＝高arousal＋
> 文脈依存のvalence、として解釈する。

## 非接触・低負担での感情計測（本プロジェクト方針との整合）
- **カメラ表情解析（AU6/12＝笑顔, AU1/2/5＝驚き）** で感情価・驚きを非接触評価（[33][37]）。
- **EDA（ステアリング埋込・リストバンド）** で覚醒・驚きの急峻な反応を捉える（[33]）。
- 表情筋EMGはメガネ型など**低装着感デバイス**で代替可能（[36]）。
- これらは提案書 [30_PROPOSAL_Automotive_HMI_UX_Evaluation.md](30_PROPOSAL_Automotive_HMI_UX_Evaluation.md) の
  非接触センサ方針（付録A）と整合する。
