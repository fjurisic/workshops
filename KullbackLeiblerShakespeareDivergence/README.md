### Kullback-Leibler Shakespeare Divergence

This workshop explains some of the information theory behind log-likelyhood, entropy and KL divergence encountered when training models. After we are done we the theory, we train a RNN model on Shakespeare text, use it to generate some new Shakespearian lines and finally use it to encode and compress text.

The underlying theme of the whole workshop is about the effects of modeling true and approximate distributions of samples, and how being able to predict future better is tied to more efficient compression of information.

The workshop can be done without a GPU.

#### Setting up

This is the setup for first timers. If you already have some environment set up, you just need pytorch, numpy and tqdm.
A GPU is not needed, a pre-trained model is provided here, and CPU is sufficient for inference.

You are going to need [Anaconda](https://www.anaconda.com/distribution/), or just [miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once you have that installed, open a terminal (Anaconda Powershell Promp as Administrator on Windows) and:
```shell
conda create -n ML python=3.7 numpy tqdm jupyter=1.0.0
conda install -n ML pytorch=1.1.0 -c pytorch
conda activate ML
```
You can either download the workshop files one by one, or clone the repo with git
```conda install git
git clone ... (you can get clone link on the github page)
```

Then navigate to workshop directory and:
```jupyter notebook```

#### Acknowledgements

The whole Shakespeare generator was inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).