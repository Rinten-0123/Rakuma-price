# Rakuma-price
Rakuma price
使用したデータ：https://drive.google.com/file/d/1vYDjLScvRtAiZHQPuThGaqTjs3p_kzkC/view
ラクマの価格推定モデルの作成
苦労した点：初めての回帰モデルの作成で、パラメータの設定や、評価指標の決定に苦労した。また、価格の幅や同じような名前やジャンルでも値段の大きく異なるものがあり、精度の良いモデルを作ることが難しかった。
工夫した点：商品名は個人がつけた物なので、自然言語処理を行う際に不要な記号や文字が含まれている。これらがあると、精度が下がる恐れがあるため、商品名から記号を削除、半角、全角処理を行ってからCountVectorizerでベクトル化を行った。
