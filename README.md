# 3班　中間発表の目標
## アームで任意のトランプを引く
**１．やること**
- 複数枚立ててあるトランプから一枚選んで引き、投げる
---

**２．面白い点**
- この動きの発展形として人間vsロボットでトランプを使ったゲームができるのではないかと思ったから
---
**３．使用する道具**
- crane_x7
- トランプ
- トランプを支えるスタンド
---

**４．どういう構成のシステムを作るか**
1. アームの初期座標から指定した座標までいく
2. アームを開きトランプをつかむ
3. トランプを持ち上げる
4. 投げる（他の動きになるかも）

rqt_graphで表すと

![rosgraph_and_all_topic](https://user-images.githubusercontent.com/72371137/96333811-f2429f00-10a6-11eb-8638-32c6d6ce6cc9.png)

---
**５．考えられる問題**
- アームでトランプをつかめない（トランプが滑るなど)
  - アームの先端にゴム製のものをつける
- スケジュール通りに進まない
  - 予備日で帳尻合わせをする
--- 

**６．スケジュール**

**課題１** (10月25日まで)
- 指定した座標までアームを動かすプログラムの作成 /担当：伊奈、川鍋
- トランプをつかむ、離す動きのプログラムの作成(サンプル参考に) /担当：清原

**課題２** (11月1日まで)
- トランプをつかんだ後の動作のプログラムの作成  /担当：庄垣、長谷川
- シミュレーター上で使うトランプ、台の作製（作り方調べる、TAに聞く）  /担当：藤原

**課題３** (11月8日まで)
- 課題1.2の動作のプログラムのマージする

**課題４** (11月12日まで)
- 一連の動作が安定してできるように調整

**課題５**(11月13日まで） 
- 中間発表の資料作り

![３スケジュール](https://user-images.githubusercontent.com/72371743/96401488-6e0b2b80-120e-11eb-940b-f50a8e18b90f.png)
