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
4. 投げるor離す（他の動きになるかも）
---
rqt_graphだと

![rosgraph_and_all_topic](https://user-images.githubusercontent.com/72371137/96333811-f2429f00-10a6-11eb-8638-32c6d6ce6cc9.png)

![rosgraph_node_only](https://user-images.githubusercontent.com/72371137/96333832-2a49e200-10a7-11eb-9a51-f4d494581c12.png)
---

**５．スケジュール**

**課題１** (10月26日まで)
- 指定した座標までアームを動かすプログラムの制作
- トランプをつかむ、離す動きのプログラムの制作(サンプル参考に)

**課題２** (11月2日まで)
- トランプをつかんだ後の動作のプログラムの制作
- シミュレーター上で使うトランプ、台の作成（作り方調べる、TAに聞く）

**課題３** (11月9日まで)
- 課題1.2の動作のプログラムのマージする

**課題４** (11月16日まで)
- 一連の動作が安定してできるように調整

**課題５**(11月16日まで） 
- 中間発表の資料作り

![設計制作論３中間スケジュール](https://user-images.githubusercontent.com/72371743/96359774-a1d44b80-1151-11eb-98cc-54ca1e90ea24.png)

