# auto_filter
Implementation of the automated filter selection method


# Changes:
2023-08-11
- added the parameter ```axis=1``` to the ```pandas.DataFrame.drop``` methods
- added the parameters ```sampling_strategy='auto'``` and ```replacement=False``` to prevent a future change in ```imblearn.ensemble.BalancedRandomForestClassifier```


# Todo:
- measure the dataset shift
- identify the type of dataset shift
