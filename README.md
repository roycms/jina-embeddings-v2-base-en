---
tags:
  - finetuner
  - mteb
  - sentence-transformers
  - feature-extraction
  - sentence-similarity
  - alibi
datasets:
  - allenai/c4
language: en
license: apache-2.0
model-index:
- name: jina-embedding-b-en-v2
  results:
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_counterfactual
      name: MTEB AmazonCounterfactualClassification (en)
      config: en
      split: test
      revision: e8379541af4e31359cca9fbcf4b00f2671dba205
    metrics:
    - type: accuracy
      value: 73.4179104477612
    - type: ap
      value: 35.798378234524705
    - type: f1
      value: 67.27708504551819
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_polarity
      name: MTEB AmazonPolarityClassification
      config: default
      split: test
      revision: e2d317d38cd51312af73b3d32a06d1a08b442046
    metrics:
    - type: accuracy
      value: 88.977575
    - type: ap
      value: 85.00359027707599
    - type: f1
      value: 88.9585285941142
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_reviews_multi
      name: MTEB AmazonReviewsClassification (en)
      config: en
      split: test
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
    metrics:
    - type: accuracy
      value: 44.455999999999996
    - type: f1
      value: 42.80615676169829
  - task:
      type: Retrieval
    dataset:
      type: arguana
      name: MTEB ArguAna
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 18.919
    - type: map_at_10
      value: 33.272
    - type: map_at_100
      value: 34.669
    - type: map_at_1000
      value: 34.68
    - type: map_at_3
      value: 28.011000000000003
    - type: map_at_5
      value: 30.767
    - type: mrr_at_1
      value: 19.061
    - type: mrr_at_10
      value: 33.352
    - type: mrr_at_100
      value: 34.75
    - type: mrr_at_1000
      value: 34.760999999999996
    - type: mrr_at_3
      value: 28.07
    - type: mrr_at_5
      value: 30.848
    - type: ndcg_at_1
      value: 18.919
    - type: ndcg_at_10
      value: 42.138
    - type: ndcg_at_100
      value: 48.165
    - type: ndcg_at_1000
      value: 48.435
    - type: ndcg_at_3
      value: 31.041
    - type: ndcg_at_5
      value: 36.015
    - type: precision_at_1
      value: 18.919
    - type: precision_at_10
      value: 7.098
    - type: precision_at_100
      value: 0.9740000000000001
    - type: precision_at_1000
      value: 0.1
    - type: precision_at_3
      value: 13.276
    - type: precision_at_5
      value: 10.384
    - type: recall_at_1
      value: 18.919
    - type: recall_at_10
      value: 70.982
    - type: recall_at_100
      value: 97.44
    - type: recall_at_1000
      value: 99.502
    - type: recall_at_3
      value: 39.829
    - type: recall_at_5
      value: 51.92
  - task:
      type: Clustering
    dataset:
      type: mteb/arxiv-clustering-p2p
      name: MTEB ArxivClusteringP2P
      config: default
      split: test
      revision: a122ad7f3f0291bf49cc6f4d32aa80929df69d5d
    metrics:
    - type: v_measure
      value: 45.38238451470738
  - task:
      type: Clustering
    dataset:
      type: mteb/arxiv-clustering-s2s
      name: MTEB ArxivClusteringS2S
      config: default
      split: test
      revision: f910caf1a6075f7329cdf8c1a6135696f37dbd53
    metrics:
    - type: v_measure
      value: 37.12265635737745
  - task:
      type: Reranking
    dataset:
      type: mteb/askubuntudupquestions-reranking
      name: MTEB AskUbuntuDupQuestions
      config: default
      split: test
      revision: 2000358ca161889fa9c082cb41daa8dcfb161a54
    metrics:
    - type: map
      value: 62.473921100678695
    - type: mrr
      value: 75.28195488721803
  - task:
      type: STS
    dataset:
      type: mteb/biosses-sts
      name: MTEB BIOSSES
      config: default
      split: test
      revision: d3fb88f8f02e40887cd149695127462bbcf29b4a
    metrics:
    - type: cos_sim_pearson
      value: 84.46030780641742
    - type: cos_sim_spearman
      value: 83.29647627997147
    - type: euclidean_pearson
      value: 83.63127685751004
    - type: euclidean_spearman
      value: 83.29647627997147
    - type: manhattan_pearson
      value: 83.29505322210208
    - type: manhattan_spearman
      value: 82.8398393691656
  - task:
      type: Classification
    dataset:
      type: mteb/banking77
      name: MTEB Banking77Classification
      config: default
      split: test
      revision: 0fd18e25b25c072e09e0d92ab615fda904d66300
    metrics:
    - type: accuracy
      value: 83.94480519480521
    - type: f1
      value: 83.26406143364741
  - task:
      type: Clustering
    dataset:
      type: mteb/biorxiv-clustering-p2p
      name: MTEB BiorxivClusteringP2P
      config: default
      split: test
      revision: 65b79d1d13f80053f67aca9498d9402c2d9f1f40
    metrics:
    - type: v_measure
      value: 37.15926312173139
  - task:
      type: Clustering
    dataset:
      type: mteb/biorxiv-clustering-s2s
      name: MTEB BiorxivClusteringS2S
      config: default
      split: test
      revision: 258694dd0231531bc1fd9de6ceb52a0853c6d908
    metrics:
    - type: v_measure
      value: 31.20469085642121
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackAndroidRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 28.462
    - type: map_at_10
      value: 39.834
    - type: map_at_100
      value: 41.329
    - type: map_at_1000
      value: 41.465
    - type: map_at_3
      value: 36.586999999999996
    - type: map_at_5
      value: 38.239000000000004
    - type: mrr_at_1
      value: 34.335
    - type: mrr_at_10
      value: 45.493
    - type: mrr_at_100
      value: 46.323
    - type: mrr_at_1000
      value: 46.37
    - type: mrr_at_3
      value: 42.870999999999995
    - type: mrr_at_5
      value: 44.502
    - type: ndcg_at_1
      value: 34.335
    - type: ndcg_at_10
      value: 46.434
    - type: ndcg_at_100
      value: 52.013
    - type: ndcg_at_1000
      value: 54.079
    - type: ndcg_at_3
      value: 41.408
    - type: ndcg_at_5
      value: 43.562
    - type: precision_at_1
      value: 34.335
    - type: precision_at_10
      value: 8.913
    - type: precision_at_100
      value: 1.439
    - type: precision_at_1000
      value: 0.197
    - type: precision_at_3
      value: 20.029
    - type: precision_at_5
      value: 14.335
    - type: recall_at_1
      value: 28.462
    - type: recall_at_10
      value: 59.574000000000005
    - type: recall_at_100
      value: 82.631
    - type: recall_at_1000
      value: 95.45700000000001
    - type: recall_at_3
      value: 45.381
    - type: recall_at_5
      value: 51.18000000000001
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackEnglishRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 27.245
    - type: map_at_10
      value: 37.156
    - type: map_at_100
      value: 38.464999999999996
    - type: map_at_1000
      value: 38.607
    - type: map_at_3
      value: 34.613
    - type: map_at_5
      value: 35.924
    - type: mrr_at_1
      value: 34.777
    - type: mrr_at_10
      value: 43.425000000000004
    - type: mrr_at_100
      value: 44.163000000000004
    - type: mrr_at_1000
      value: 44.211
    - type: mrr_at_3
      value: 41.391
    - type: mrr_at_5
      value: 42.461
    - type: ndcg_at_1
      value: 34.777
    - type: ndcg_at_10
      value: 42.807
    - type: ndcg_at_100
      value: 47.629
    - type: ndcg_at_1000
      value: 49.84
    - type: ndcg_at_3
      value: 39.28
    - type: ndcg_at_5
      value: 40.671
    - type: precision_at_1
      value: 34.777
    - type: precision_at_10
      value: 8.134
    - type: precision_at_100
      value: 1.3599999999999999
    - type: precision_at_1000
      value: 0.186
    - type: precision_at_3
      value: 19.320999999999998
    - type: precision_at_5
      value: 13.286999999999999
    - type: recall_at_1
      value: 27.245
    - type: recall_at_10
      value: 52.491
    - type: recall_at_100
      value: 73.065
    - type: recall_at_1000
      value: 86.931
    - type: recall_at_3
      value: 41.257
    - type: recall_at_5
      value: 45.811
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackGamingRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 37.088
    - type: map_at_10
      value: 49.003
    - type: map_at_100
      value: 50.017999999999994
    - type: map_at_1000
      value: 50.07899999999999
    - type: map_at_3
      value: 45.846
    - type: map_at_5
      value: 47.733
    - type: mrr_at_1
      value: 42.193999999999996
    - type: mrr_at_10
      value: 52.522999999999996
    - type: mrr_at_100
      value: 53.177
    - type: mrr_at_1000
      value: 53.205999999999996
    - type: mrr_at_3
      value: 49.916
    - type: mrr_at_5
      value: 51.50900000000001
    - type: ndcg_at_1
      value: 42.193999999999996
    - type: ndcg_at_10
      value: 54.99699999999999
    - type: ndcg_at_100
      value: 59.058
    - type: ndcg_at_1000
      value: 60.355000000000004
    - type: ndcg_at_3
      value: 49.515
    - type: ndcg_at_5
      value: 52.412000000000006
    - type: precision_at_1
      value: 42.193999999999996
    - type: precision_at_10
      value: 8.84
    - type: precision_at_100
      value: 1.1820000000000002
    - type: precision_at_1000
      value: 0.134
    - type: precision_at_3
      value: 21.944
    - type: precision_at_5
      value: 15.197
    - type: recall_at_1
      value: 37.088
    - type: recall_at_10
      value: 69.13
    - type: recall_at_100
      value: 86.612
    - type: recall_at_1000
      value: 95.946
    - type: recall_at_3
      value: 54.76
    - type: recall_at_5
      value: 61.76199999999999
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackGisRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 21.816
    - type: map_at_10
      value: 30.630000000000003
    - type: map_at_100
      value: 31.641000000000002
    - type: map_at_1000
      value: 31.730999999999998
    - type: map_at_3
      value: 28.153
    - type: map_at_5
      value: 29.433
    - type: mrr_at_1
      value: 23.842
    - type: mrr_at_10
      value: 32.432
    - type: mrr_at_100
      value: 33.354
    - type: mrr_at_1000
      value: 33.421
    - type: mrr_at_3
      value: 30.131999999999998
    - type: mrr_at_5
      value: 31.358000000000004
    - type: ndcg_at_1
      value: 23.842
    - type: ndcg_at_10
      value: 35.626000000000005
    - type: ndcg_at_100
      value: 40.855999999999995
    - type: ndcg_at_1000
      value: 43.111
    - type: ndcg_at_3
      value: 30.712
    - type: ndcg_at_5
      value: 32.912
    - type: precision_at_1
      value: 23.842
    - type: precision_at_10
      value: 5.627
    - type: precision_at_100
      value: 0.873
    - type: precision_at_1000
      value: 0.11100000000000002
    - type: precision_at_3
      value: 13.333
    - type: precision_at_5
      value: 9.266
    - type: recall_at_1
      value: 21.816
    - type: recall_at_10
      value: 49.370000000000005
    - type: recall_at_100
      value: 73.855
    - type: recall_at_1000
      value: 90.67399999999999
    - type: recall_at_3
      value: 35.85
    - type: recall_at_5
      value: 41.282000000000004
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackMathematicaRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 14.402000000000001
    - type: map_at_10
      value: 21.401999999999997
    - type: map_at_100
      value: 22.425
    - type: map_at_1000
      value: 22.561
    - type: map_at_3
      value: 19.238
    - type: map_at_5
      value: 20.213
    - type: mrr_at_1
      value: 17.91
    - type: mrr_at_10
      value: 25.629999999999995
    - type: mrr_at_100
      value: 26.529999999999998
    - type: mrr_at_1000
      value: 26.616
    - type: mrr_at_3
      value: 23.362
    - type: mrr_at_5
      value: 24.438
    - type: ndcg_at_1
      value: 17.91
    - type: ndcg_at_10
      value: 26.161
    - type: ndcg_at_100
      value: 31.474000000000004
    - type: ndcg_at_1000
      value: 34.802
    - type: ndcg_at_3
      value: 21.965
    - type: ndcg_at_5
      value: 23.511000000000003
    - type: precision_at_1
      value: 17.91
    - type: precision_at_10
      value: 4.8629999999999995
    - type: precision_at_100
      value: 0.869
    - type: precision_at_1000
      value: 0.129
    - type: precision_at_3
      value: 10.655000000000001
    - type: precision_at_5
      value: 7.5120000000000005
    - type: recall_at_1
      value: 14.402000000000001
    - type: recall_at_10
      value: 36.760999999999996
    - type: recall_at_100
      value: 60.549
    - type: recall_at_1000
      value: 84.414
    - type: recall_at_3
      value: 25.130000000000003
    - type: recall_at_5
      value: 29.079
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackPhysicsRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 26.176
    - type: map_at_10
      value: 35.789
    - type: map_at_100
      value: 37.092000000000006
    - type: map_at_1000
      value: 37.206
    - type: map_at_3
      value: 33.207
    - type: map_at_5
      value: 34.436
    - type: mrr_at_1
      value: 31.569000000000003
    - type: mrr_at_10
      value: 41.219
    - type: mrr_at_100
      value: 42.016999999999996
    - type: mrr_at_1000
      value: 42.065000000000005
    - type: mrr_at_3
      value: 39.012
    - type: mrr_at_5
      value: 40.22
    - type: ndcg_at_1
      value: 31.569000000000003
    - type: ndcg_at_10
      value: 41.515
    - type: ndcg_at_100
      value: 47.125
    - type: ndcg_at_1000
      value: 49.314
    - type: ndcg_at_3
      value: 37.201
    - type: ndcg_at_5
      value: 38.906
    - type: precision_at_1
      value: 31.569000000000003
    - type: precision_at_10
      value: 7.517
    - type: precision_at_100
      value: 1.225
    - type: precision_at_1000
      value: 0.161
    - type: precision_at_3
      value: 17.485
    - type: precision_at_5
      value: 12.089
    - type: recall_at_1
      value: 26.176
    - type: recall_at_10
      value: 53.076
    - type: recall_at_100
      value: 77.049
    - type: recall_at_1000
      value: 91.51
    - type: recall_at_3
      value: 40.82
    - type: recall_at_5
      value: 45.479
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackProgrammersRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 22.675
    - type: map_at_10
      value: 31.752999999999997
    - type: map_at_100
      value: 33.19
    - type: map_at_1000
      value: 33.303
    - type: map_at_3
      value: 28.89
    - type: map_at_5
      value: 30.451
    - type: mrr_at_1
      value: 27.854
    - type: mrr_at_10
      value: 36.736999999999995
    - type: mrr_at_100
      value: 37.783
    - type: mrr_at_1000
      value: 37.836
    - type: mrr_at_3
      value: 34.266000000000005
    - type: mrr_at_5
      value: 35.577999999999996
    - type: ndcg_at_1
      value: 27.854
    - type: ndcg_at_10
      value: 37.391999999999996
    - type: ndcg_at_100
      value: 43.682
    - type: ndcg_at_1000
      value: 46.005
    - type: ndcg_at_3
      value: 32.66
    - type: ndcg_at_5
      value: 34.73
    - type: precision_at_1
      value: 27.854
    - type: precision_at_10
      value: 6.963
    - type: precision_at_100
      value: 1.184
    - type: precision_at_1000
      value: 0.159
    - type: precision_at_3
      value: 15.715000000000002
    - type: precision_at_5
      value: 11.256
    - type: recall_at_1
      value: 22.675
    - type: recall_at_10
      value: 49.15
    - type: recall_at_100
      value: 76.542
    - type: recall_at_1000
      value: 92.19000000000001
    - type: recall_at_3
      value: 35.607
    - type: recall_at_5
      value: 41.288000000000004
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 23.214499999999997
    - type: map_at_10
      value: 31.979833333333335
    - type: map_at_100
      value: 33.20666666666666
    - type: map_at_1000
      value: 33.328583333333334
    - type: map_at_3
      value: 29.341416666666664
    - type: map_at_5
      value: 30.718083333333336
    - type: mrr_at_1
      value: 27.328583333333338
    - type: mrr_at_10
      value: 35.88433333333333
    - type: mrr_at_100
      value: 36.80075000000001
    - type: mrr_at_1000
      value: 36.86175
    - type: mrr_at_3
      value: 33.51625
    - type: mrr_at_5
      value: 34.821416666666664
    - type: ndcg_at_1
      value: 27.328583333333338
    - type: ndcg_at_10
      value: 37.24475
    - type: ndcg_at_100
      value: 42.63825
    - type: ndcg_at_1000
      value: 45.08266666666667
    - type: ndcg_at_3
      value: 32.61783333333334
    - type: ndcg_at_5
      value: 34.631249999999994
    - type: precision_at_1
      value: 27.328583333333338
    - type: precision_at_10
      value: 6.5873333333333335
    - type: precision_at_100
      value: 1.094916666666667
    - type: precision_at_1000
      value: 0.15091666666666664
    - type: precision_at_3
      value: 15.073499999999997
    - type: precision_at_5
      value: 10.651916666666667
    - type: recall_at_1
      value: 23.214499999999997
    - type: recall_at_10
      value: 49.010250000000006
    - type: recall_at_100
      value: 72.70374999999999
    - type: recall_at_1000
      value: 89.66041666666666
    - type: recall_at_3
      value: 36.06008333333334
    - type: recall_at_5
      value: 41.289166666666674
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackStatsRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 23.497
    - type: map_at_10
      value: 29.176000000000002
    - type: map_at_100
      value: 30.218
    - type: map_at_1000
      value: 30.317
    - type: map_at_3
      value: 27.072000000000003
    - type: map_at_5
      value: 28.162
    - type: mrr_at_1
      value: 25.919999999999998
    - type: mrr_at_10
      value: 31.513
    - type: mrr_at_100
      value: 32.434000000000005
    - type: mrr_at_1000
      value: 32.507000000000005
    - type: mrr_at_3
      value: 29.576
    - type: mrr_at_5
      value: 30.45
    - type: ndcg_at_1
      value: 25.919999999999998
    - type: ndcg_at_10
      value: 32.958999999999996
    - type: ndcg_at_100
      value: 37.937
    - type: ndcg_at_1000
      value: 40.455000000000005
    - type: ndcg_at_3
      value: 28.969
    - type: ndcg_at_5
      value: 30.552
    - type: precision_at_1
      value: 25.919999999999998
    - type: precision_at_10
      value: 5.106999999999999
    - type: precision_at_100
      value: 0.8170000000000001
    - type: precision_at_1000
      value: 0.11100000000000002
    - type: precision_at_3
      value: 12.117
    - type: precision_at_5
      value: 8.373999999999999
    - type: recall_at_1
      value: 23.497
    - type: recall_at_10
      value: 42.506
    - type: recall_at_100
      value: 65.048
    - type: recall_at_1000
      value: 83.545
    - type: recall_at_3
      value: 31.078
    - type: recall_at_5
      value: 35.018
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackTexRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 15.267
    - type: map_at_10
      value: 22.292
    - type: map_at_100
      value: 23.412
    - type: map_at_1000
      value: 23.543
    - type: map_at_3
      value: 19.993
    - type: map_at_5
      value: 21.256
    - type: mrr_at_1
      value: 18.445
    - type: mrr_at_10
      value: 25.698999999999998
    - type: mrr_at_100
      value: 26.682
    - type: mrr_at_1000
      value: 26.764
    - type: mrr_at_3
      value: 23.446
    - type: mrr_at_5
      value: 24.757
    - type: ndcg_at_1
      value: 18.445
    - type: ndcg_at_10
      value: 26.833000000000002
    - type: ndcg_at_100
      value: 32.151999999999994
    - type: ndcg_at_1000
      value: 35.235
    - type: ndcg_at_3
      value: 22.597
    - type: ndcg_at_5
      value: 24.585
    - type: precision_at_1
      value: 18.445
    - type: precision_at_10
      value: 4.942
    - type: precision_at_100
      value: 0.894
    - type: precision_at_1000
      value: 0.135
    - type: precision_at_3
      value: 10.735999999999999
    - type: precision_at_5
      value: 7.915
    - type: recall_at_1
      value: 15.267
    - type: recall_at_10
      value: 37.198
    - type: recall_at_100
      value: 60.748999999999995
    - type: recall_at_1000
      value: 82.72699999999999
    - type: recall_at_3
      value: 25.419000000000004
    - type: recall_at_5
      value: 30.416999999999998
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackUnixRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 22.839000000000002
    - type: map_at_10
      value: 31.287
    - type: map_at_100
      value: 32.474
    - type: map_at_1000
      value: 32.586
    - type: map_at_3
      value: 28.735
    - type: map_at_5
      value: 30.11
    - type: mrr_at_1
      value: 26.959
    - type: mrr_at_10
      value: 34.943000000000005
    - type: mrr_at_100
      value: 35.957
    - type: mrr_at_1000
      value: 36.022
    - type: mrr_at_3
      value: 32.572
    - type: mrr_at_5
      value: 33.952
    - type: ndcg_at_1
      value: 26.959
    - type: ndcg_at_10
      value: 36.252
    - type: ndcg_at_100
      value: 41.915
    - type: ndcg_at_1000
      value: 44.461
    - type: ndcg_at_3
      value: 31.532
    - type: ndcg_at_5
      value: 33.674
    - type: precision_at_1
      value: 26.959
    - type: precision_at_10
      value: 6.166
    - type: precision_at_100
      value: 1.01
    - type: precision_at_1000
      value: 0.134
    - type: precision_at_3
      value: 14.302999999999999
    - type: precision_at_5
      value: 10.131
    - type: recall_at_1
      value: 22.839000000000002
    - type: recall_at_10
      value: 47.796
    - type: recall_at_100
      value: 72.68
    - type: recall_at_1000
      value: 90.556
    - type: recall_at_3
      value: 34.955000000000005
    - type: recall_at_5
      value: 40.293
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackWebmastersRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 21.676000000000002
    - type: map_at_10
      value: 30.742000000000004
    - type: map_at_100
      value: 32.332
    - type: map_at_1000
      value: 32.548
    - type: map_at_3
      value: 27.560000000000002
    - type: map_at_5
      value: 29.331000000000003
    - type: mrr_at_1
      value: 25.099
    - type: mrr_at_10
      value: 34.538999999999994
    - type: mrr_at_100
      value: 35.629
    - type: mrr_at_1000
      value: 35.687000000000005
    - type: mrr_at_3
      value: 31.621
    - type: mrr_at_5
      value: 33.419
    - type: ndcg_at_1
      value: 25.099
    - type: ndcg_at_10
      value: 36.741
    - type: ndcg_at_100
      value: 42.964
    - type: ndcg_at_1000
      value: 45.754
    - type: ndcg_at_3
      value: 31.356
    - type: ndcg_at_5
      value: 33.934999999999995
    - type: precision_at_1
      value: 25.099
    - type: precision_at_10
      value: 7.115
    - type: precision_at_100
      value: 1.46
    - type: precision_at_1000
      value: 0.23800000000000002
    - type: precision_at_3
      value: 14.954
    - type: precision_at_5
      value: 11.067
    - type: recall_at_1
      value: 21.676000000000002
    - type: recall_at_10
      value: 49.546
    - type: recall_at_100
      value: 76.544
    - type: recall_at_1000
      value: 94.39999999999999
    - type: recall_at_3
      value: 34.67
    - type: recall_at_5
      value: 41.528999999999996
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackWordpressRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 17.431
    - type: map_at_10
      value: 24.694
    - type: map_at_100
      value: 25.884
    - type: map_at_1000
      value: 25.996999999999996
    - type: map_at_3
      value: 22.203
    - type: map_at_5
      value: 23.329
    - type: mrr_at_1
      value: 19.039
    - type: mrr_at_10
      value: 26.459
    - type: mrr_at_100
      value: 27.560000000000002
    - type: mrr_at_1000
      value: 27.636
    - type: mrr_at_3
      value: 24.03
    - type: mrr_at_5
      value: 25.213
    - type: ndcg_at_1
      value: 19.039
    - type: ndcg_at_10
      value: 29.220000000000002
    - type: ndcg_at_100
      value: 34.854
    - type: ndcg_at_1000
      value: 37.580999999999996
    - type: ndcg_at_3
      value: 24.218999999999998
    - type: ndcg_at_5
      value: 26.125
    - type: precision_at_1
      value: 19.039
    - type: precision_at_10
      value: 4.861
    - type: precision_at_100
      value: 0.826
    - type: precision_at_1000
      value: 0.116
    - type: precision_at_3
      value: 10.290000000000001
    - type: precision_at_5
      value: 7.394
    - type: recall_at_1
      value: 17.431
    - type: recall_at_10
      value: 41.525
    - type: recall_at_100
      value: 67.121
    - type: recall_at_1000
      value: 87.575
    - type: recall_at_3
      value: 27.794
    - type: recall_at_5
      value: 32.332
  - task:
      type: Retrieval
    dataset:
      type: climate-fever
      name: MTEB ClimateFEVER
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 10.767
    - type: map_at_10
      value: 17.456
    - type: map_at_100
      value: 19.097
    - type: map_at_1000
      value: 19.272
    - type: map_at_3
      value: 14.530000000000001
    - type: map_at_5
      value: 15.943999999999999
    - type: mrr_at_1
      value: 23.583000000000002
    - type: mrr_at_10
      value: 33.391
    - type: mrr_at_100
      value: 34.43
    - type: mrr_at_1000
      value: 34.479
    - type: mrr_at_3
      value: 30.239
    - type: mrr_at_5
      value: 31.923000000000002
    - type: ndcg_at_1
      value: 23.583000000000002
    - type: ndcg_at_10
      value: 24.84
    - type: ndcg_at_100
      value: 31.749
    - type: ndcg_at_1000
      value: 35.161
    - type: ndcg_at_3
      value: 19.906
    - type: ndcg_at_5
      value: 21.543
    - type: precision_at_1
      value: 23.583000000000002
    - type: precision_at_10
      value: 7.739
    - type: precision_at_100
      value: 1.5110000000000001
    - type: precision_at_1000
      value: 0.215
    - type: precision_at_3
      value: 14.506
    - type: precision_at_5
      value: 11.179
    - type: recall_at_1
      value: 10.767
    - type: recall_at_10
      value: 30.270000000000003
    - type: recall_at_100
      value: 54.467
    - type: recall_at_1000
      value: 73.71799999999999
    - type: recall_at_3
      value: 18.251
    - type: recall_at_5
      value: 22.831000000000003
  - task:
      type: Retrieval
    dataset:
      type: dbpedia-entity
      name: MTEB DBPedia
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 6.493
    - type: map_at_10
      value: 15.290999999999999
    - type: map_at_100
      value: 21.523999999999997
    - type: map_at_1000
      value: 22.980999999999998
    - type: map_at_3
      value: 11.015
    - type: map_at_5
      value: 12.631
    - type: mrr_at_1
      value: 55.50000000000001
    - type: mrr_at_10
      value: 65.068
    - type: mrr_at_100
      value: 65.608
    - type: mrr_at_1000
      value: 65.622
    - type: mrr_at_3
      value: 62.625
    - type: mrr_at_5
      value: 64.2
    - type: ndcg_at_1
      value: 44.875
    - type: ndcg_at_10
      value: 35.046
    - type: ndcg_at_100
      value: 38.662
    - type: ndcg_at_1000
      value: 45.916000000000004
    - type: ndcg_at_3
      value: 38.888
    - type: ndcg_at_5
      value: 36.411
    - type: precision_at_1
      value: 55.50000000000001
    - type: precision_at_10
      value: 28.175
    - type: precision_at_100
      value: 8.938
    - type: precision_at_1000
      value: 1.894
    - type: precision_at_3
      value: 41.917
    - type: precision_at_5
      value: 34.949999999999996
    - type: recall_at_1
      value: 6.493
    - type: recall_at_10
      value: 20.992
    - type: recall_at_100
      value: 44.138
    - type: recall_at_1000
      value: 67.181
    - type: recall_at_3
      value: 12.546
    - type: recall_at_5
      value: 15.552
  - task:
      type: Classification
    dataset:
      type: mteb/emotion
      name: MTEB EmotionClassification
      config: default
      split: test
      revision: 4f58c6b202a23cf9a4da393831edf4f9183cad37
    metrics:
    - type: accuracy
      value: 45.955
    - type: f1
      value: 40.97084067876041
  - task:
      type: Retrieval
    dataset:
      type: fever
      name: MTEB FEVER
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 43.765
    - type: map_at_10
      value: 56.566
    - type: map_at_100
      value: 57.154
    - type: map_at_1000
      value: 57.181000000000004
    - type: map_at_3
      value: 53.637
    - type: map_at_5
      value: 55.457
    - type: mrr_at_1
      value: 47.03
    - type: mrr_at_10
      value: 59.938
    - type: mrr_at_100
      value: 60.44500000000001
    - type: mrr_at_1000
      value: 60.458999999999996
    - type: mrr_at_3
      value: 57.141
    - type: mrr_at_5
      value: 58.862
    - type: ndcg_at_1
      value: 47.03
    - type: ndcg_at_10
      value: 63.227
    - type: ndcg_at_100
      value: 65.846
    - type: ndcg_at_1000
      value: 66.412
    - type: ndcg_at_3
      value: 57.546
    - type: ndcg_at_5
      value: 60.638000000000005
    - type: precision_at_1
      value: 47.03
    - type: precision_at_10
      value: 8.831
    - type: precision_at_100
      value: 1.027
    - type: precision_at_1000
      value: 0.109
    - type: precision_at_3
      value: 23.642
    - type: precision_at_5
      value: 15.884
    - type: recall_at_1
      value: 43.765
    - type: recall_at_10
      value: 80.537
    - type: recall_at_100
      value: 92.06400000000001
    - type: recall_at_1000
      value: 96.054
    - type: recall_at_3
      value: 65.27199999999999
    - type: recall_at_5
      value: 72.71
  - task:
      type: Retrieval
    dataset:
      type: fiqa
      name: MTEB FiQA2018
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 20.684
    - type: map_at_10
      value: 33.393
    - type: map_at_100
      value: 35.370000000000005
    - type: map_at_1000
      value: 35.539
    - type: map_at_3
      value: 28.810000000000002
    - type: map_at_5
      value: 31.484
    - type: mrr_at_1
      value: 41.049
    - type: mrr_at_10
      value: 49.736999999999995
    - type: mrr_at_100
      value: 50.541000000000004
    - type: mrr_at_1000
      value: 50.575
    - type: mrr_at_3
      value: 47.094
    - type: mrr_at_5
      value: 48.768
    - type: ndcg_at_1
      value: 41.049
    - type: ndcg_at_10
      value: 41.338
    - type: ndcg_at_100
      value: 48.386
    - type: ndcg_at_1000
      value: 51.209
    - type: ndcg_at_3
      value: 37.208000000000006
    - type: ndcg_at_5
      value: 38.788
    - type: precision_at_1
      value: 41.049
    - type: precision_at_10
      value: 11.466
    - type: precision_at_100
      value: 1.8769999999999998
    - type: precision_at_1000
      value: 0.23800000000000002
    - type: precision_at_3
      value: 24.691
    - type: precision_at_5
      value: 18.519
    - type: recall_at_1
      value: 20.684
    - type: recall_at_10
      value: 48.431000000000004
    - type: recall_at_100
      value: 74.331
    - type: recall_at_1000
      value: 91.268
    - type: recall_at_3
      value: 33.267
    - type: recall_at_5
      value: 40.313
  - task:
      type: Retrieval
    dataset:
      type: hotpotqa
      name: MTEB HotpotQA
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 32.242
    - type: map_at_10
      value: 47.49
    - type: map_at_100
      value: 48.409
    - type: map_at_1000
      value: 48.489
    - type: map_at_3
      value: 44.519
    - type: map_at_5
      value: 46.298
    - type: mrr_at_1
      value: 64.483
    - type: mrr_at_10
      value: 71.364
    - type: mrr_at_100
      value: 71.734
    - type: mrr_at_1000
      value: 71.751
    - type: mrr_at_3
      value: 69.899
    - type: mrr_at_5
      value: 70.791
    - type: ndcg_at_1
      value: 64.483
    - type: ndcg_at_10
      value: 56.274
    - type: ndcg_at_100
      value: 59.855999999999995
    - type: ndcg_at_1000
      value: 61.538000000000004
    - type: ndcg_at_3
      value: 51.636
    - type: ndcg_at_5
      value: 54.089
    - type: precision_at_1
      value: 64.483
    - type: precision_at_10
      value: 11.858
    - type: precision_at_100
      value: 1.47
    - type: precision_at_1000
      value: 0.169
    - type: precision_at_3
      value: 32.635999999999996
    - type: precision_at_5
      value: 21.521
    - type: recall_at_1
      value: 32.242
    - type: recall_at_10
      value: 59.291000000000004
    - type: recall_at_100
      value: 73.518
    - type: recall_at_1000
      value: 84.747
    - type: recall_at_3
      value: 48.953
    - type: recall_at_5
      value: 53.801
  - task:
      type: Classification
    dataset:
      type: mteb/imdb
      name: MTEB ImdbClassification
      config: default
      split: test
      revision: 3d86128a09e091d6018b6d26cad27f2739fc2db7
    metrics:
    - type: accuracy
      value: 80.9492
    - type: ap
      value: 75.30846930618502
    - type: f1
      value: 80.89150705991759
  - task:
      type: Retrieval
    dataset:
      type: msmarco
      name: MTEB MSMARCO
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 22.033
    - type: map_at_10
      value: 34.331
    - type: map_at_100
      value: 35.536
    - type: map_at_1000
      value: 35.583
    - type: map_at_3
      value: 30.562
    - type: map_at_5
      value: 32.667
    - type: mrr_at_1
      value: 22.708000000000002
    - type: mrr_at_10
      value: 34.967999999999996
    - type: mrr_at_100
      value: 36.105
    - type: mrr_at_1000
      value: 36.147
    - type: mrr_at_3
      value: 31.256
    - type: mrr_at_5
      value: 33.322
    - type: ndcg_at_1
      value: 22.708000000000002
    - type: ndcg_at_10
      value: 41.211999999999996
    - type: ndcg_at_100
      value: 46.952
    - type: ndcg_at_1000
      value: 48.131
    - type: ndcg_at_3
      value: 33.501
    - type: ndcg_at_5
      value: 37.248999999999995
    - type: precision_at_1
      value: 22.708000000000002
    - type: precision_at_10
      value: 6.519
    - type: precision_at_100
      value: 0.9390000000000001
    - type: precision_at_1000
      value: 0.104
    - type: precision_at_3
      value: 14.302999999999999
    - type: precision_at_5
      value: 10.481
    - type: recall_at_1
      value: 22.033
    - type: recall_at_10
      value: 62.348000000000006
    - type: recall_at_100
      value: 88.771
    - type: recall_at_1000
      value: 97.782
    - type: recall_at_3
      value: 41.331
    - type: recall_at_5
      value: 50.32600000000001
  - task:
      type: Classification
    dataset:
      type: mteb/mtop_domain
      name: MTEB MTOPDomainClassification (en)
      config: en
      split: test
      revision: d80d48c1eb48d3562165c59d59d0034df9fff0bf
    metrics:
    - type: accuracy
      value: 92.69037847697219
    - type: f1
      value: 92.20814766144707
  - task:
      type: Classification
    dataset:
      type: mteb/mtop_intent
      name: MTEB MTOPIntentClassification (en)
      config: en
      split: test
      revision: ae001d0e6b1228650b7bd1c2c65fb50ad11a8aba
    metrics:
    - type: accuracy
      value: 61.12859097127223
    - type: f1
      value: 44.859837744275346
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_intent
      name: MTEB MassiveIntentClassification (en)
      config: en
      split: test
      revision: 31efe3c427b0bae9c22cbb560b8f15491cc6bed7
    metrics:
    - type: accuracy
      value: 67.59246805648958
    - type: f1
      value: 65.35653843975764
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_scenario
      name: MTEB MassiveScenarioClassification (en)
      config: en
      split: test
      revision: 7d571f92784cd94a019292a1f45445077d0ef634
    metrics:
    - type: accuracy
      value: 72.82447881640888
    - type: f1
      value: 71.74294810351809
  - task:
      type: Clustering
    dataset:
      type: mteb/medrxiv-clustering-p2p
      name: MTEB MedrxivClusteringP2P
      config: default
      split: test
      revision: e7a26af6f3ae46b30dde8737f02c07b1505bcc73
    metrics:
    - type: v_measure
      value: 32.623627054114884
  - task:
      type: Clustering
    dataset:
      type: mteb/medrxiv-clustering-s2s
      name: MTEB MedrxivClusteringS2S
      config: default
      split: test
      revision: 35191c8c0dca72d8ff3efcd72aa802307d469663
    metrics:
    - type: v_measure
      value: 28.715250618201516
  - task:
      type: Reranking
    dataset:
      type: mteb/mind_small
      name: MTEB MindSmallReranking
      config: default
      split: test
      revision: 3bdac13927fdc888b903db93b2ffdbd90b295a69
    metrics:
    - type: map
      value: 31.268319417897434
    - type: mrr
      value: 32.363138927039806
  - task:
      type: Retrieval
    dataset:
      type: nfcorpus
      name: MTEB NFCorpus
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 5.702
    - type: map_at_10
      value: 11.838999999999999
    - type: map_at_100
      value: 14.879999999999999
    - type: map_at_1000
      value: 16.277
    - type: map_at_3
      value: 8.912
    - type: map_at_5
      value: 10.213999999999999
    - type: mrr_at_1
      value: 44.891999999999996
    - type: mrr_at_10
      value: 53.15800000000001
    - type: mrr_at_100
      value: 53.830999999999996
    - type: mrr_at_1000
      value: 53.882
    - type: mrr_at_3
      value: 51.135
    - type: mrr_at_5
      value: 52.234
    - type: ndcg_at_1
      value: 43.808
    - type: ndcg_at_10
      value: 32.179
    - type: ndcg_at_100
      value: 29.842000000000002
    - type: ndcg_at_1000
      value: 38.858
    - type: ndcg_at_3
      value: 38.015
    - type: ndcg_at_5
      value: 35.574
    - type: precision_at_1
      value: 44.891999999999996
    - type: precision_at_10
      value: 23.375
    - type: precision_at_100
      value: 7.545
    - type: precision_at_1000
      value: 2.052
    - type: precision_at_3
      value: 35.088
    - type: precision_at_5
      value: 30.154999999999998
    - type: recall_at_1
      value: 5.702
    - type: recall_at_10
      value: 15.421000000000001
    - type: recall_at_100
      value: 30.708999999999996
    - type: recall_at_1000
      value: 62.487
    - type: recall_at_3
      value: 9.966999999999999
    - type: recall_at_5
      value: 12.059000000000001
  - task:
      type: Retrieval
    dataset:
      type: nq
      name: MTEB NQ
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 39.117000000000004
    - type: map_at_10
      value: 54.041
    - type: map_at_100
      value: 54.845
    - type: map_at_1000
      value: 54.876999999999995
    - type: map_at_3
      value: 50.339999999999996
    - type: map_at_5
      value: 52.678999999999995
    - type: mrr_at_1
      value: 43.627
    - type: mrr_at_10
      value: 56.752
    - type: mrr_at_100
      value: 57.32899999999999
    - type: mrr_at_1000
      value: 57.35
    - type: mrr_at_3
      value: 53.818999999999996
    - type: mrr_at_5
      value: 55.684999999999995
    - type: ndcg_at_1
      value: 43.627
    - type: ndcg_at_10
      value: 60.934
    - type: ndcg_at_100
      value: 64.277
    - type: ndcg_at_1000
      value: 64.97
    - type: ndcg_at_3
      value: 54.164
    - type: ndcg_at_5
      value: 57.994
    - type: precision_at_1
      value: 43.627
    - type: precision_at_10
      value: 9.383
    - type: precision_at_100
      value: 1.131
    - type: precision_at_1000
      value: 0.12
    - type: precision_at_3
      value: 23.919
    - type: precision_at_5
      value: 16.541
    - type: recall_at_1
      value: 39.117000000000004
    - type: recall_at_10
      value: 79.012
    - type: recall_at_100
      value: 93.395
    - type: recall_at_1000
      value: 98.494
    - type: recall_at_3
      value: 61.714999999999996
    - type: recall_at_5
      value: 70.55799999999999
  - task:
      type: Retrieval
    dataset:
      type: quora
      name: MTEB QuoraRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 70.832
    - type: map_at_10
      value: 84.82300000000001
    - type: map_at_100
      value: 85.44500000000001
    - type: map_at_1000
      value: 85.461
    - type: map_at_3
      value: 81.917
    - type: map_at_5
      value: 83.734
    - type: mrr_at_1
      value: 81.61
    - type: mrr_at_10
      value: 87.75500000000001
    - type: mrr_at_100
      value: 87.85300000000001
    - type: mrr_at_1000
      value: 87.854
    - type: mrr_at_3
      value: 86.855
    - type: mrr_at_5
      value: 87.465
    - type: ndcg_at_1
      value: 81.58999999999999
    - type: ndcg_at_10
      value: 88.536
    - type: ndcg_at_100
      value: 89.714
    - type: ndcg_at_1000
      value: 89.80799999999999
    - type: ndcg_at_3
      value: 85.8
    - type: ndcg_at_5
      value: 87.286
    - type: precision_at_1
      value: 81.58999999999999
    - type: precision_at_10
      value: 13.438
    - type: precision_at_100
      value: 1.5310000000000001
    - type: precision_at_1000
      value: 0.157
    - type: precision_at_3
      value: 37.563
    - type: precision_at_5
      value: 24.65
    - type: recall_at_1
      value: 70.832
    - type: recall_at_10
      value: 95.574
    - type: recall_at_100
      value: 99.575
    - type: recall_at_1000
      value: 99.99
    - type: recall_at_3
      value: 87.61
    - type: recall_at_5
      value: 91.9
  - task:
      type: Clustering
    dataset:
      type: mteb/reddit-clustering
      name: MTEB RedditClustering
      config: default
      split: test
      revision: 24640382cdbf8abc73003fb0fa6d111a705499eb
    metrics:
    - type: v_measure
      value: 54.4131741738767
  - task:
      type: Clustering
    dataset:
      type: mteb/reddit-clustering-p2p
      name: MTEB RedditClusteringP2P
      config: default
      split: test
      revision: 282350215ef01743dc01b456c7f5241fa8937f16
    metrics:
    - type: v_measure
      value: 59.816632341901865
  - task:
      type: Retrieval
    dataset:
      type: scidocs
      name: MTEB SCIDOCS
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 4.857
    - type: map_at_10
      value: 11.937000000000001
    - type: map_at_100
      value: 14.143
    - type: map_at_1000
      value: 14.451
    - type: map_at_3
      value: 8.376999999999999
    - type: map_at_5
      value: 10.172
    - type: mrr_at_1
      value: 23.799999999999997
    - type: mrr_at_10
      value: 34.134
    - type: mrr_at_100
      value: 35.285
    - type: mrr_at_1000
      value: 35.33
    - type: mrr_at_3
      value: 30.833
    - type: mrr_at_5
      value: 32.828
    - type: ndcg_at_1
      value: 23.799999999999997
    - type: ndcg_at_10
      value: 20.0
    - type: ndcg_at_100
      value: 28.486
    - type: ndcg_at_1000
      value: 33.781
    - type: ndcg_at_3
      value: 18.726000000000003
    - type: ndcg_at_5
      value: 16.587
    - type: precision_at_1
      value: 23.799999999999997
    - type: precision_at_10
      value: 10.39
    - type: precision_at_100
      value: 2.263
    - type: precision_at_1000
      value: 0.35300000000000004
    - type: precision_at_3
      value: 17.333000000000002
    - type: precision_at_5
      value: 14.56
    - type: recall_at_1
      value: 4.857
    - type: recall_at_10
      value: 21.02
    - type: recall_at_100
      value: 45.932
    - type: recall_at_1000
      value: 71.693
    - type: recall_at_3
      value: 10.552
    - type: recall_at_5
      value: 14.760000000000002
  - task:
      type: STS
    dataset:
      type: mteb/sickr-sts
      name: MTEB SICK-R
      config: default
      split: test
      revision: a6ea5a8cab320b040a23452cc28066d9beae2cee
    metrics:
    - type: cos_sim_pearson
      value: 85.00513539036214
    - type: cos_sim_spearman
      value: 79.19581558052613
    - type: euclidean_pearson
      value: 82.46689229301268
    - type: euclidean_spearman
      value: 79.19581263972574
    - type: manhattan_pearson
      value: 82.46839559537645
    - type: manhattan_spearman
      value: 79.19301791744469
  - task:
      type: STS
    dataset:
      type: mteb/sts12-sts
      name: MTEB STS12
      config: default
      split: test
      revision: a0d554a64d88156834ff5ae9920b964011b16384
    metrics:
    - type: cos_sim_pearson
      value: 82.44111721768361
    - type: cos_sim_spearman
      value: 73.14524004507561
    - type: euclidean_pearson
      value: 78.70346379990235
    - type: euclidean_spearman
      value: 73.14518679640568
    - type: manhattan_pearson
      value: 78.68478215009414
    - type: manhattan_spearman
      value: 73.10912398034866
  - task:
      type: STS
    dataset:
      type: mteb/sts13-sts
      name: MTEB STS13
      config: default
      split: test
      revision: 7e90230a92c190f1bf69ae9002b8cea547a64cca
    metrics:
    - type: cos_sim_pearson
      value: 82.17030364533524
    - type: cos_sim_spearman
      value: 82.88382996129783
    - type: euclidean_pearson
      value: 82.25266887145027
    - type: euclidean_spearman
      value: 82.88382996129783
    - type: manhattan_pearson
      value: 82.21831434263969
    - type: manhattan_spearman
      value: 82.83144970048046
  - task:
      type: STS
    dataset:
      type: mteb/sts14-sts
      name: MTEB STS14
      config: default
      split: test
      revision: 6031580fec1f6af667f0bd2da0a551cf4f0b2375
    metrics:
    - type: cos_sim_pearson
      value: 80.73413303490618
    - type: cos_sim_spearman
      value: 76.95203008005365
    - type: euclidean_pearson
      value: 79.09169854088067
    - type: euclidean_spearman
      value: 76.95202489005659
    - type: manhattan_pearson
      value: 79.04289364751341
    - type: manhattan_spearman
      value: 76.89976809512328
  - task:
      type: STS
    dataset:
      type: mteb/sts15-sts
      name: MTEB STS15
      config: default
      split: test
      revision: ae752c7c21bf194d8b67fd573edf7ae58183cbe3
    metrics:
    - type: cos_sim_pearson
      value: 86.84421416279349
    - type: cos_sim_spearman
      value: 87.67393507190887
    - type: euclidean_pearson
      value: 86.81662915280972
    - type: euclidean_spearman
      value: 87.67395576051472
    - type: manhattan_pearson
      value: 86.76502179645067
    - type: manhattan_spearman
      value: 87.60931601838358
  - task:
      type: STS
    dataset:
      type: mteb/sts16-sts
      name: MTEB STS16
      config: default
      split: test
      revision: 4d8694f8f0e0100860b497b999b3dbed754a0513
    metrics:
    - type: cos_sim_pearson
      value: 83.47603001840406
    - type: cos_sim_spearman
      value: 84.57363689562743
    - type: euclidean_pearson
      value: 83.62746191773213
    - type: euclidean_spearman
      value: 84.57363689562743
    - type: manhattan_pearson
      value: 83.5049257196953
    - type: manhattan_spearman
      value: 84.43576972291818
  - task:
      type: STS
    dataset:
      type: mteb/sts17-crosslingual-sts
      name: MTEB STS17 (en-en)
      config: en-en
      split: test
      revision: af5e6fb845001ecf41f4c1e033ce921939a2a68d
    metrics:
    - type: cos_sim_pearson
      value: 89.17222804445805
    - type: cos_sim_spearman
      value: 89.04642204765032
    - type: euclidean_pearson
      value: 88.93412366747594
    - type: euclidean_spearman
      value: 89.04642204765032
    - type: manhattan_pearson
      value: 88.88891722217033
    - type: manhattan_spearman
      value: 88.95405155642727
  - task:
      type: STS
    dataset:
      type: mteb/sts22-crosslingual-sts
      name: MTEB STS22 (en)
      config: en
      split: test
      revision: 6d1ba47164174a496b7fa5d3569dae26a6813b80
    metrics:
    - type: cos_sim_pearson
      value: 63.4232873899918
    - type: cos_sim_spearman
      value: 62.53261852485254
    - type: euclidean_pearson
      value: 63.95808586267597
    - type: euclidean_spearman
      value: 62.53261852485254
    - type: manhattan_pearson
      value: 64.07446205165546
    - type: manhattan_spearman
      value: 62.86514483815617
  - task:
      type: STS
    dataset:
      type: mteb/stsbenchmark-sts
      name: MTEB STSBenchmark
      config: default
      split: test
      revision: b0fddb56ed78048fa8b90373c8a3cfc37b684831
    metrics:
    - type: cos_sim_pearson
      value: 84.324835033109
    - type: cos_sim_spearman
      value: 84.75551248417419
    - type: euclidean_pearson
      value: 84.98725144123726
    - type: euclidean_spearman
      value: 84.75551248417419
    - type: manhattan_pearson
      value: 84.9546533100131
    - type: manhattan_spearman
      value: 84.73671830914728
  - task:
      type: Reranking
    dataset:
      type: mteb/scidocs-reranking
      name: MTEB SciDocsRR
      config: default
      split: test
      revision: d3c5e1fc0b855ab6097bf1cda04dd73947d7caab
    metrics:
    - type: map
      value: 83.62940531539546
    - type: mrr
      value: 95.50283503714876
  - task:
      type: Retrieval
    dataset:
      type: scifact
      name: MTEB SciFact
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 52.428
    - type: map_at_10
      value: 62.731
    - type: map_at_100
      value: 63.327
    - type: map_at_1000
      value: 63.356
    - type: map_at_3
      value: 60.17400000000001
    - type: map_at_5
      value: 61.461
    - type: mrr_at_1
      value: 55.333
    - type: mrr_at_10
      value: 63.788999999999994
    - type: mrr_at_100
      value: 64.27000000000001
    - type: mrr_at_1000
      value: 64.298
    - type: mrr_at_3
      value: 61.944
    - type: mrr_at_5
      value: 62.861
    - type: ndcg_at_1
      value: 55.333
    - type: ndcg_at_10
      value: 67.309
    - type: ndcg_at_100
      value: 70.033
    - type: ndcg_at_1000
      value: 70.842
    - type: ndcg_at_3
      value: 63.05500000000001
    - type: ndcg_at_5
      value: 64.8
    - type: precision_at_1
      value: 55.333
    - type: precision_at_10
      value: 9.1
    - type: precision_at_100
      value: 1.057
    - type: precision_at_1000
      value: 0.11199999999999999
    - type: precision_at_3
      value: 25.111
    - type: precision_at_5
      value: 16.333000000000002
    - type: recall_at_1
      value: 52.428
    - type: recall_at_10
      value: 80.156
    - type: recall_at_100
      value: 92.833
    - type: recall_at_1000
      value: 99.333
    - type: recall_at_3
      value: 68.73899999999999
    - type: recall_at_5
      value: 73.13300000000001
  - task:
      type: PairClassification
    dataset:
      type: mteb/sprintduplicatequestions-pairclassification
      name: MTEB SprintDuplicateQuestions
      config: default
      split: test
      revision: d66bd1f72af766a5cc4b0ca5e00c162f89e8cc46
    metrics:
    - type: cos_sim_accuracy
      value: 99.8069306930693
    - type: cos_sim_ap
      value: 94.89496931806809
    - type: cos_sim_f1
      value: 90.0763358778626
    - type: cos_sim_precision
      value: 91.70984455958549
    - type: cos_sim_recall
      value: 88.5
    - type: dot_accuracy
      value: 99.8069306930693
    - type: dot_ap
      value: 94.89495820622456
    - type: dot_f1
      value: 90.0763358778626
    - type: dot_precision
      value: 91.70984455958549
    - type: dot_recall
      value: 88.5
    - type: euclidean_accuracy
      value: 99.8069306930693
    - type: euclidean_ap
      value: 94.8949693180681
    - type: euclidean_f1
      value: 90.0763358778626
    - type: euclidean_precision
      value: 91.70984455958549
    - type: euclidean_recall
      value: 88.5
    - type: manhattan_accuracy
      value: 99.8009900990099
    - type: manhattan_ap
      value: 94.81699021810266
    - type: manhattan_f1
      value: 89.82278481012658
    - type: manhattan_precision
      value: 90.97435897435898
    - type: manhattan_recall
      value: 88.7
    - type: max_accuracy
      value: 99.8069306930693
    - type: max_ap
      value: 94.8949693180681
    - type: max_f1
      value: 90.0763358778626
  - task:
      type: Clustering
    dataset:
      type: mteb/stackexchange-clustering
      name: MTEB StackExchangeClustering
      config: default
      split: test
      revision: 6cbc1f7b2bc0622f2e39d2c77fa502909748c259
    metrics:
    - type: v_measure
      value: 58.95255708336027
  - task:
      type: Clustering
    dataset:
      type: mteb/stackexchange-clustering-p2p
      name: MTEB StackExchangeClusteringP2P
      config: default
      split: test
      revision: 815ca46b2622cec33ccafc3735d572c266efdb44
    metrics:
    - type: v_measure
      value: 34.26328409998647
  - task:
      type: Reranking
    dataset:
      type: mteb/stackoverflowdupquestions-reranking
      name: MTEB StackOverflowDupQuestions
      config: default
      split: test
      revision: e185fbe320c72810689fc5848eb6114e1ef5ec69
    metrics:
    - type: map
      value: 52.324949351182134
    - type: mrr
      value: 53.08798329938036
  - task:
      type: Summarization
    dataset:
      type: mteb/summeval
      name: MTEB SummEval
      config: default
      split: test
      revision: cda12ad7615edc362dbf25a00fdd61d3b1eaf93c
    metrics:
    - type: cos_sim_pearson
      value: 30.286127875761963
    - type: cos_sim_spearman
      value: 30.85723241148158
    - type: dot_pearson
      value: 30.28613033184199
    - type: dot_spearman
      value: 30.85723241148158
  - task:
      type: Retrieval
    dataset:
      type: trec-covid
      name: MTEB TRECCOVID
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 0.199
    - type: map_at_10
      value: 1.633
    - type: map_at_100
      value: 8.813
    - type: map_at_1000
      value: 21.015
    - type: map_at_3
      value: 0.577
    - type: map_at_5
      value: 0.907
    - type: mrr_at_1
      value: 72.0
    - type: mrr_at_10
      value: 82.667
    - type: mrr_at_100
      value: 82.667
    - type: mrr_at_1000
      value: 82.667
    - type: mrr_at_3
      value: 80.667
    - type: mrr_at_5
      value: 82.667
    - type: ndcg_at_1
      value: 67.0
    - type: ndcg_at_10
      value: 65.377
    - type: ndcg_at_100
      value: 50.693
    - type: ndcg_at_1000
      value: 45.449
    - type: ndcg_at_3
      value: 67.78800000000001
    - type: ndcg_at_5
      value: 67.19000000000001
    - type: precision_at_1
      value: 72.0
    - type: precision_at_10
      value: 70.6
    - type: precision_at_100
      value: 52.0
    - type: precision_at_1000
      value: 20.316000000000003
    - type: precision_at_3
      value: 72.667
    - type: precision_at_5
      value: 72.39999999999999
    - type: recall_at_1
      value: 0.199
    - type: recall_at_10
      value: 1.8800000000000001
    - type: recall_at_100
      value: 12.195
    - type: recall_at_1000
      value: 42.612
    - type: recall_at_3
      value: 0.608
    - type: recall_at_5
      value: 1.004
  - task:
      type: Retrieval
    dataset:
      type: webis-touche2020
      name: MTEB Touche2020
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 2.34
    - type: map_at_10
      value: 7.983
    - type: map_at_100
      value: 14.488999999999999
    - type: map_at_1000
      value: 16.133
    - type: map_at_3
      value: 4.312
    - type: map_at_5
      value: 6.3420000000000005
    - type: mrr_at_1
      value: 26.531
    - type: mrr_at_10
      value: 41.558
    - type: mrr_at_100
      value: 42.211999999999996
    - type: mrr_at_1000
      value: 42.211999999999996
    - type: mrr_at_3
      value: 36.054
    - type: mrr_at_5
      value: 39.217999999999996
    - type: ndcg_at_1
      value: 23.469
    - type: ndcg_at_10
      value: 21.077
    - type: ndcg_at_100
      value: 35.497
    - type: ndcg_at_1000
      value: 47.282000000000004
    - type: ndcg_at_3
      value: 20.906
    - type: ndcg_at_5
      value: 21.78
    - type: precision_at_1
      value: 26.531
    - type: precision_at_10
      value: 18.570999999999998
    - type: precision_at_100
      value: 7.673000000000001
    - type: precision_at_1000
      value: 1.551
    - type: precision_at_3
      value: 21.769
    - type: precision_at_5
      value: 22.448999999999998
    - type: recall_at_1
      value: 2.34
    - type: recall_at_10
      value: 14.154
    - type: recall_at_100
      value: 48.355
    - type: recall_at_1000
      value: 84.872
    - type: recall_at_3
      value: 5.19
    - type: recall_at_5
      value: 9.211
  - task:
      type: Classification
    dataset:
      type: mteb/toxic_conversations_50k
      name: MTEB ToxicConversationsClassification
      config: default
      split: test
      revision: d7c0de2777da35d6aae2200a62c6e0e5af397c4c
    metrics:
    - type: accuracy
      value: 71.9318
    - type: ap
      value: 14.755439516631267
    - type: f1
      value: 55.39101096477449
  - task:
      type: Classification
    dataset:
      type: mteb/tweet_sentiment_extraction
      name: MTEB TweetSentimentExtractionClassification
      config: default
      split: test
      revision: d604517c81ca91fe16a244d1248fc021f9ecee7a
    metrics:
    - type: accuracy
      value: 61.06395019807584
    - type: f1
      value: 61.18513886850968
  - task:
      type: Clustering
    dataset:
      type: mteb/twentynewsgroups-clustering
      name: MTEB TwentyNewsgroupsClustering
      config: default
      split: test
      revision: 6125ec4e24fa026cec8a478383ee943acfbd5449
    metrics:
    - type: v_measure
      value: 43.68814723462553
  - task:
      type: PairClassification
    dataset:
      type: mteb/twittersemeval2015-pairclassification
      name: MTEB TwitterSemEval2015
      config: default
      split: test
      revision: 70970daeab8776df92f5ea462b6173c0b46fd2d1
    metrics:
    - type: cos_sim_accuracy
      value: 85.8258329856351
    - type: cos_sim_ap
      value: 73.51953909054856
    - type: cos_sim_f1
      value: 68.17958783120707
    - type: cos_sim_precision
      value: 63.70930765703806
    - type: cos_sim_recall
      value: 73.3245382585752
    - type: dot_accuracy
      value: 85.8258329856351
    - type: dot_ap
      value: 73.51954936569123
    - type: dot_f1
      value: 68.17958783120707
    - type: dot_precision
      value: 63.70930765703806
    - type: dot_recall
      value: 73.3245382585752
    - type: euclidean_accuracy
      value: 85.8258329856351
    - type: euclidean_ap
      value: 73.51954390509214
    - type: euclidean_f1
      value: 68.17958783120707
    - type: euclidean_precision
      value: 63.70930765703806
    - type: euclidean_recall
      value: 73.3245382585752
    - type: manhattan_accuracy
      value: 85.8258329856351
    - type: manhattan_ap
      value: 73.44954175022839
    - type: manhattan_f1
      value: 68.08816482989938
    - type: manhattan_precision
      value: 62.351908731899954
    - type: manhattan_recall
      value: 74.9868073878628
    - type: max_accuracy
      value: 85.8258329856351
    - type: max_ap
      value: 73.51954936569123
    - type: max_f1
      value: 68.17958783120707
  - task:
      type: PairClassification
    dataset:
      type: mteb/twitterurlcorpus-pairclassification
      name: MTEB TwitterURLCorpus
      config: default
      split: test
      revision: 8b6510b0b1fa4e4c4f879467980e9be563ec1cdf
    metrics:
    - type: cos_sim_accuracy
      value: 88.6094617145962
    - type: cos_sim_ap
      value: 85.4121913477208
    - type: cos_sim_f1
      value: 77.61548157484985
    - type: cos_sim_precision
      value: 74.84627484627485
    - type: cos_sim_recall
      value: 80.59747459193102
    - type: dot_accuracy
      value: 88.6094617145962
    - type: dot_ap
      value: 85.41219830675979
    - type: dot_f1
      value: 77.61548157484985
    - type: dot_precision
      value: 74.84627484627485
    - type: dot_recall
      value: 80.59747459193102
    - type: euclidean_accuracy
      value: 88.6094617145962
    - type: euclidean_ap
      value: 85.41219328124808
    - type: euclidean_f1
      value: 77.61548157484985
    - type: euclidean_precision
      value: 74.84627484627485
    - type: euclidean_recall
      value: 80.59747459193102
    - type: manhattan_accuracy
      value: 88.53960492102301
    - type: manhattan_ap
      value: 85.35022078482446
    - type: manhattan_f1
      value: 77.56588974387569
    - type: manhattan_precision
      value: 74.98742183569324
    - type: manhattan_recall
      value: 80.3279950723745
    - type: max_accuracy
      value: 88.6094617145962
    - type: max_ap
      value: 85.41219830675979
    - type: max_f1
      value: 77.61548157484985
