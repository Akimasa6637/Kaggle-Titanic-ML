# **Titanic - Machine Learning from Disaster**  
## ◇ プロジェクト概要
Kaggleコンペティション「Titanic - Machine Learning from Disaster」のデータを用いて、  
生存予測モデルの構築に取り組んだプロジェクトです。  
Baselineモデルの作成を起点に、  
EDA(探索的データ分析)、特徴エンジニアリング、モデル選定、ハイパーパラメータの調整などを通じて、  
予測精度の向上とモデルの解釈性の向上を目指しました。  

コンペティションページ  
=> [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)  

## ◇ 実施内容
- Baselineモデルの構築(LightGBM)
- 交差検証による学習と評価
- 単一モデルによるアンサンブル学習
- EDAによるデータの可視化と仮説立案
- 特徴量エンジニアリング
- モデル選定: CatBoostの採用
- ハイパーパラメータ最適化
- NNによる分類モデルの構築
- Kaggle提出スコア (Public LB): Baseline **0.77751**, Main **0.78708**, NN **0.75358**  

## ◇ ファイル構成
- Titanic_Main.ipynb: 基準となるベースラインモデル
- Titanic_Baseline.ipynb: EDA・特徴量設計・CatBoostによる最終モデル
- Titanic_NN.ipynb: 深層学習の手法を取り入れた実験的・理解促進のための検証モデル
- README.md: 本ファイル。プロジェクトの概要や構成を記載

#### ▽ 検証モデル: ニューラルネットワーク(MLP)について  
LightGBMやCatBoostによる精度評価・改善とは別に、  
**実験的・理解促進のための検証モデル**として、MLPを実装いたしました。  
本モデルは最終スコア向上を目的としたものではなく、  
**深層学習の知識定着** および **他手法との比較理解** を目的としています。

## ◇ ノートブック実行リンク
- Titanic_Main.ipynb (最終モデル・CatBoost使用)  
  => [Google Colabで開く](https://colab.research.google.com/drive/12oMqZPmN-YnR89Npmka2QeoN4cIVNAPO?usp=drive_link)
- Titanic_Baseline.ipynb (初期ベースラインモデル)  
  => [Google Colabで開く](https://colab.research.google.com/drive/1wV6OvXCQD2ehuVn_F_0RVp6atlrSg1af?usp=drive_link)  
- Titanic_NN.ipynb (MLPを用いた検証モデル)  
  => [Google Colabで開く](https://colab.research.google.com/drive/1j6aJKPAmfLwFQmdcU1Yyu8MNoln-VsUO?usp=drive_link)  

> ※ 実行には 'kaggle.json' のアップロードが必要です。

## ◇ 学び・得られたこと
- 深層学習の経験を経たうえで、改めて機械学習に取り組んだことで、  
「やっぱりMLって楽しい！」という原点の気づきを得ることができました。  
以前よりスムーズにコードを書けるようになり、構造の理解が深まっていたことから、  
自身の成長を実感する機会にもなりました。  

- 多くのKaggleコンペに参加する中で、Titanicコンペの奥深さと、  
「実力を問われる構成」であることを改めて体感しました。  
長年多くの参加者から支持され続けている理由も、実際に取り組んでみて深く理解できました。

- 今回の取り組みを通じて、スコアへのこだわりや分析の深さも強まり、  
Titanicコンペにおいて「0.80超え」を本気で目指す姿勢が生まれました。  
手ごたえを感じられる取り組みとなり、今後の学習にもつながる自信となりました。
  
- 実験的に深層学習を取り入れたことで、「MLらしい検証方法」への理解が深まり、  
SKFoldの適用、汎化性能を意識した工夫など、  
これまでの経験と結びつけながら取り組むことができました。
  
---
最後までご覧いただき、ありがとうございました。  
本プロジェクトを通じて得た学びや気づきが、今後のさらなる成長と挑戦につながるよう、  
引き続き取り組んでまいります。  