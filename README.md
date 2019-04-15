# Urban Sound Recognition

## Top Level Files
`supervised_classification.m` - This code reads the 5435 audio files and their labels, runs PCA on extracted 107 features, performs 5 supervised classification with 10-fold cross validation and 80-20 holdout validation.  Classification results are evaluated using confusion matrix.  
`feedforward_nn.m` - Trains feed-forward neural network using spectrogram data.  
`resnet_nn.m` - Trains an 18 layer Residual Network to recognize sounds from spectrogram data.  
`Matlab_Neural_Nets.ipynb` - Jupyter notebook version of neural network stage (view on Github with images/in depth comments)  

NOTE: `resnet_nn.m ` uses the spectrograms created from `feedforward_nn`, so run `feedforward_nn.m` first and do not clear your work space before running `resnet_nn.m`.

## Necessary Software
+ MATLAB
+ Statistics and Machine Learning Toolbox
+ Audio Toolbox
+ Deep Learning Toolbox
+ Parallel Computing Toolbox



