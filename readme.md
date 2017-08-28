# Zillow Prize: Zillow's Home Value Prediction (Zestimate)

Workflow for the Kaggle competition Zillow Prize using GBM methods (XGBoost and LightGBM).

### Files

```sh
├── input
│   ├── properties_2016.csv
│   ├── train_2016_v2.csv
│   └── zillow_data_dictionary.xlsx
├── notebooks
│   ├── eda.ipynb
│   ├── full_model.ipynb
│   ├── parameter_tuning_localCV.ipynb
│   └── xgboost.ipynb
├── readme.md
└── submissions
    ├── submission.csv
```

### Requirements

I did all development with cpu versions of XGBoost and LightGBM using python 3.6. Please refer to a version of the ```requirements.txt``` file with versions of packages that should work with these notebooks.

### Data 

For the paths in the notebooks the data collected from the Kaggle download should be saved in a ```input/``` directory as is. 

### Resources 

<strong> Thank you all! </strong>Without the hard work from the open source and kaggle communities none of this could be a possibility.

* http://xgboost.readthedocs.io/en/latest/ 

* http://lightgbm.readthedocs.io/en/latest/  

* http://scikit-learn.org/stable/ 

* https://www.slideshare.net/odsc/owen-zhangopen-sourcetoolsanddscompetitions1 

* https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/ 

* https://www.kaggle.com/sidharthkumar/trying-lightgbm 

* https://www.kaggle.com/yuqingxue/lightgbm-85-97 

* https://www.kaggle.com/aharless/lightgbm-with-outliers-remaining 

* https://www.kaggle.com/jamesdhope/zillow-ensemble-of-regressors-0-065 

* https://www.kaggle.com/nikunjm88/creating-additional-features/ 

#### Contact

Brandon Serna // [bserna@regis.edu](mailto:bserna@regis.edu)
