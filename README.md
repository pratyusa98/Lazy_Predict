# Lazy_Predict
![ml](https://i.ytimg.com/vi/VCm8Rr9r8ug/maxresdefault.jpg)

### What is LazyPredict?

LazyPredict is an open-source Python library that automates the model training pipeline and speeds up the workflow. LazyPredict trains around 30 classification models for a classification dataset and trains around 40 regression models for a regression dataset.

LazyPredict returns with the trained models along with its performance metric without writing much code. One can compare the performance metrics of each model and tune the best model to further improve the performance.

Installation:
LazyPredict can be installed from the PyPl library using:
      
      pip install lazypredict
      
Post-installation, one can import the library to perform auto-training of classification and regression models.

    from lazypredict.Supervised import LazyRegressor, LazyClassifier
    
    Boston Housing (Regression) and Breast_Cance (Classification) dataset are used for the demonstration of the LazyPredict library.
