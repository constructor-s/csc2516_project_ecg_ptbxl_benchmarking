# Set up

## Download this repo

Clone the `csc2516` branch (make sure to use `csc2516` branch)

```shell
git clone --branch csc2516 https://github.com/constructor-s/csc2516_project_ecg_ptbxl_benchmarking.git`
```

## Minimal dependencies

The `wfdb` dependency is required

```shell
conda install wfdb
```

## Download data

Switch to the root directory of this repo, then download

```shell
cd csc2516_project_ecg_ptbxl_benchmarking
./get_datasets.sh
```

Best run on a UNIX-like environment. Requires `wget`, `unzip`, and `python`. This will take a while to download and unpack...

# Afterwards

Now you should be able to run the notebook `code/basics.ipynb`. Copy this notebook and create your own sub-class of `ClassificationModel`
