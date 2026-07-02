# Peruzzini ら (2018): 生理データモニタリングと混合プロトタイピングによるUX分析

## 書誌情報
- **タイトル**: User experience analysis based on physiological data monitoring and mixed prototyping to support human-centre product design
- **著者**: Margherita Peruzzini, Fabio Grandi, Marcello Pellicciari
- **出典**: *Advances in Ergonomics in Design* (AHFE 2018), Springer, pp. 401–412
- **DOI/URL**: https://link.springer.com/chapter/10.1007/978-3-319-94706-8_44
- **被引用数**: 約22（2026年時点）

## 概要
人間中心設計（Human-Centred Design, HCD）のプロセスにおいて、ユーザーが製品を使用する際の **UX（ユーザー体験）を客観的・定量的に測定する**ための方法論を提案した研究。従来のUX評価がアンケートやインタビューといった主観的手法に偏っていた点を課題とし、**生理指標（physiological data）と混合プロトタイピング（mixed prototyping）を組み合わせる**ことで、ユーザーの無意識的・非言語的な反応を捉えることを狙う。

## HRV（RMSSD / SDNN）の位置づけ
本研究では、心拍変動（Heart Rate Variability, HRV）を主要な生理指標の一つとして採用している。
- **SDNN**: 正常拍動間隔（Normal-to-Normal, NN間隔）の標準偏差。全体的な自律神経活動（交感神経＋副交感神経）を反映する指標として利用。
- **RMSSD**: 隣接するNN間隔の差の二乗平均平方根。**副交感神経（迷走神経）活動**を強く反映し、リラックス／回復状態の指標として利用。

これらを、心拍数（HR）や皮膚電気活動（GSR/EDA）などと併用し、ユーザーがプロトタイプを操作する際の **ストレス・認知負荷・快適性** を推定している。UXが良好な（＝ストレスの少ない、直感的に使える）設計では、RMSSD やHRVが相対的に高く保たれるという解釈枠組みを採る。

## 手法のポイント
1. **Mixed Prototyping（混合プロトタイピング）**: 物理モックアップとバーチャル（VR/AR）要素を組み合わせ、実製品に近い操作体験を安価に再現。
2. **マルチモーダル生理計測**: HRV（SDNN, RMSSD）、心拍数、呼吸、皮膚電気活動などを同期取得。
3. **主観評価との統合**: 生理データと主観的UX評価（アンケート）を突き合わせ、設計改善点を特定。

## UX評価への示唆
- **客観指標としてのHRVの有効性**: 主観アンケートでは拾いきれない微細なストレス・不快感を、SDNN/RMSSDの低下として検出できる可能性を示した。
- **設計プロセスへの組み込み**: 製品開発の早期段階（プロトタイプ）でUXを定量評価し、手戻りを減らす枠組みを提示した点が実務的に重要。

## 引用の際のポイント
- 「HRV（特にSDNNとRMSSD）を製品UX評価の客観指標として用いた初期の代表的事例」として引用できる。
- 人間中心設計・エルゴノミクス分野での生理計測導入の根拠文献として有用。
