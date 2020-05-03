# Denoising of 1D signal using WAVENET / LADDERNET / BOOSTING
# Kaggle competition from University of Liverpool

For more information see:
https://www.kaggle.com/c/liverpool-ion-switching

The competition is basically about removing noise from a 1D signal.

*IONCHANNEL_CONV1D_20200425.ipynb*: Use of WAVENET or LADDERNET (U-NET)
*IONCHANNEL_LGB_20200502.ipynb*: Use of lightgbm (Feature engineering + Boosting)
*IONCHANNEL_CATBOOST_20200502.ipynb*: Use of CATBOOST (Feature engineering + Boosting)

**Data:** (folder)
train.csv: original training data
test.csv: original test data
train_clean.csv: training data with drift removal. Obtained from [Chris Deotte](https://www.kaggle.com/cdeotte/data-without-drift)
test_clean.csv: test data with drift removal. Obtained from [Chris Deotte](https://www.kaggle.com/cdeotte/data-without-drift)
