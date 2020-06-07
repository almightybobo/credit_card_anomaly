## TODO
- [x] Write data analysis script, output count_each_column(number of unique value in each column) and fraud_binary.png / real_binary.png (number of Y/N, 5 features)
- [x] Write data preprocess script, csv read/write, N/Y -> 0/1, regression value -> 0~1
- [x] Write model script, but not test yet
- [x] Write main script, can train now (eval metrics: auc -> aucpr)
- [x] Delete some features, one-hot encoding some features
- [x] Extract more feature
- [x] Run on colab, azure machine learning studio
- [ ] Analyze more to find the special pattern in fraud data
- [ ] Tune the hyperparameters (ex. learning rate, scale_pos_weight, l1, l2)
- [ ] Try different models (ex. catboost, neural network)
- [ ] Ensemble mdoels