# Evaluating UX and Usability in Automotive Human–Machine Interfaces: A Systematic Review

# 詳細解説（2026）

---

# 1. 論文概要

## タイトル

Evaluating UX and Usability in Automotive Human–Machine Interfaces: A Systematic Review

## 分野

* Automotive UX
* Human–Machine Interface (HMI)
* Human Factors
* Usability Engineering
* Physiological UX
* Driver Interaction

## 論文タイプ

Systematic Review（システマティックレビュー）

---

# 2. この論文は何をしたのか？

この論文は、

> 「自動車HMIのUX・Usability評価研究を体系的に整理した」

レビュー論文である。

対象となるHMIは：

* センターディスプレイ
* HUD
* 音声UI
* タッチUI
* ステアリングスイッチ
* ジェスチャ操作
* ADASインタフェース
* 自動運転HMI

など。

---

# 3. なぜ重要なのか？

近年の自動車は：

# Software Defined Vehicle（SDV）

化している。

つまり：

* 車 = ソフトウェア化
* UI中心化
* 大型ディスプレイ化

が急速に進んでいる。

その結果：

# HMI品質がUXを決定

する時代になった。

---

# 4. 論文の問題意識

論文では：

## Automotive UX研究が急増

している一方で、

* 評価方法がバラバラ
* 指標が統一されていない
* 生理信号活用が未成熟

という問題を指摘している。

---

# 5. レビュー対象

論文では多数のAutomotive UX研究を分析し、

以下を整理している。

| 分析対象  | 内容                 |
| ----- | ------------------ |
| 評価手法  | アンケート・行動・生理        |
| 実験環境  | 実車・シミュレータ          |
| UX指標  | SUS, NASA-TLX等     |
| HMI種類 | HUD, 音声UI等         |
| 生理指標  | ECG, Eye Tracking等 |

---

# 6. Automotive UXとは？

論文では：

# UX ≠ Usability

を強調している。

---

## Usability

使いやすさ。

例：

* 分かりやすい
* 操作しやすい
* エラー少ない

---

## UX

体験全体。

例：

* 快適
* 安心
* 楽しい
* 信頼感
* 没入感

---

# 7. 自動車HMI特有の難しさ

自動車UXは通常UIと違い：

* 安全性
* 認知負荷
* 視線移動
* 運転タスク
* 緊急性

が関係する。

つまり：

# 「使いやすい」だけでは不十分

である。

---

# 8. 主な評価手法

論文では評価手法を分類している。

---

## ① アンケート系

最も多い。

### 代表例

| 指標         | 内容              |
| ---------- | --------------- |
| SUS        | Usability       |
| UEQ        | UX全体            |
| AttrakDiff | Hedonic Quality |
| NASA-TLX   | 認知負荷            |

---

# 9. NASA-TLX

特に重要。

## 測定項目

* Mental Demand
* Physical Demand
* Temporal Demand
* Effort
* Frustration
* Performance

---

## Automotive UXとの相性

非常に良い。

理由：

# 運転中の認知負荷

を測れるため。

---

# 10. 行動観察系

論文では：

# Behavioral Analysis

も重要視。

---

## 例

* 視線移動
* タスク時間
* エラー数
* 操作回数
* 手の移動
* 迷い時間

---

# 11. Eye Tracking

自動車UXで急増中。

## なぜ重要？

運転中は：

# 視線逸脱 = 危険

だから。

---

## 測定例

| 指標                | 意味   |
| ----------------- | ---- |
| Fixation Duration | 注意集中 |
| Saccade           | 探索   |
| Glance Duration   | 視線逸脱 |
| Blink Rate        | 疲労   |

---

# 12. 生理指標系（超重要）

この論文の重要ポイント。

近年急増中。

---

## 使用される生理信号

| 信号          | 用途    |
| ----------- | ----- |
| ECG         | ストレス  |
| HRV         | 自律神経  |
| EEG         | 認知負荷  |
| NIRS        | 脳活動   |
| EDA         | 緊張    |
| Respiration | リラックス |
| Blink       | 疲労    |

---

# 13. なぜ生理信号が重要？

論文では：

# アンケートだけでは不十分

と強く指摘。

理由：

* ユーザーが気づかない
* 言語化できない
* 記憶が曖昧

ため。

---

# 14. Hidden UX

論文の重要概念。

## Hidden UXとは？

表面化しないUX。

例：

```text
本人：
「問題ない」
```

しかし：

* HRV低下
* EDA上昇

なら：

# 実際はストレス状態

かもしれない。

---

# 15. 実験環境

論文では：

## シミュレータ研究

