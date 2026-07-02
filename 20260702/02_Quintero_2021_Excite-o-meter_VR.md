# Quintero ら (2021): Excite-o-meter — VRに心臓活動を統合するソフトウェアフレームワーク

## 書誌情報
- **タイトル**: Excite-o-meter: Software framework to integrate heart activity in virtual reality
- **著者**: Luis Quintero, John E. Muñoz, Jeroen De Mooij ほか
- **出典**: 2021 IEEE International Symposium on Mixed and Augmented Reality (ISMAR)
- **URL (PDF)**: https://drive.google.com/file/d/1kzmZw9kUlJFRp5gKHUAL9U9lHBwsNrKL/view
- **被引用数**: 約23（2026年時点）

## 概要
VR（バーチャルリアリティ）体験の研究において、**心臓活動（心拍・HRV）をリアルタイムに取得・解析・可視化**するためのオープンソースフレームワーク「Excite-o-meter」を提案した論文。Unity上で動作し、市販の心拍センサー（Polar製チェストストラップ等）と連携して、VRコンテンツ体験中のユーザーの生理反応を記録できる。

## HRV（RMSSD / SDNN）の位置づけ
本研究の最大の特徴は、**「UX研究においてSDNNとRMSSDのどちらのHRV指標が適切か」を明示的に検討している**点にある。
- **SDNN**: 全体的な自律神経変動を反映。より長い計測窓が必要で、実験の各セグメントが十分長い場合に有効。
- **RMSSD**: 短時間計測でも比較的安定して算出でき、副交感神経（迷走神経）活動を反映。VRのような短いイベント単位の体験評価に適する。

論文では、この2つを **「UX研究のための候補HRV指標（candidate HRV measures）」** として位置づけ、それぞれの長所・短所と適用場面を整理している。これはまさに「RMSSD/SDNNでUXの良し悪しを評価する」というテーマに直接応える内容。

## 手法・システムのポイント
1. **リアルタイム取得**: VR体験中の心拍データをストリーミング取得し、HR・HRV指標を算出。
2. **オープンソース**: Unityアセットとして公開され、研究者が自分のVRコンテンツに容易に組み込める。
3. **イベント同期**: VR内のイベント（刺激提示など）と生理データを時間同期し、どの体験要素がどんな生理反応を引き起こしたかを分析可能。
4. **可視化**: 「興奮度（excitement）」を可視化するダッシュボードを提供。

## UX評価への示唆
- **VR・XR体験のUXを生理指標で定量化**する標準的ツールとして広く利用されている。
- SDNN vs RMSSD の選択指針を提供している点で、実験設計時の指標選定の参考文献として非常に有用。
- 短時間セグメント評価にはRMSSDが実用的、という実務的知見を提供。

## 引用の際のポイント
- 「VR/XRのUX研究でHRV指標を活用する標準フレームワーク」として引用可能。
- 「RMSSDとSDNNの使い分け」を論じる際の一次的根拠として利用できる。
