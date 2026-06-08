あります！しかもここ2～3年の流れを見ると、

> 「UXを1つのアンケートスコアで表す」

から

> 「主観＋行動＋生理信号＋AIを統合したUX Value Scoreを作る」

方向へ大きくシフトしています。

上野さんの研究テーマ（自動車UX、HOT-2000、呼吸、瞬目、生理信号）に近いものを厳選すると、次の文献がかなり参考になります。

---

# ① Physiological Data for User Experience and Quality of Experience: A Systematic Review (2024)

([Taylor & Francis Online][1])

## なぜ重要？

この論文は、

* ECG
* HRV
* EEG
* EDA
* Eye Tracking
* 呼吸

などの生理指標を用いたUX評価研究を体系的にレビューしています。([Taylor & Francis Online][1])

---

## 面白い点

論文の結論として、

> 単一アンケートだけではUXを十分に説明できず、複数の生理信号と主観評価を組み合わせるべき

という流れが明確に示されています。([Taylor & Francis Online][1])

これは実質的に

```text
UX Score
=
主観評価
+
生理指標
```

の方向です。

---

# ② Breaking the Bias (2025)

以前お話しした論文です。

---

## なぜ重要？

UX研究者の判断精度を

* 自己申告
* 生理データ

の統合で向上させる研究。

---

## 実質的な提案

```text
UX Accuracy Score

=
Self Report
+
HRV
+
EDA
+
Behavior
```

という考え方です。

これは「UX価値の総合スコア化」の代表例に近いです。

---

# ③ ECG-Based AI Emotion Recognition for User Journey Mapping (2026)

これも以前紹介した論文です。

---

## 面白い点

UXを

```text
満足
```

ではなく

```text
感情の時系列
```

として扱っています。

---

### イメージ

```text
Journey UX Value

=
Emotion(t)
+
Stress(t)
+
Task Success(t)
```

---

将来的なUXスコアの形にかなり近いです。

---

# ④ User Experience Estimation in Human-Robot Interaction Via Multi-Instance Learning of Multimodal Social Signals (2025)

([arXiv][2])

---

## 個人的にかなり注目

この論文は

> UXをAIで推定する

研究です。([arXiv][2])

入力は

* 顔表情
* 音声

などのマルチモーダル信号。

---

### 出力

```text
UX Score
```

を推定。

---

これは

```text
人間が採点
↓
AIが学習
↓
UX自動採点
```

の流れです。([arXiv][2])

---

# ⑤ UX Measurement Practices Review (2024)

([Frontiers][3])

---

## 内容

CHI論文などのUX研究を大量調査。

---

### 結論

研究者は実際には

```text
SUS
+
NASA-TLX
+
行動ログ
```

のように複数指標を組み合わせている。([Frontiers][3])

---

## 示唆

未来のUX評価は

```text
Composite UX Index
```

になる可能性が高い。

---

# 上野さんのテーマに一番近い研究の方向

実は最近のトップ会議や論文では、

**UXI（User Experience Index）そのものを改良する研究よりも、**

```text
UX Value Score

=
主観評価
+
行動データ
+
生理信号
+
AI感情推定
```

という

**Multimodal UX Score**

へ進んでいます。([Taylor & Francis Online][1])

---

# もし論文化を狙うなら

上野さんの

* HOT-2000（脳血流）
* 呼吸
* 瞬目
* リクライニング姿勢
* 窓スイッチ操作

を使って、

```text
Rear Seat UX Value Index (RS-UXI)

=
0.25 × 主観満足度
+
0.20 × 操作成功率
+
0.15 × HRV
+
0.15 × 脳血流
+
0.10 × 呼吸
+
0.10 × 瞬目
+
0.05 × 姿勢安定性
```

のような指標を作る研究は、2026年時点でもかなり新規性があります。

特に自動車後席UXに限定した「生理信号込みのUX価値スコア」は、まだ研究例がかなり少ない分野です。

[1]: https://www.tandfonline.com/doi/full/10.1080/10447318.2024.2311972?utm_source=chatgpt.com "Physiological Data for User Experience and Quality of Experience: A Systematic Review (2018–2022): International Journal of Human–Computer Interaction: Vol 41 , No 1 - Get Access"
[2]: https://arxiv.org/abs/2507.23544?utm_source=chatgpt.com "User Experience Estimation in Human-Robot Interaction Via Multi-Instance Learning of Multimodal Social Signals"
[3]: https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1368860/full?utm_source=chatgpt.com "Frontiers | Measurement practices in user experience (UX) research: a systematic quantitative literature review"
