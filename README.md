# lyft_mp_ensemble
Ensembling function for multi-trajectory motion prediction for autonomous vehicles

# Description
This small repository is a follow-up to Lyft Kaggle competition on motion prediction:

[link to competition](https://www.kaggle.com/c/lyft-motion-prediction-autonomous-vehicles)


The code is described in some detail here: [Kaggle forum post](https://www.kaggle.com/c/lyft-motion-prediction-autonomous-vehicles/discussion/199636)

There is also a discussion of the results [here](https://www.kaggle.com/c/lyft-motion-prediction-autonomous-vehicles/discussion/201493#1102803).

The `Ensembling.ipynb` notebook contains two functions
- `ensembleTorch()` iterative procedure for ensembling which converges to at least a local minimum
- `run_ensemble()` takes several individual model submission files and feeds them to the first function

Running of this notebook requires individual model submission files. The first and 9th place shared them in these kaggle datasets: 

* [1st place](https://www.kaggle.com/ilu000/lyft-submission-csvs)
* [9th place](https://www.kaggle.com/zaharch/lyft-submission-csvs-9th-place)
