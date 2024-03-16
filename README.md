# PoliTO-DataScienceLab
### Final project for the PoliTO course Data Science Lab
The program address a speech recognition task aimed at detecting the correct command from voice instructions (similarly to what it is done by voice assistnats).
All the project code has been inserted in the file `progtam.ipynb`.  
The pipeline is divided into different steps:
- **Data loading**: tracks loading with librosa library
- **Data pre-processing and cleaning**: audio trimming, female voice pitch shift, deletion of tracks with anomalous length
- **MFCC features extraction**: MFCC data extraction and discretization
- **Dataset splitting**: train, eval, test
- **Dimensionality reduction**: PCA (100 features)
- **Hyperparameters tuning**: grid-search process for different models
- **Train and test**: models training with best parameters and testing to find the best
- **Private test-set classification**: classification with best model
