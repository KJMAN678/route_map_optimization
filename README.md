## streamlitでデプロイ中(2021/5/16時点)
https://share.streamlit.io/kjman678/route_map_optimization/main/map.py

<img width="960" alt="2021-05-16_12h22_39" src="https://user-images.githubusercontent.com/45703844/118384525-9e4e6780-b641-11eb-8679-7a45aa02bbc1.png">

- サイドバー で移動手段の台数（仮にヘリとしている）を1～4、異動する拠点を出発点の東京含め1～25まで変更して最適なルートを算定し地図上にルートを表示。
- Google の ORTools を使用
https://developers.google.com/optimization
