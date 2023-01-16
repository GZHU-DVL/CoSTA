# StarVQAplus
StarVQA+: Co-training Space-Time Attention for Video Quality Assessment
#  Installation

First, create a conda virtual environment and activate it:

```
conda create -n StarVQA python=3.7 -y
source activate StarVQA
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
git clone https://github.com/GZHU-DVL/StarVQA.git
cd StarVQA
python setup.py build develop
```

Please replace the data path with your local path 
