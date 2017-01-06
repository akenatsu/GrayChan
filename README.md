# GrayChan

「らりほま式 Gray ちゃん」ver.0.5.0の.blendの改変版です。
私がアニメーションを作成しやすいように、主にRig周りを弄っています

```
Note: テクスチャ等は含みません。

blender上でテクスチャが適用された改変版Grayちゃんモデルを確認したい場合は、
らりほまさんのところからのver.0.5.0をDLして、
解凍したフォルダ内にGrayChan_v05x.blendを入れて確認してみてください。
テクスチャが参照されるはずです。
```

## ダウンロード

下記の画像のように「Download ZIP」からダウンロードして、

![dl_link](https://github.com/akenatsu/GrayChan/blob/master/img/dl_graychan.jpg "ダウンロードリンク")

展開して含まれている「GrayChan_v05x.blend」をご利用ください


```
Note: その他の.blendファイルをご利用したい場合は、git/git-lfsを用いて別途ダウンロードしてください
```

## ライセンス

「らりほま式 Gray ちゃん」のライセンスに準じます。詳細は[rarilog][page]を確認ください

[page]: http://rarihoma.xvs.jp/products/graychan/


## 参考資料

* blenderのFBX exportとUE4のFBX importの方法について
  - [Blender で作ったアニメーションを Unreal Engine 4 で利用する](http://www.slideshare.net/rarihoma/blender-step1)

## TODO

* [x] changelog書く
* [ ] Rig修正(手と頭のIK回り)
* [ ] idleアニメーション追加
* [ ] walk/run/jumpアニメーションの見直し

## changelog

* ver.0.5.12
  - アニメーション追加
    + [x] walk => DopeSheet/ActionEditor/Walk.005
	+ [x] run  => DopeSheet/ActionEditor/RunAnime.004
	+ [ ] idle
	+ [x] jump => DopeSheet/ActionEditor/GrayChanAction.004
  - アニメーション選択とトリミング
    + [x] NLA Editor対応
* ver.0.5.11
  - Rig改造
    + [ ] 腕から手首回り
* ver.0.5.7 - 0.5.10
  - Rig改造
    + [x] 胸と腰回り
* ver.0.5.5 - 0.5.6
  - スカートの物理シミュレーション模索
* ver.0.5.4
  - CustomShape追加
    + 胸と腰辺り
* ver.0.5.3
  - 腰ボーン修正
* ver.0.5.1
  - お尻まわりのリトポ
* ver.0.3.1-0.3.2
  - Rig改造
    + ver0.5のRigVerUpが出たので終わり
