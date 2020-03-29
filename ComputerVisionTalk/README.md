### Computer Vision Talk

This is just a notebook I used to generate materials for a presentation about some basics of computer vision related to an art project I was involved in.


#### Setting up

You are going to need [Anaconda](https://www.anaconda.com/distribution/), or just [miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once you have that installed, open a terminal (Anaconda Powershell Promp as Administrator on Windows) and:
```shell
conda create -n ML python=3.7 numpy tqdm jupyter=1.0.0 matplotlib
conda install -n ML pytorch torchvision -c pytorch
conda install -n ML opencv -c conda-forge
conda activate ML
python -m pip install opencv-contrib-python --user
```

You can either download the workshop files one by one, or clone the repo with git
```conda install git
git clone ... (you can get clone link on the github page)
```

Then navigate to workshop directory and:
```jupyter notebook```