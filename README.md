# house_price


## 欠損値処理 1/15 1/17

## Discussion

### 欠測値の網羅的なガイド!!!
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/253225
- Handle Missing Values Only NoteBook you Need（ノートブック）
  - https://www.kaggle.com/rushikeshdarge/handle-missing-values-only-notebook-you-need
<img width="977" alt="スクリーンショット 2022-01-18 8 30 06" src="https://user-images.githubusercontent.com/31781305/149847451-cdcb4de5-ed4f-4df1-9375-2f40dd3c68c2.png">




### 'Fence'の値がありません
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/160538
<img width="924" alt="スクリーンショット 2022-01-18 8 01 12" src="https://user-images.githubusercontent.com/31781305/149845772-bc0e61c7-ce8f-4762-b195-f128a09828d9.png">
意味のある欠損値と意味のない欠損値を分ける
<img width="932" alt="スクリーンショット 2022-01-18 8 12 57" src="https://user-images.githubusercontent.com/31781305/149846463-6925a77f-3545-4578-bbf4-00988f77b576.png">
「Fence」が重要でない場合、全てを一緒にドロップすると、分散が減少し、過剰にフィットするため、より正確なモデルが得られる場合があります。

### 「LotFrontage」で欠落している値を処理するにはどうすればよいですか？
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/50085


### データ漏洩を伴う上位1％のスコア
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/117853
- 特にトップ1〜20％のスコアを主張するノートブックはトレーニングセットとテストセットを連結している


### テストデータセットの欠落データの処理
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/35968
- テストデータセット内の各IDを予測することになっているため、テストデータセット内の欠落データを処理する方法について混乱しています。これにより、テストデータセット内の行を削除できなくなります。
また、列車内の欠落データを処理し、データセットを同じ方法でテストするかどうかも知りたいと思います。
<img width="1196" alt="スクリーンショット 2022-01-18 11 55 19" src="https://user-images.githubusercontent.com/31781305/149862891-dd9c3a47-fa15-4304-9272-c135249714aa.png">


### 行方不明の値の代入
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/41682

### 第1回KaggleCompeititionから学んだ教訓
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/40391




