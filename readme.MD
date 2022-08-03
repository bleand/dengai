# DengAI competition

In this repo you'll find a WIP solution of the DengAI competition.

Each notebook is numbered for easier exploration.
* 1, 2, 3: Data exploration and feature creation
* 4, 5, 6: Testing different models and features combination
* 7: Submission code, used to generate prediction after picking a candidate from 4, 5, 6

# Activity tracker
- [X] Load data
- [X] Basic EDA
- [X] Features correlation
- [X] Missing values
- [X] Outliers
- [X] Replace week 53 with week 0 -> Not much improvement
- [ ] Calculate time delay -> Inconclusive
- [X] Normalize values
- [X] Create a time split 80 - 20 per city (there are more years to train and predict for sj than iq)
- [X] Create a basic baseline model with all features 'as is' (bad performance expected)
- [X] Create a basic model with only "non-correlated" features
- [X] One model per city
- [X] Normalize features for models
- [X] Obtain feature importance
- [X] Implement time delay using moving averages (another notebook)
- [ ] Create function to test multiple models (WIP - `Modeling_tests.ipynb` - not up to date)

Next steps:
- [ ] FFNN
- [ ] LSTM
- [ ] Ensembles
- [ ] Hyperopt