が最も多いと報告。

---

## 理由

実車は：

* 危険
* 高コスト
* 再現性低い

ため。

---

# 16. シミュレータの利点

| 利点      | 内容     |
| ------- | ------ |
| 安全      | 危険無し   |
| 再現性     | 条件統一   |
| センサ設置容易 | EEG等   |
| 実験制御    | 条件変更可能 |

---

# 17. 一方で問題もある

シミュレータには：

# Ecological Validity問題

がある。

---

## つまり

実車と：

* 緊張感
* 振動
* 周囲環境

が違う。

---

# 18. 音声UI研究

論文では：

# Voice HMI

研究増加を指摘。

---

## 理由

運転中は：

* 手を使わない
* 視線逸脱少ない

ため。

---

# 19. しかし問題もある

音声UIは：

* 認識ミス
* 発話負荷
* タイミング問題

がある。

そのため：

# Cognitive Load評価

が重要。

---

# 20. ジェスチャUI

自動車ジェスチャ操作研究も増加。

---

## 評価ポイント

* 誤認識
* 疲労
* 学習コスト
* 認知負荷

など。

---

# 21. 自動運転UX

論文では：

# Automated Driving UX

研究急増も指摘。

---

## 特に重要なテーマ

* Trust（信頼）
* Situation Awareness
* Takeover Request
* Driver Monitoring

---

# 22. Trust（信頼）

自動運転で超重要。

例：

```text
信頼しすぎ
↓
危険
```

または：

```text
信頼しなさすぎ
↓
使わない
```

---

# 23. Driver Monitoring

現在急増中。

## 監視対象

* 視線
* 瞬目
* 姿勢
* 顔向き
* 心拍

など。

---

# 24. あなたの研究テーマとの関連

非常に近い。

特に：

* リクライニング姿勢
* HOT-2000
* 瞬目
* 呼吸
* ジェスチャ
* 快適性

は完全にこの分野。

---

# 25. リクライニングUXとの関係

例えば：

```text
リクライニング姿勢
↓
窓操作
↓
姿勢崩れる
↓
HRV低下
↓
UX悪化
```

など。

これは：

# Automotive Physiological UX

に属する。

---

# 26. 論文の重要な結論

論文最大の主張：

# マルチモーダルUX評価が必要

---

## つまり

単一指標では不十分。

必要なのは：

* アンケート
* 行動
* 生理信号

の統合。

---

# 27. 現在のトレンド

論文では以下を重要視。

| トレンド             | 内容     |
| ---------------- | ------ |
| Multimodal UX    | 多信号統合  |
| Real-time UX     | リアルタイム |
| Physiological UX | 生体信号   |
| Emotion-aware UX | 感情考慮   |
| AI-assisted UX   | AI支援   |
| Continuous UX    | 常時計測   |

---

# 28. AIとの統合

今後は：

* ECG
* EEG
* 視線
* 顔表情
* 呼吸

をAIへ入力し、

# 自動UX推定

へ進む可能性が高い。

---

# 29. 論文が指摘する課題

| 課題      | 内容        |
| ------- | --------- |
| 標準化不足   | 指標バラバラ    |
| 個人差     | 生理反応差     |
| 実車不足    | シミュレータ偏重  |
| データ統合困難 | マルチモーダル解析 |
| 倫理問題    | 生体データ     |

---

# 30. 今後重要になる指標

論文で特に重要視される。

| 指標             | 用途    |
| -------------- | ----- |
| HRV            | ストレス  |
| Blink          | 疲労    |
| Pupil Diameter | 認知負荷  |
| Respiration    | リラックス |
| Eye Tracking   | 注意    |
| Posture        | 快適性   |

---

# 31. この論文の本当に重要な点

最大のポイントは：

# Automotive UXが「感情・生理」へ進化している

こと。

従来：

```text
操作できた？
```

現在：

```text
快適だった？
安心した？
疲れた？
ストレスあった？
```

へ変化。

---

# 32. まとめ

この論文は、

> 「自動車HMI UX研究の全体像」

を整理した重要レビューである。

特に：

* Physiological UX
* Multimodal UX
* Driver Monitoring
* Emotion-aware UX

の重要性を強調している。

今後：

* SDV
* 自動運転
* AI HMI
* Emotion-aware Vehicle

時代において、

# UX評価は車両開発の中心

になる可能性が高い。

---

# 33. 重要キーワード

* Automotive UX
* HMI
* Driver Monitoring
* Physiological UX
* HRV
* Eye Tracking
* Cognitive Load
* Emotion-aware UX
* Human Factors
* Multimodal Interaction
