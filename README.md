# kisopuro2025

## File Description
```
.
├── README.md
├── data
│   ├── input
│   │   ├── input.csv                                 # 入力データ。movementをベースに作成されたcsv。
│   │   └── input_without_Taiwan.csv                  # input.csvからTaiwanを含む行を削除したファイル。
│   └── output
│       ├── centralities
│       │   ├── centrality.csv                        # input.csvの中心性指標（媒介中心性、固有ベクトル中心性）
│       │   └── centrality_without_Taiwan.csv         # input_without_Taiwan.csvの中心性指標
│       ├── change_betweenness_df_groupby_country.csv # change_betweenness.csvを国ごとに集計
│       ├── change_eigenvector_df_groupby_country.csv # change_eigenvector.csvを国ごとに集計
│       └── changes
│           ├── change_betweenness.csv                # 媒介中心性指標がTaiwanを消す前後でどう変わったか
│           └── change_eigenvector.csv                # 固有ベクトル中心性指標がTaiwanを消す前後でどう変わったか
└── main.ipynb                                        # 分析を行うファイル
```