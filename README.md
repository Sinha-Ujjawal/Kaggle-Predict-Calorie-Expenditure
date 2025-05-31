# Kaggle Predict Calorie Expenditure
My Submission for the [Kaggle Playground Prediction Competition (Season 5, Epside 5)](https://www.kaggle.com/competitions/playground-series-s5e5/overview)

## Getting Started

1. Use [conda-forge miniforge](https://github.com/conda-forge/miniforge) for creating the envs. On my Mac M2 setup, I was facing few issues while trying to do it via pip. Specifically, I was having issues with dowhy and econml setup.

```console
conda env create -f ./environment.yml
```

Note - To change the env name, change in [environment.yml](./environment.yml) file

2. Once the env is setup activate

```console
conda activate kaggle-predict-calorie-expenditure
```

3. Open [Analysis.ipynb](./Analysis.ipynb) to follow along.

4. I have already attached the [dataset](./data.tar.gz) as part of the repo.

## Copyrights

Licensed under [@MIT](./LICENSE)

