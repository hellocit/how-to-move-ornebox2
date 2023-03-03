# how-to-move-ornebox2
## ハードウェアの起動からwaypoints navigationの起動までの手順
1. 主電源（トグルスイッチ）を入れる．
2. GIGABYTEの電源を入れる．
3. 有線LANでノートPCとbox2の背面にあるLANポートをつなぐ．
4. VNC Viewerを用いてGIGABYTEに接続する．
5. ~/scripts/*.shを用いてwaypoint navigationの起動する.

## 地図生成
* bringupを立ち上げてからgmapping.launchを立ち上げる.
* 以下のコマンドを実行して保存
```
rosrun map_server mapsaver -f "フルパスでファイル指定＋名前指定"
```

## ウェイポイントの配置
* 
* 

## ナビゲーション
* 
* 
## 運用上してはいけないこと
* 主電源を入れたまま放置すること
  * バッテリーが上がってしまう．
* GIGABYTEと無線WiFiを接続すること
  * 状況をみるにVNC Viewerとの相性が悪い？

## 気をつけること
* たまにBIOSのboot装置の優先順位が変わることがある．
  * ディスプレイを用いて状況を確認し，BIOSに入ってbootの順番を入れ替える．
