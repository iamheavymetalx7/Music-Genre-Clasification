# Music-Genre-Clasification
In this project, we need to correctly classify music genres based on various characterisitics of music.

General Instructions:
1. For the python files name having _optuna : Use the data set generated from the file named 0_Generating_Data.ipynb 
2. For the python files name having _mutual: Use the data set generated from the file named 1_RFC_Mutual.ipynb
3. For the python files name having _pca: Use the data set generated from the file named 1_PCA_RFC.ipynb

In order to save time during computations, no need to run the cell having the code:

study = optuna.create_study(direction="maximize")
study.optimize(objective, n_trials=50, timeout = 4*60*60)

This is because, I have already enliste the best parameters that I obtained after this command and if we run the above mentioned cell, hypertuning will take a lot of time.

