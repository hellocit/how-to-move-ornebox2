# how-to-move-ornebox2
## ハードウェアの起動からwaypoints navigationの起動までの手順
1. 主電源（トグルスイッチ）を入れる．
2. GIGABYTEの電源を入れる．
3. 有線LANでノートPCとbox2の背面にあるLANポートをつなぐ．
4. VNC Viewerを用いてGIGABYTEに接続する．
5. ~/scripts/*.shを用いてwaypoint navigationの起動する

## 運用上してはいけないこと
* 主電源を入れたまま放置すること
  * バッテリーが上がってしまう．
* GIGABYTEと無線WiFiを接続すること
  * 状況をみるにVNC Viewerとの相性が悪い？

## 気をつけること
* たまにBIOSのboot装置の優先順位が変わることがある．
  * ディスプレイを用いて状況を確認し，BIOSに入ってbootの順番を入れ替える．