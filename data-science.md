# データサイエンス

## catboost
### 概要
- ロシアで一番大きい検索エンジン企業が作った
- GBDT(決定木ベースの勾配ブースティング)の一派

### 特徴
- 回帰と分類どっちもOK
- カテゴリカル変数（質的変数）の処理が上手い
- 過学習が起こりにくい
- Light GBMと張っている

## GBDT
### 概要
- G: Gradient(勾配)
- B: Boosting(ブースティング) = アンサンブル手法の1つ
- D: Decision(決定)
- T: Tree(木)

https://www.acceluniverse.com/blog/developers/2019/12/gbdt.html

### 勾配降下法
- 精度の誤差を最小化させる手法

### Boosting(ブースティング)
- 精度の低い学習器を組み合わせて精度を上げる
- 3人寄らば文殊の知恵
