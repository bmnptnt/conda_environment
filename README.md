# Pytorch for Multi-Label Classification: ML-Decoder

```
> conda create --name multilabel2 -y
> conda activate  multilabel2
> conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.8 -c pytorch -c nvidia
> export CUDA_HOME=$CONDA_PREFI
> sudo apt-get --yes install build-essential
> conda install -c "nvidia/label/cuda-11.8.0" cuda-toolkit
> sudo apt-get --purge remove gcc
> sudo apt-get install --reinstall gcc
> sudo apt-get update
> sudo apt-get install g++
> pip install inplace-abn
> pip install pycocotools
> pip install randaugment
> conda install -c anaconda scikit-learn
> conda install -c anaconda pandas
> conda install -c conda-forge torchinfo
```

# Tensorflow for REBN & MCSR
- RTX 3090(Ti also)
```
> conda create -n tf_2.5 python=3.8
> conda activate tf_2.5
> conda install -c anaconda cudatoolkit
> conda install -c anaconda cudnn
> pip install tensorflow-gpu==2.5.0 
> pip install scikit-learn
> pip install matplotlib
> pip install ipython
> pip install opencv-python (or conda install -c conda-forge opencv)
> pip install scikit-image
> pip install imageio
> pip install ffmpeg

```

- ~~RTX TITAN & 2080(Ti also)~~
```
> conda create -n tf_2.1 python=3.6~~
> conda activate tf_2.1
> conda install -c anaconda cudatoolkit=10.1
> conda install -c anaconda cudnn=7.6.5
> pip install tensorflow-gpu==2.1.0 
> pip install scikit-learn
> pip install matplotlib
> pip install ipython
> pip install opencv-python (or conda install -c conda-forge opencv)
> pip install scikit-image
> pip install imageio
> pip install ffmpeg

```~~