---
<!-- TODO: add evaluation results here -->
<br><br>

<p align="center">
<img src="https://github.com/jina-ai/finetuner/blob/main/docs/_static/finetuner-logo-ani.svg?raw=true" alt="Finetuner logo: Finetuner helps you to create experiments in order to improve embeddings on search tasks. It accompanies you to deliver the last mile of performance-tuning for neural search applications." width="150px">
</p>


<p align="center">
<b>The text embedding set trained by <a href="https://jina.ai/"><b>Jina AI</b></a>, <a href="https://github.com/jina-ai/finetuner"><b>Finetuner</b></a> team.</b>
</p>


## Intended Usage & Model Info

`jina-embeddings-v2-base-en` is an English, monolingual **embedding model** supporting **8192 sequence length**.
It is based on a Bert architecture (JinaBert) that supports the symmetric bidirectional variant of [ALiBi](https://arxiv.org/abs/2108.12409) to allow longer sequence length.
The backbone `jina-bert-v2-base-en` is pretrained on the C4 dataset.
The model is further trained on Jina AI's collection of more than 400 millions of sentence pairs and hard negatives.
These pairs were obtained from various domains and were carefully selected through a thorough cleaning process.

The embedding model was trained using 512 sequence length, but extrapolates to 8k sequence length (or even longer) thanks to ALiBi.
This makes our model useful for a range of use cases, especially when processing long documents is needed, including long document retrieval, semantic textual similarity, text reranking, recommendation, RAG and LLM-based generative search, etc.

With a standard size of 137 million parameters, the model enables fast inference while delivering better performance than our small model. It is recommended to use a single GPU for inference.
Additionally, we provide the following embedding models:

### V1 (Based on T5, 512 Seq)

- [`jina-embeddings-v1-small-en`](https://huggingface.co/jinaai/jina-embedding-s-en-v1): 35 million parameters.
- [`jina-embeddings-v1-base-en`](https://huggingface.co/jinaai/jina-embedding-b-en-v1): 110 million parameters.
- [`jina-embeddings-v2-large-en`](https://huggingface.co/jinaai/jina-embedding-l-en-v1): 330 million parameters.

### V2 (Based on JinaBert, 8k Seq)

- [`jina-embeddings-v2-small-en`](https://huggingface.co/jinaai/jina-embeddings-v2-small-en): 33 million parameters **(you are here)**.
- [`jina-embeddings-v2-base-en`](https://huggingface.co/jinaai/jina-embeddings-v2-base-en): 137 million parameters.
- [`jina-embeddings-v2-large-en`](): 435 million parameters (releasing soon).

## Data & Parameters

Jina Embeddings V2 technical report coming soon.

Jina Embeddings V1 [technical report](https://arxiv.org/abs/2307.11224).

## Usage

You can use Jina Embedding models directly from transformers package:
```python
!pip install transformers
from transformers import AutoModel
from numpy.linalg import norm

cos_sim = lambda a,b: (a @ b.T) / (norm(a)*norm(b))
model = AutoModel.from_pretrained('jinaai/jina-embeddings-v2-base-en', trust_remote_code=True) # trust_remote_code is needed to use the encode method
embeddings = model.encode(['How is the weather today?', 'What is the current weather like today?'])
print(cos_sim(embeddings[0], embeddings[1]))
```

If you only want to handle shorter sequence, such as 2k, pass the `max_length` parameter to the `encode` function:

```python
embeddings = model.encode(
    ['Very long ... document'],
    max_length=2048
)
```

## Fine-tuning

Please consider [Finetuner](https://github.com/jina-ai/finetuner).

## Plans

The development of new bilingual models is currently underway. We will be targeting mainly the German and Spanish languages. The upcoming models will be called `jina-embedding-b-de/es-v2`.

## Contact

Join our [Discord community](https://discord.jina.ai) and chat with other community members about ideas.

## Citation

If you find Jina Embeddings useful in your research, please cite the following paper:

<!-- TODO: update the paper ID once it is published on arxiv -->
``` latex
@misc{günther2023jina,
      title={Beyond the 512-Token Barrier: Training General-Purpose Text
Embeddings for Large Documents}, 
      author={Michael Günther and Jackmin Ong and Isabelle Mohr and Alaeddine Abdessalem and Tanguy Abel and Mohammad Kalim Akram and Susana Guzman and Georgios Mastrapas and Saba Sturua and Bo Wang},
      year={2023},
      eprint={2307.11224},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```