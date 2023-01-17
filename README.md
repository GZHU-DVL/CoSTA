# StarVQAplus
StarVQA+: Co-training Space-Time Attention for Video Quality Assessment
(The code is constantly being updated)
#  Installation

First, create a conda virtual environment and activate it:

```
conda create -n StarVQAplus python=3.7 -y
source activate StarVQAplus
```
Then, install the following packages:

- fvcore: pip install 'git+https://github.com/facebookresearch/fvcore'
- simplejson: pip install simplejson
- einops: pip install einops
- timm: pip install timm
- PyAV: conda install av -c conda-forge
- psutil: pip install psutil
- scikit-learn: pip install scikit-learn
- OpenCV: pip install opencv-python
- tensorboard: pip install tensorboard

Clone this repo.

```
git clone https://github.com/GZHU-DVL/StarVQAplus.git
cd StarVQA
python setup.py build develop
```

Please replace the data path with your local path 
# Pretrain model
[**checkpoint-baidu**](https://pan.baidu.com/s/16z7erijruMTJNYyr2IWwfw) 提取码:87st
