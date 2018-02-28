## Genetic Algorithm used for classification of gamma rays

- Used TPOT library for genetic algothim and trained it for classification of gamma rays.
The dataset is taken from tpot repo only.

- Trained it for 5 generations and population size of 30.
- Best pipeline came out to be : XGBClassifier(input_matrix, learning_rate=0.1, max_depth=7, min_child_weight=1, n_estimators=100, nthread=1, subsample=0.9)