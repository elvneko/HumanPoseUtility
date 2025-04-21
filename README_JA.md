# Human Pose Utility

![デモ](/doc/hpu_demo.jpg)

## 名前空間

```cs
using HumanPoseUtil;
```

## スクリプト

```cs
// キャラクターにポーズを適用
public static void ApplyHumanPose(Animator animator, HumanPose pose);
// キャラクターからポーズを取得
public static HumanPose ExtractHumanPose(Animator animator);
```

## デモシーンについて

利用法をわかりやすくするために、3Dキャラクターとファイルブラウザに関する無料アセットを内包しています。

![デモ動画](/doc/demo.gif)

* [Unity-Chan! Model](https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705?aid=1011liAjm)
* [Runtime File Browser](https://assetstore.unity.com/packages/tools/gui/runtime-file-browser-113006?aid=1011liAjm)

ご自身のプロダクトにとって不要なアセットは削除し、プロダクトに応じて実装をしていただけると幸いです。

## Links

UnityのHumanPoseHandlerを扱いやすいようにラッピングしたパッケージです。

Unityの公式ドキュメントはこちらを参照ください。

* [HumanPoseHandler](https://docs.unity.cn/ScriptReference/HumanPoseHandler.html)
* [HumanPose](https://docs.unity.cn/ScriptReference/HumanPose.html)

![UnityChan](/doc/imageLicenseLogo.png)
