# workshops
Just some ML related workshops I put together over the years.

## Python environment

If you already have a Python environment, then you just need jupyter and packages in the README of each workshop.
If you are unfamiliar with setting-up an environment I recommend [Anaconda](https://www.anaconda.com/distribution/), or just [miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once you have that installed, open a terminal (Anaconda Powershell Prompt as Administrator on Windows to install packages) and:
```shell
conda create -n ML python=3.7 numpy tqdm jupyter=1.0.0
```

Then you can install individual packages, or sets of them:
```shell
conda install -n ML tensorflow=1.15.0 scikit-learn
```

Finally, activate your environment with:
```shell
conda activate ML
```
From then on, position yourself to a directory where your notebooks are and start jupyter.
```shell
jupyter notebook
```