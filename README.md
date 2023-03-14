# Feature-Selection
This space is used to record my ideas for equity feature selection for use in screening processes.

1. PCA (classic dimensionality reduction algorithm)
2. Nearest Neighbour and LGBM - https://www.kaggle.com/competitions/optiver-realized-volatility-prediction/discussion/274970 OR https://www.kaggle.com/competitions/optiver-realized-volatility-prediction/discussion/278676
3. Gradient Boosting models - 
LGBM - https://www.kaggle.com/competitions/ubiquant-market-prediction/discussion/338220 OR https://www.kaggle.com/competitions/ubiquant-market-prediction/discussion/338615 OR https://www.kaggle.com/competitions/ubiquant-market-prediction/discussion/338293 OR https://www.kaggle.com/competitions/ubiquant-market-prediction/discussion/338236 - THIS ISNT LGB BUT COULD BE USED WITH https://www.kaggle.com/competitions/ubiquant-market-prediction/discussion/33823 OR https://www.kaggle.com/competitions/optiver-realized-volatility-prediction/discussion/276506
4. Forecasting using a weighted cross-validation ensemble https://www.sciencedirect.com/science/article/abs/pii/S0925231213000209?via%3Dihub,
Other CV resources - https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/224029 and https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/227167 or https://www.kaggle.com/competitions/g-research-crypto-forecasting/discussion/323098 or https://www.kaggle.com/competitions/g-research-crypto-forecasting/discussion/323703
4. Deep learning resources - https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/224713 and https://sjsm.shiraz.iau.ir/article_694701_01ed85f4ac1466918717bd15c22c3a31.pdf and https://link.springer.com/article/10.1007/s11042-022-12328-x
5. Autoencoders can be used to reduce an original high dimensionality to a lower dimensionality.
Useful Autoencoders resources:
https://towardsdatascience.com/autoencoders-for-the-compression-of-stock-market-data-28e8c1a2da3e 
https://machinelearningmastery.com/lstm-autoencoders/
Training Supervised Autoencoder with MLP - https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/224348 this ties into https://www.kaggle.com/code/gogo827jz/jane-street-supervised-autoencoder-mlp/notebook?scriptVersionId=73762661 and https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/202081 note books are https://www.kaggle.com/code/gogo827jz/jane-street-supervised-autoencoder-mlp/notebook?scriptVersionId=73762661 and https://www.kaggle.com/code/aimind/bottleneck-encoder-mlp-keras-tuner-8601c5/notebook
Like all the neural networks, is a function approximator and as such it tries to globally approximate all the data points we use in the training. This global optimization inherently means that in order to approximate some values better it will have to necessarily loose performance in approximating others. The advantage of using autoencoders is that some of its components, such as the encoder, can be separately trained on several independent stock market returns and then re-used in other end-to-end neural-networks while still keeping the potential to be globally optimized by back-propagation.
Different types are denoising, variational and sparse encoder.
5. Geometric Brownian Motion with Drift Fitting with neural network- https://www.kaggle.com/competitions/jane-street-market-prediction/discussion/226837
