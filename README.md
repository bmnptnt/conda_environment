# Conda environment, CUDA, CUDNN
### Tensorflow for REBN & MCSR
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

- RTX TITAN & 2080(Ti also)
```
> conda create -n tf_2.1 python=3.6
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

```
