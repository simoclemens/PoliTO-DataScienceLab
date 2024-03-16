# PoliTO-DataScienceLab
### Final project for the PoliTO course Data Science Lab

All the project code has been inserted in the file `progtam.ipynb`.  
The pipeline is divided into different steps:
- **Data loading**: tracks loading with librosa library
- **Data pre-processing and cleaning**: audio trimming, female voice pitch shift, deletion of tracks with anomalous length
- **MFCC features extraction**: MFCC data extraction and discretization
- **Dimensionality reduction**: PCA
- **Private test-set classification**:
