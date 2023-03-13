# 現状の状況
## 日程
* https://docs.google.com/spreadsheets/d/1LMHDco09aONliOvSGXYFmmSMs0BjXtmgS7KEwsbJ1ho/edit#gid=0
## 津田沼チャレンジの目的(必須課題)
* ⾃律⾛⾏：スタートからゴールまで、約 1661 m の課題コースを⾃律⾛⾏すること
## 選択課題
* 事前データ取得なし⾛⾏：コース地図に⽰す2 号館1 階内を、事前データ取得なしで⾛⾏すること
* 探索対象発⾒：探索エリアで、探索対象であるマネキンを発⾒すること

## 現状出ている課題と解決しなければならないこと
* 6号館空き具合
* 目的：よい占有格子地図を生成するためには環境が静的であるほうがよい
  * このディレクトリにあるIMG_7445.jpgを参照のこと
  * 3/10午前と3/11すべてが比較的６号館の１階が使われていない日
  * これら２つの日以外は学会等で使用されていることが多い．

* gmappingで地図を生成したところあまりうまく行かなかった．
  * その解決策として次の3個の策がある．
    1. gmappingのパラメータ変更による地図生成
    2. cartgrapherを用いた地図生成
       1. 2Dか3DのSLAM
          1. 2Dの問題点
             1. 2DSLAMのパラメータが今井くんが持っているalpha用のパラメータ
          2. 3Dの問題点
             1. 性能の高いデスクトップPCが必要である．また，付録に示すPCでは厳しいとの指摘があった．しかし，中村のPC1を用いることでcartgrapherのデモは動かすことができた．

## 使用しているcartgrapherのURL
## ルール
* https://drive.google.com/file/d/1-QobU4ehfqgEPXchh3RPPVXsEuUhCAIm/view
# References
1. https://sites.google.com/p.chibakoudai.jp/rdc-lab/development/tsudanuma-challenge
2. kari

# Appendix
1. PC1
Core i7-11800H
RTX 3050 Laptop
メモリ
32GB
2. PC2
AMD Ryzen 9 5900HX プロセッサー ( 8コア / 16スレッド / 3.3GHz / ブースト時最大4.6GHz / L3キャッシュ16MB )
32GB メモリ [16GB×2 ( DDR4-3200 ) / デュアルチャネル ]
NVIDIA GeForce RTX 3060 Laptop GPU / GDDR6 6GB