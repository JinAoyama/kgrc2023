# kgrc2023：構築したナレッジグラフ
[VirtualHome2KG](https://github.com/aistairc/VirtualHome2KG)を用いて2種類のナレッジグラフを構築（それぞれ6種類のアクティビティを表現するナレッジグラフを構築）
- [rdf/scene1](https://github.com/JinAoyama/kgrc2023/rdf/scene1)のturtleファイルはオブジェクトの3D座標とオブジェクトの3D座標とアクションの実行時間を記録せずに状態変化のみをシミュレーションしてナレッジグラフを生成したもの
- [rdf_with_bbox/scene1](https://github.com/JinAoyama/kgrc2023/rdf_with_bbox/scene1)のturtleファイルは3D座標とアクションの実行時間も記録してナレッジグラフを生成したもの

<br>

[rdf/scene1](https://github.com/JinAoyama/kgrc2023/rdf/scene1) のナレッジグラフの基本情報

| アクティビティ | トリプル数 | データサイズ |
| :---: | :---: | :---: |
| Browse internet | 15412 | 856 KB |
| Go to toilet | 10169 | 533 KB |
| Put groceries in fridge | 17285 | 1,062 KB |
| Read book | 17350 | 893 KB |
| Watch tv | 20920 | 1,068 KB |
| Work | 15467 | 738 KB |

<br>

[rdf_with_bbox/scene1](https://github.com/JinAoyama/kgrc2023/rdf_with_bbox/scene1) のナレッジグラフの基本情報

| アクティビティ | トリプル数 | データサイズ |
| :---: | :---: | :---: |
| Browse internet | 29895 | 972 KB |
| Go to toilet | 20282 | 644 KB |
| Put groceries in fridge | 33159 | 1,158 KB |
| Read book | 33113 | 1,021 KB |
| Watch tv | 39527 | 1,209 KB |
| Work | 30157 | 884 KB |

<br>

※ ナレッジグラフ構築のために生成したVirtualHomeのデータセット（アクティビティ、アクティビティの説明文、アクションスクリプトの組）は、[dataset/scene1](https://github.com/JinAoyama/kgrc2023/dataset/scene1) に公開
