# MakeIT2025 - What shapes prices in Airbnb?

## Repository 

    This repository contains the code that was used to prepare the presentation  

    **"What shapes prices in Airbnb?"** during the MakeIT2025 conference (28th-30th May 2025)
    
    *.py files are Python files to run in a standard way.  
    *.ipynb files are Jupyter notebooks for running in Colab, OCI DataScience or on-premises Jupyter notebooks installation. 
    The presentation is in PowerPoint format.

## Code

    automl/requirements.txt - required libraries to run examples
            (install with your Python Environment tool, I've used virtualenv)
    airbnb_ShallowTuner_BayesianOptimization_*.py - Select Shallow Model - Random Forest vs SVM, Use BayesianOptimization strategy
        Berlin - automl/airbnb_ShallowTuner_BayesianOptimization_berlin.py
        Munich - automl/airbnb_ShallowTuner_BayesianOptimization_munich.py
        Prague - automl/airbnb_ShallowTuner_BayesianOptimization_prague.py
    airbnb_ShallowTuner_*.py -  Select Shallow Model - Random Forest vs SVM, Use RandomSearch strategy
        Berlin - automl/airbnb_ShallowTuner_berlin.py
        Munich - automl/airbnb_ShallowTuner_munich.py
        Prague - automl/airbnb_ShallowTuner_prague.py
    MLP-Structured-Data-Regression.py - MLP and how we could treat exact architecture as hyperparameter
    airbnb_*_automl_taskapi.py- How to deal with AutoML Functional API
        Berlin - automl/airbnb_berlin_automl_taskapi.py
        Munich - automl/airbnb_munich_automl_taskapi.py
        Prague - automl/airbnb_prague_automl_taskapi.py
    Interpretable ML
        Berlin - notebooks/airbnb_explainable_AI_shap_berlin.ipynb
    Using LASSO regularization on Airbnb data
        notebook/What_shapes_AirBnb_prices.ipynb