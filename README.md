# kgrc2023：構築したナレッジグラフ
[VirtualHome2KG](https://github.com/aistairc/VirtualHome2KG)を用いて2種類のナレッジグラフを構築（それぞれ6種類のアクティビティを表現するナレッジグラフを構築）
- [rdf/scene1](https://github.com/JinAoyama/kgrc2023/tree/main/rdf/scene1)のturtleファイルはオブジェクトの3D座標とアクションの実行時間を記録せずに状態変化のみをシミュレーションしてナレッジグラフを生成したもの
- [rdf_with_bbox/scene1](https://github.com/JinAoyama/kgrc2023/tree/main/rdf_with_bbox/scene1)のturtleファイルは3D座標とアクションの実行時間も記録してナレッジグラフを生成したもの

<br>

[rdf/scene1](https://github.com/JinAoyama/kgrc2023/tree/main/rdf/scene1) のナレッジグラフの基本情報

| アクティビティ | トリプル数 | データサイズ |
| :---: | :---: | :---: |
| Browse internet | 15,412 | 856 KB |
| Go to toilet | 10,169 | 533 KB |
| Put groceries in fridge | 17,285 | 1,062 KB |
| Read book | 17,350 | 893 KB |
| Watch tv | 20,920 | 1,068 KB |
| Work | 15,467 | 738 KB |

<br>

[rdf_with_bbox/scene1](https://github.com/JinAoyama/kgrc2023/tree/main/rdf_with_bbox/scene1) のナレッジグラフの基本情報

| アクティビティ | トリプル数 | データサイズ |
| :---: | :---: | :---: |
| Browse internet | 29,895 | 972 KB |
| Go to toilet | 20,282 | 644 KB |
| Put groceries in fridge | 33,159 | 1,158 KB |
| Read book | 33,113 | 1,021 KB |
| Watch tv | 39,527 | 1,209 KB |
| Work | 30,157 | 884 KB |

<br>

※ ナレッジグラフ構築のために生成したVirtualHomeのデータセット（アクティビティ、アクティビティの説明文、アクションスクリプトの組）は、[dataset/scene1](https://github.com/JinAoyama/kgrc2023/tree/main/dataset/scene1) に公開
