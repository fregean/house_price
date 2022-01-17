# house_price


## 欠損値処理 1/15 1/17

### Discution

テストデータセットの欠落データの処理
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/35968

行方不明の値の代入
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/41682

「LotFrontage」で欠落している値を処理するにはどうすればよいですか？
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/50085


第1回KaggleCompeititionから学んだ教訓
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/40391
- 

データ漏洩を伴う上位1％のスコア
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/117853
- 特にトップ1〜20％のスコアを主張するノートブックはトレーニングセットとテストセットを連結している

'Fence'の値がありません
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/discussion/160538
- <img width="924" alt="スクリーンショット 2022-01-18 8 01 12" src="https://user-images.githubusercontent.com/31781305/149845772-bc0e61c7-ce8f-4762-b195-f128a09828d9.png">
- 意味のある欠損値と意味のない欠損値を分ける
<img width="932" alt="スクリーンショット 2022-01-18 8 12 57" src="https://user-images.githubusercontent.com/31781305/149846463-6925a77f-3545-4578-bbf4-00988f77b576.png">
- 「Fence」が重要でない場合、全てを一緒にドロップすると、分散が減少し、過剰にフィットするため、より正確なモデルが得られる場合があります。
