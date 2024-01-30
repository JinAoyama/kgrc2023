# kgrc2023で構築したナレッジグラフ
2種類のナレッジグラフを構築（それぞれ6種類のアクティビティを表現するナレッジグラフを構築）
- [rdf/scene1](https://github.com/JinAoyama/kgrc2023/rdf/scene1)のturtleファイルはオブジェクトの3D座標とオブジェクトの3D座標とアクションの実行時間を記録せずに状態変化のみをシミュレーションしてナレッジグラフを生成したもの
- [rdf_with_bbox/scene1](https://github.com/JinAoyama/kgrc2023/rdf_with_bbox/scene1)のturtleファイルは3D座標とアクションの実行時間も記録してナレッジグラフを生成したもの
詳しい生成方法は[https://github.com/aistairc/VirtualHome2KG](https://github.com/aistairc/VirtualHome2KG)を参照

ナレッジグラフ構築のために生成したVirtualHomeのデータセット（アクティビティ、アクティビティの説明文、アクションスクリプトの組）は[dataset/scene1](https://github.com/JinAoyama/kgrc2023/dataset/scene1)に公開
