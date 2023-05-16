# Learning of Process Representations Using Recurrent Neural Networks

## Project Files
----------------------------------
PPT   : https://docs.google.com/presentation/d/1lTgEOD1g5o2w4kFVh9_2ISgENjUCUaqB/edit?usp=sharing&ouid=100321335721317390801&rtpof=true&sd=true

XLSX  : https://docs.google.com/spreadsheets/d/1v9QpH7e7VAu5iVoYAr555sW0STSiOyVe/edit?usp=sharing&ouid=100321335721317390801&rtpof=true&sd=true


## Author's Description
----------------------------------
## Setup
Use Miniconda for the easiest way to setup an environment.

### Using Miniconda
1. Install [Miniconda](https://conda.io/miniconda.html) (make sure to use a Python 3 version)
2. After setting up miniconda you can make use of the `conda` command in your command line (Powershell, CMD, Bash)
3. We suggest that you set up a dedicated environment for this project by running `conda env create -f environment.yml`
    * This will setup a virtual conda environment with all necessary dependencies.
    * If your device does have a GPU replace `tensorflow` with `tensorflow-gpu` in the `environement.yml`
4. Depending on your operating system you can activate the virtual environment with `conda activate replearn` on Linux and macOS, and `activate ad` on Windows (`cmd` only).
5. If you want to make use of a GPU, you must install the CUDA Toolkit. To install the CUDA Toolkit on your computer refer to the [TensorFlow installation guide](https://www.tensorflow.org/install/install_windows).
6. If you want to quickly install the `replearn` package, run `pip install -e .` inside the root directory.
7. Now you can start the notebook server by `jupyter notebook notebooks`.

## Jupyter Notebooks
Check the `notebooks` directory for example Jupyter Notebooks.

## Datasets
- [Synthetic event logs for multi-perspective trace clustering](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/2338)
- [Extended synthetic event logs for multi-perspective trace clustering](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/2415)
