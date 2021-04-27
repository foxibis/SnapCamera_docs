# 導入方法
[ユニティちゃんトゥーンシェーダー2.0](https://unity-chan.com/download/releaseNote.php?id=UTS2_0)(必須) + DynamicBoneを予めインポートしてください。

SnapCamera.unitypackageをインポート後、Assets > SnapCamera内に各種データが格納されています。


## VirtualLens2
__必ずろじらぼ様の[セットアップガイド](http://static.logicmachine.jp/vlens2/docs/setup/)をご覧になってセットアップを行って下さい。__ 以下、補足です。

- VirtualLens2を利用される方は __SnapCamera_VirtualLens.prefab__ を利用して下さい。

- Virtual Lens SettingsのCamera Objectでは、Root Objectに `SnapCamera_VirtualLens` をNon-Preview RootにSnapCamera_Meshを設定して下さい。

- Hideable MeshesにSnapCamera_Meshを設定するとカメラモデルの非表示表示オプションが使えるようになります。

## VRCLens
__必ずひらびきWORKS様の[ドキュメント](https://vrchat.com/home/world/wrld_85bfeefb-78b8-444c-b4e8-15698fb7864d)をご覧になってからセットアップを行って下さい。__ 以下、補足です。

- VRCLensを利用される方は __SnapCamera.prefab__ をSceneに配置後、調整はせず(Position/RotationがXYZ0の状態)セットアップにてChange Camera Modelを押して下さい。その後VRC Lens SetupにてScaleなど調整して下さい。

- 個人的に使用しているパラメーターを添付するので参考にどうぞ

# 更新履歴
| Data       | Version | About |
|:----------:|:-------:|:------|
| 2020/09/30 | 1.0     |       |
| 2020/11/13 | 2.0     | モデルデーターを変更しました。(見た目は変わりません) <br> UV見直しに伴いテクスチャが大幅に変更されています。 <br> PSDを追加 <br> ストラップ(DynamicBoneセットアップ済)を追加 |
| 2021/04/27 | 2.1     | Boneを修正したため以前とDynamicBoneの挙動が変わっています <br> Prefab内構造を見直しセットアップがしやすくなっています <br> オンラインドキュメントを追加 |

# 規約
基本的に良識の範囲内でご利用いただければ問題ありません。

VN3ライセンスを採用しています。詳しくは[コチラ](https://drive.google.com/file/d/17SH3o9QpT2s8uz86N5zk5N1bJwi0FS5h/view?usp=sharing)

# お問い合わせ
本モデルデーターに関して不具合や質問等などございましたら下記へご連絡下さい。

Twitter [@FoxIbis](https://twitter.com/foxibis)

Discord ふぉっくす#9951