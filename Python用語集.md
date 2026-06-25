# Python 用語集・エラーメッセージ集

Pythonでのコーディング、特に機械学習・データ分析でよく出会う専門用語とエラーメッセージをまとめた用語集です。

---

## 目次

1. [Python 基本用語](#1-python-基本用語)
2. [オブジェクト指向・関数まわり](#2-オブジェクト指向関数まわり)
3. [よく出るエラーメッセージ（例外）](#3-よく出るエラーメッセージ例外)
4. [機械学習の基本用語](#4-機械学習の基本用語)
5. [データ分析の用語](#5-データ分析の用語)
6. [主要ライブラリ用語](#6-主要ライブラリ用語)
7. [機械学習・データ分析でよく出るエラー](#7-機械学習データ分析でよく出るエラー)
8. [GitHub の基本用語](#8-github-の基本用語)
9. [Git コマンド用語](#9-git-コマンド用語)
10. [GitHub・Git でよく出るエラーメッセージ](#10-githubgit-でよく出るエラーメッセージ)

---

## 1. Python 基本用語

| 用語 | 読み方 | 意味 |
| --- | --- | --- |
| **Variable（変数）** | バリアブル | 値を入れておく名前付きの入れ物。`x = 10` のように代入する。 |
| **Data Type（データ型）** | データタイプ | 値の種類。`int`（整数）、`float`（小数）、`str`（文字列）、`bool`（真偽値）など。 |
| **List（リスト）** | リスト | 順序を持つ可変の集合。`[1, 2, 3]`。 |
| **Tuple（タプル）** | タプル | 順序を持つ変更不可（immutable）の集合。`(1, 2, 3)`。 |
| **Dict（辞書）** | ディクショナリ | キーと値のペアの集合。`{"a": 1}`。 |
| **Set（集合）** | セット | 重複を許さない順序なしの集合。`{1, 2, 3}`。 |
| **Iterable（イテラブル）** | イテラブル | `for` で繰り返し処理できるオブジェクト。 |
| **Iterator（イテレータ）** | イテレータ | `next()` で順番に値を取り出せるオブジェクト。 |
| **Comprehension（内包表記）** | コンプリヘンション | `[x*2 for x in range(5)]` のような簡潔な生成構文。 |
| **Slice（スライス）** | スライス | `list[1:3]` のように一部を切り出す操作。 |
| **Indentation（インデント）** | インデンテーション | Pythonではブロックを字下げ（空白）で表す。 |
| **Mutable / Immutable** | ミュータブル / イミュータブル | 変更可能／変更不可能なオブジェクトの性質。 |
| **None** | ノン | 「値が存在しない」ことを表す特別な値。 |
| **f-string** | エフストリング | `f"{name}さん"` のように変数を埋め込める文字列。 |
| **PEP 8** | ペップエイト | Pythonの公式コーディング規約（スタイルガイド）。 |
| **Virtual Environment（仮想環境）** | バーチャルエンバイロメント | プロジェクトごとに独立したパッケージ環境（`venv`, `conda`）。 |
| **pip** | ピップ | Pythonのパッケージ管理ツール。`pip install numpy`。 |

---

## 2. オブジェクト指向・関数まわり

| 用語 | 意味 |
| --- | --- |
| **Function（関数）** | `def` で定義する処理のまとまり。 |
| **Argument（引数）** | 関数に渡す値。位置引数・キーワード引数がある。 |
| **Parameter（仮引数）** | 関数定義側で受け取る変数名。 |
| **Return value（戻り値）** | 関数が返す値。`return` で返す。 |
| **Lambda（ラムダ式）** | `lambda x: x+1` のような無名関数。 |
| **Decorator（デコレータ）** | `@` を使って関数に機能を追加する仕組み。 |
| **Class（クラス）** | オブジェクトの設計図。 |
| **Instance（インスタンス）** | クラスから生成された実体。 |
| **Method（メソッド）** | クラス内に定義された関数。 |
| **Attribute（属性）** | オブジェクトが持つデータ（変数）。 |
| **self** | メソッドの第1引数。インスタンス自身を指す。 |
| **`__init__`** | コンストラクタ。インスタンス生成時に呼ばれる初期化メソッド。 |
| **Inheritance（継承）** | 既存クラスの機能を引き継いで新しいクラスを作ること。 |
| **`*args` / `**kwargs`** | 可変長の位置引数 / キーワード引数。 |
| **Scope（スコープ）** | 変数が有効な範囲（ローカル / グローバル）。 |

---

## 3. よく出るエラーメッセージ（例外）

| エラー名 | 意味 | よくある原因と対処 |
| --- | --- | --- |
| **SyntaxError** | 文法エラー | 括弧やコロン `:` の閉じ忘れ、タイプミス。 |
| **IndentationError** | インデントエラー | 字下げのズレ。スペースとタブの混在に注意。 |
| **NameError** | 名前エラー | 未定義の変数・関数を使った。スペルミスや定義前の使用。 |
| **TypeError** | 型エラー | 型が合わない演算（例: `"a" + 1`）や引数の数違い。 |
| **ValueError** | 値エラー | 型は正しいが値が不適切（例: `int("abc")`）。 |
| **KeyError** | キーエラー | 辞書に存在しないキーを参照した。 |
| **IndexError** | インデックスエラー | リストの範囲外を参照した（例: 要素3個に `list[5]`）。 |
| **AttributeError** | 属性エラー | オブジェクトに存在しない属性・メソッドを呼んだ。 |
| **ImportError / ModuleNotFoundError** | インポートエラー | モジュールが見つからない。`pip install` 忘れ。 |
| **ZeroDivisionError** | ゼロ除算エラー | 0で割った。 |
| **FileNotFoundError** | ファイル未検出 | 指定したファイルパスが存在しない。 |
| **IndentationError: unexpected indent** | 予期しないインデント | 不要な字下げがある。 |
| **RecursionError** | 再帰エラー | 再帰が深すぎる（無限再帰など）。 |
| **RuntimeError** | 実行時エラー | 実行中の一般的なエラー。 |
| **UnboundLocalError** | 未束縛ローカル変数 | ローカル変数を代入前に参照した。 |
| **StopIteration** | 反復終了 | イテレータの要素が尽きた。 |
| **OverflowError** | オーバーフロー | 計算結果が表現できる範囲を超えた。 |
| **MemoryError** | メモリ不足 | メモリを使い切った。データ量を見直す。 |
| **PermissionError** | 権限エラー | ファイル/フォルダへのアクセス権がない。 |
| **EncodingError / UnicodeDecodeError** | 文字コードエラー | 文字エンコーディングの不一致。`encoding="utf-8"` を指定。 |

### エラーの読み方のコツ

- **Traceback（トレースバック）**: エラーが発生するまでの呼び出し履歴。**一番下** にエラーの種類とメッセージが出るので、まず最下行を読む。
- エラーメッセージ内のファイル名と行番号（`line 10` など）で発生箇所を特定する。
- `Exception` を握りつぶさず、メッセージをよく読むのが解決の近道。

---

## 4. 機械学習の基本用語

| 用語 | 意味 |
| --- | --- |
| **Machine Learning（機械学習）** | データからパターンを学習し予測・分類するアルゴリズムの総称。 |
| **Supervised Learning（教師あり学習）** | 正解ラベル付きデータで学習する手法（分類・回帰）。 |
| **Unsupervised Learning（教師なし学習）** | ラベルなしデータから構造を見つける手法（クラスタリングなど）。 |
| **Reinforcement Learning（強化学習）** | 報酬を最大化する行動を試行錯誤で学習する手法。 |
| **Feature（特徴量）** | モデルの入力となる変数・属性。 |
| **Label / Target（ラベル / 目的変数）** | 予測したい正解の値。 |
| **Training data（訓練データ）** | モデルの学習に使うデータ。 |
| **Test data（テストデータ）** | モデルの性能評価に使う未知のデータ。 |
| **Validation data（検証データ）** | ハイパーパラメータ調整に使うデータ。 |
| **Model（モデル）** | データから学習された予測の仕組み。 |
| **Classification（分類）** | カテゴリを予測するタスク（例: 犬か猫か）。 |
| **Regression（回帰）** | 連続値を予測するタスク（例: 価格予測）。 |
| **Clustering（クラスタリング）** | 似たデータをグループ分けする手法。 |
| **Overfitting（過学習）** | 訓練データに適合しすぎて未知データで性能が落ちること。 |
| **Underfitting（未学習）** | 学習が不十分でパターンを捉えきれていない状態。 |
| **Bias-Variance Tradeoff** | バイアス（偏り）とバリアンス（分散）のトレードオフ。 |
| **Hyperparameter（ハイパーパラメータ）** | 学習前に人が設定する値（学習率、木の深さなど）。 |
| **Parameter（パラメータ）** | 学習で自動調整される値（重みなど）。 |
| **Loss Function（損失関数）** | モデルの誤差を測る関数。これを最小化する。 |
| **Gradient Descent（勾配降下法）** | 損失を減らす方向にパラメータを更新する最適化手法。 |
| **Learning Rate（学習率）** | 1回の更新でパラメータをどれだけ動かすかの度合い。 |
| **Epoch（エポック）** | 訓練データ全体を1回学習し終える単位。 |
| **Batch（バッチ）** | 一度に処理するデータのまとまり。 |
| **Cross Validation（交差検証）** | データを分割し複数回評価して汎化性能を測る手法。 |
| **Confusion Matrix（混同行列）** | 分類結果の正誤を表にしたもの（TP/FP/FN/TN）。 |
| **Accuracy（正解率）** | 全体のうち正しく予測できた割合。 |
| **Precision（適合率）** | 陽性と予測したうち実際に陽性だった割合。 |
| **Recall（再現率）** | 実際の陽性のうち正しく陽性と予測できた割合。 |
| **F1 Score** | PrecisionとRecallの調和平均。 |
| **ROC / AUC** | 分類性能を評価する曲線とその下の面積。 |
| **Regularization（正則化）** | 過学習を防ぐためにモデルの複雑さに罰則を与える手法（L1/L2）。 |
| **Neural Network（ニューラルネットワーク）** | 脳の神経回路を模した機械学習モデル。 |
| **Deep Learning（深層学習）** | 多層のニューラルネットワークを使う手法。 |
| **Activation Function（活性化関数）** | ニューロンの出力を変換する関数（ReLU, Sigmoidなど）。 |

---

## 5. データ分析の用語

| 用語 | 意味 |
| --- | --- |
| **DataFrame（データフレーム）** | 表形式のデータ構造（pandasの中核）。 |
| **Series（シリーズ）** | 1次元のラベル付き配列（DataFrameの1列）。 |
| **Index（インデックス）** | 行・列を識別するためのラベル。 |
| **Missing Value（欠損値）** | データが欠けている部分（`NaN`）。 |
| **NaN（Not a Number）** | 数値ではない / 欠損を表す値。 |
| **Outlier（外れ値）** | 他から大きく外れた異常な値。 |
| **Normalization（正規化）** | 値を0〜1などの範囲にそろえる処理。 |
| **Standardization（標準化）** | 平均0・分散1にそろえる処理。 |
| **Encoding（エンコーディング）** | カテゴリ変数を数値に変換する処理（One-Hotなど）。 |
| **One-Hot Encoding** | カテゴリを0/1の複数列に展開する手法。 |
| **Feature Engineering（特徴量エンジニアリング）** | 予測に役立つ特徴量を作り出す作業。 |
| **EDA（探索的データ分析）** | データの傾向を可視化・集計して把握する作業。 |
| **Correlation（相関）** | 2つの変数の関係の強さ。 |
| **Distribution（分布）** | データの値の散らばり方。 |
| **Aggregation（集約）** | 合計・平均などにまとめる処理（`groupby`）。 |
| **Pivot（ピボット）** | データを縦横に並べ替えて集計する操作。 |
| **Merge / Join（結合）** | 複数のテーブルをキーで結合する操作。 |
| **Sampling（サンプリング）** | データから一部を抽出すること。 |
| **Imputation（補完）** | 欠損値を平均値などで埋める処理。 |
| **Dimensionality Reduction（次元削減）** | 特徴量の数を減らす手法（PCAなど）。 |

---

## 6. 主要ライブラリ用語

| ライブラリ | 用途 | 代表的な用語 |
| --- | --- | --- |
| **NumPy** | 数値計算 | `ndarray`（多次元配列）、`shape`（形状）、`dtype`（要素の型）、`axis`（軸）、ブロードキャスト。 |
| **pandas** | データ操作 | `DataFrame`、`Series`、`loc` / `iloc`（ラベル / 位置指定）、`groupby`、`merge`。 |
| **Matplotlib / seaborn** | 可視化 | `figure`、`axes`、`plot`、`subplot`、ヒストグラム、散布図。 |
| **scikit-learn** | 機械学習 | `fit`（学習）、`predict`（予測）、`transform`（変換）、`train_test_split`、`Pipeline`。 |
| **TensorFlow / Keras** | 深層学習 | `Tensor`（テンソル）、`layer`（層）、`model.compile`、`model.fit`。 |
| **PyTorch** | 深層学習 | `Tensor`、`autograd`（自動微分）、`nn.Module`、`optimizer`、`backward`。 |

### scikit-learn の基本パターン

```python
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = RandomForestClassifier()
model.fit(X_train, y_train)      # 学習
pred = model.predict(X_test)     # 予測
```

---

## 7. 機械学習・データ分析でよく出るエラー

| エラー / 警告 | 意味・原因 | 対処 |
| --- | --- | --- |
| **ValueError: could not convert string to float** | 文字列を数値に変換しようとした。カテゴリ変数が未処理。 | エンコーディングや欠損処理を行う。 |
| **ValueError: Found input variables with inconsistent numbers of samples** | `X` と `y` のサンプル数（行数）が一致しない。 | データの行数をそろえる。 |
| **ValueError: Input contains NaN** | 欠損値が含まれたまま学習しようとした。 | `fillna()` や `SimpleImputer` で補完する。 |
| **ValueError: shapes (a,b) and (c,d) not aligned** | 行列の形状が合わず計算できない。 | `shape` を確認して次元をそろえる。 |
| **ValueError: Expected 2D array, got 1D array instead** | scikit-learnに1次元配列を渡した。 | `X.reshape(-1, 1)` で2次元にする。 |
| **NotFittedError** | `fit` する前に `predict` / `transform` を呼んだ。 | 先に `fit` を実行する。 |
| **ConvergenceWarning** | 反復回数内に最適化が収束しなかった。 | `max_iter` を増やす、データを標準化する。 |
| **KeyError: '列名'** | DataFrameに存在しない列名を指定した。 | 列名のスペル・大文字小文字を確認。 |
| **SettingWithCopyWarning** | DataFrameのコピーに対して代入した可能性。 | `.loc[]` を使って明示的に代入する。 |
| **MemoryError** | データが大きすぎてメモリに乗らない。 | バッチ処理、データ型の縮小、サンプリング。 |
| **DtypeWarning: Columns have mixed types** | CSV読み込み時に列の型が混在。 | `dtype` を明示指定、`low_memory=False`。 |
| **RuntimeWarning: divide by zero / invalid value** | 0除算や `NaN` を含む数値計算。 | データの欠損・ゼロを確認する。 |
| **CUDA out of memory** | GPUメモリ不足（PyTorch / TensorFlow）。 | バッチサイズを小さくする、不要なテンソルを解放。 |
| **RuntimeError: Expected all tensors to be on the same device** | CPUとGPUのテンソルが混在（PyTorch）。 | `.to(device)` で統一する。 |

---

> **メモ:** エラーが出たら、まずは**メッセージの最終行**と**該当行番号**を確認しましょう。エラー名で検索すると解決策が見つかりやすいです。

---

## 8. GitHub の基本用語

| 用語 | 読み方 | 意味 |
| --- | --- | --- |
| **Git** | ギット | ソースコードの変更履歴を管理する分散型バージョン管理システム。 |
| **GitHub** | ギットハブ | Gitリポジトリをホスティングし、共同開発を支援するWebサービス。 |
| **Repository（リポジトリ）** | リポジトリ | プロジェクトのファイルと変更履歴を保管する場所。略して「リポ / repo」。 |
| **Local / Remote（ローカル / リモート）** | ローカル / リモート | 手元のPC上 / GitHubなどサーバー上のリポジトリ。 |
| **Commit（コミット）** | コミット | 変更内容を履歴として記録する単位。 |
| **Branch（ブランチ）** | ブランチ | 作業を分岐させる枝。`main` から派生して並行開発する。 |
| **main / master** | メイン / マスター | 既定の中心ブランチ名。 |
| **Merge（マージ）** | マージ | あるブランチの変更を別のブランチに統合すること。 |
| **Conflict（コンフリクト）** | コンフリクト | 同じ箇所を別々に変更しマージ時に衝突した状態。 |
| **Pull Request（プルリクエスト）** | プルリクエスト | 変更をレビューしてマージしてもらうための依頼。略して「PR」。 |
| **Fork（フォーク）** | フォーク | 他人のリポジトリを自分のアカウントに複製すること。 |
| **Clone（クローン）** | クローン | リモートリポジトリを手元に丸ごと複製すること。 |
| **Push（プッシュ）** | プッシュ | ローカルのコミットをリモートに送ること。 |
| **Pull（プル）** | プル | リモートの変更をローカルに取り込むこと（fetch + merge）。 |
| **Fetch（フェッチ）** | フェッチ | リモートの変更情報を取得するだけ（マージはしない）。 |
| **Stage / Staging（ステージング）** | ステージ | コミット対象として変更を一時的に登録する領域（index）。 |
| **Working Tree（作業ツリー）** | ワーキングツリー | 実際に編集しているファイル群の状態。 |
| **HEAD** | ヘッド | 現在チェックアウトしているコミット・ブランチを指すポインタ。 |
| **Origin（オリジン）** | オリジン | リモートリポジトリの既定の名前。 |
| **Upstream（アップストリーム）** | アップストリーム | フォーク元のオリジナルリポジトリ。 |
| **Tag（タグ）** | タグ | 特定のコミットに付ける目印（バージョン名など）。 |
| **Release（リリース）** | リリース | タグに紐づく配布版の公開単位。 |
| **Issue（イシュー）** | イシュー | バグ報告やタスク・要望を管理するチケット。 |
| **Gist（ジスト）** | ジスト | コード断片を手軽に共有できる仕組み。 |
| **README** | リードミー | プロジェクトの説明を書くファイル。 |
| **.gitignore** | ギットイグノア | Gitの管理対象から除外するファイルを指定する設定ファイル。 |
| **License（ライセンス）** | ライセンス | コードの利用条件を定めるファイル（MIT, Apacheなど）。 |
| **Star（スター）** | スター | リポジトリをお気に入り登録する機能。 |
| **Watch（ウォッチ）** | ウォッチ | リポジトリの更新通知を受け取る設定。 |
| **Actions（GitHub Actions）** | アクションズ | テストやデプロイを自動化するCI/CD機能。 |
| **CI/CD** | シーアイ / シーディー | 継続的インテグレーション / 継続的デリバリー（自動ビルド・テスト・配信）。 |
| **Wiki** | ウィキ | リポジトリに付属するドキュメント機能。 |
| **Collaborator（コラボレーター）** | コラボレーター | リポジトリへの書き込み権限を持つ共同作業者。 |
| **SSH Key / PAT** | エスエスエイチキー / パット | 認証に使う鍵 / 個人アクセストークン（Personal Access Token）。 |

---

## 9. Git コマンド用語

| コマンド | 意味 |
| --- | --- |
| `git init` | 新しいGitリポジトリを作成する。 |
| `git clone <URL>` | リモートリポジトリを複製する。 |
| `git status` | 変更状況（ステージ / 未追跡など）を確認する。 |
| `git add <file>` | 変更をステージングに追加する。`git add .` で全て。 |
| `git commit -m "メッセージ"` | ステージした変更をコミットする。 |
| `git push` | コミットをリモートに送る。 |
| `git pull` | リモートの変更を取り込む。 |
| `git fetch` | リモートの情報を取得する（マージしない）。 |
| `git branch` | ブランチの一覧表示 / 作成。 |
| `git checkout <branch>` / `git switch <branch>` | ブランチを切り替える。 |
| `git merge <branch>` | 指定ブランチを現在のブランチに統合する。 |
| `git log` | コミット履歴を表示する。 |
| `git diff` | 変更差分を表示する。 |
| `git reset` | ステージやコミットを取り消す。 |
| `git revert <commit>` | 指定コミットを打ち消す新しいコミットを作る。 |
| `git stash` | 作業中の変更を一時退避する。 |
| `git remote -v` | 登録済みリモートを確認する。 |
| `git rebase` | コミット履歴を整理・付け替えする。 |

---

## 10. GitHub・Git でよく出るエラーメッセージ

| エラー / メッセージ | 意味・原因 | 対処 |
| --- | --- | --- |
| **fatal: not a git repository** | Git管理下でないフォルダで `git` コマンドを実行した。 | `git init` するか、正しいディレクトリへ移動する。 |
| **fatal: remote origin already exists** | 既に `origin` が登録済みなのに再追加しようとした。 | `git remote set-url origin <URL>` で更新する。 |
| **fatal: repository '...' not found** | リモートURLが間違っている / 権限がない。 | URLとアクセス権を確認する。 |
| **Permission denied (publickey)** | SSH認証に失敗。鍵が未登録 / 不一致。 | SSHキーをGitHubに登録する。 |
| **Authentication failed** | 認証情報が誤り。パスワード認証は廃止済み。 | PAT（個人アクセストークン）を使う。 |
| **Updates were rejected because the remote contains work...** | リモートに自分が持っていない変更がある。 | 先に `git pull` してから `git push`。 |
| **error: failed to push some refs** | プッシュ拒否（上の理由が多い）。 | `git pull --rebase` 後に再プッシュ。 |
| **CONFLICT (content): Merge conflict in <file>** | マージ時に同じ箇所が衝突した。 | 該当ファイルを手動で修正し `git add` → `git commit`。 |
| **Your branch is ahead of 'origin/main' by N commits** | ローカルがリモートより進んでいる。 | `git push` で反映する。 |
| **Your branch is behind 'origin/main'...** | リモートが進んでいる。 | `git pull` で取り込む。 |
| **fatal: refusing to merge unrelated histories** | 履歴が無関係なリポジトリをマージしようとした。 | `git pull --allow-unrelated-histories`。 |
| **error: Your local changes would be overwritten by merge** | 未コミットの変更があり取り込めない。 | `git stash` か `git commit` してから取り込む。 |
| **detached HEAD state** | ブランチではなく特定コミットを直接見ている。 | `git switch -c <新ブランチ>` で枝を作る。 |
| **nothing to commit, working tree clean** | コミットする変更がない（エラーではない）。 | 変更を加えるか、状態を確認する。 |
| **fatal: The current branch has no upstream branch** | 追跡先リモートブランチが未設定。 | `git push -u origin <branch>` で設定する。 |
| **remote: Support for password authentication was removed** | パスワード認証が廃止された。 | PATまたはSSHを使う。 |
| **fatal: pathspec '...' did not match any files** | 指定したファイルが存在しない。 | ファイル名・パスを確認する。 |
| **large files detected / file is too large** | 100MB超のファイルをプッシュしようとした。 | Git LFSを使うか、ファイルを除外する。 |

### コンフリクト解消の流れ

1. `git status` で衝突ファイルを確認する。
2. ファイル内の `<<<<<<<` / `=======` / `>>>>>>>` マーカーを探す。
3. 残す内容を手動で編集し、マーカーを削除する。
4. `git add <file>` で解決済みにする。
5. `git commit`（マージの場合）で完了。

---

> **メモ:** GitHubのエラーは「認証」「リモートとの差分」「コンフリクト」の3パターンが大半です。まず `git status` で現状を確認するのが基本です。
