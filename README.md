# Python Test

Test contains 2 parts:
1. pandas test
2. sklearn test

Both parts are done in separate notebooks located in notebooks folders.  
Their html versions are exported to html folder and are available for download

## Set up
___
For reproducibility purpises both parts are created in separate environments.  
To set up environment for pandas test:
```bash
conda env create -f environment_python_test.yml
pip install -f pip_requirements_pyrhon_test.txt
```
To set up environment for sklearn test:
```
conda env create -f environment_scikit_learn.yml
pip install -f pip_requirements_sklearn.txt
```

## Pandas test
___
2 remarks:
* task 7. It seems the word file contained artifacts of 2 different tasks: (1) add new line (2) sort dataframe. This is why the expected output does not match exactly with the required. But the current output is correct.
* task 14. The row selection reproducibility requires knowledge of the seed used for this selection, therefore the output is not exactly the same.

## Sk learn test
___

The task is very general, therefore I tried to construct the reasoning I would follow when working on such task. Due to time constraints and the context of the task (it is a test one, not the production one) I skiped some steps.

The EDA has been done using ydata_profiler (previously called pandas_profiler). The reports have also been put into `html` folder and are available for download.
