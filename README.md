MMD Shader for Unity
========

### Preview ###

<img src="http://3dcgarts.github.com/MMD-Shader-for-Unity/images/material_preview.png">


### 使い方 ###

Unityパッケージである

```
PMDMaterials.unitypackage
```

を、Unityのメニューの

```
Assets->Import Package->Custom Package...
```

からインポートしてください。

シェーダは以下の４つが用意されています。

```
MMD/PMDMaterial
MMD/PMDMaterial-with-Outline
MMD/Transparent/PMDMaterial
MMD/Transparent/PMDMaterial-with-Outline
```

Transparent とついているものは、透明な材質に使ってください。

Outline     とついているものは、輪郭線を表示する材質に使ってください。

### その他 ###

シェーダに割り当てられているプロパティは、PMDEditor の値に準拠しています。

MikuMikuDance の表示に最も近くなるのは Directional Light (Color: White) の光源を受けている時であるように設計されています。

「Lat式ミク」のような特殊なメッシュ構造を持ったモデルも正しく表示することができます。

