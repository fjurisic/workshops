### Neural Networks Behind the Scenes

This workshop give simple examples of how neural networks embed the outputs of its layers into N-dimensional space, 2D in this case, along with visualizations of class boundaries that are learned from given samples.

It shows some interesting handling of tensorflow (1.X version), and has plenty of options for interactivity, where you can change the code and observe how the outcome changes.

There is also a basic example of adversarial samples at the end.

The workshop can be done without a GPU.

#### Setting up

You are going to need [Anaconda](https://www.anaconda.com/distribution/), or just [miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once you have that installed, open a terminal (Anaconda Powershell Promp as Administrator on Windows) and:
```shell
conda create -n ML python=3.7 numpy tqdm jupyter=1.0.0
conda install -n ML tensorflow-gpu=1.15 pandas matplotlib seaborn
conda activate ML
```

If you don't have a compatible gpu, you can only install `tensorflow` instead of `tensorflow-gpu`.

You can either download the workshop files one by one, or clone the repo with git
```conda install git
git clone ... (you can get clone link on the github page)
```

Then navigate to workshop directory and:
```jupyter notebook```